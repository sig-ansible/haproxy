while true; do find . -name '*.yml' | entr -c -d ansible-lint tests/test.yml; done
