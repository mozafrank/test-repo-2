
sphinx-quickstart -q -a 'Adam Frank <afrank@mozilla.com>' -v '0.0.1' --ext-autodoc --ext-coverage --ext-doctest --ext-githubpages -p cloudsecrets docs
sphinx-apidoc -f -o docs ./

sphinx-build -b html docs build
