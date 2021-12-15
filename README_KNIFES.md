修改版本号
rm -r dist && rm -r build && python3 -m build && python3 -m twine upload dist/*

pip install you-get-knifes --index-url https://pypi.python.org/simple -U