# python_packages_index

This is the Clevyr python package index.

You can use pip to install packages from this repo with the following syntax:

`pip install test_package --extra-index-url=https://clevyr.github.io/python_packages_index/`

If you want to leave off the --extra-index-url flag, you can run the following commands to add it to your pip config:

```
pip config --user set global.extra-index-url https://clevyr.github.io/python_packages_index
pip config --user set global.trusted-host clevyr.github.io
```

Currently, adding a new package to the repo is a manual process. Either review the simple html of this repo and follow the same pattern, and/or review this [blog-post](https://www.freecodecamp.org/news/how-to-use-github-as-a-pypi-server-1c3b0d07db2/)

Happy Coding!
