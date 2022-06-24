1. Test Runner: unittest, nose or nose2, pytest
2. Multiple env: tox
3. CI/CD: Travis
4. Linter: flake8, black
5. Peformance: pytest-benchmark
6. Security Flaws: bandit
``` python
if __name__ == '__main__':
    unittest.main()

or 

python -m unittest test

python3 -m unittest -v test

python3 -m unittest discover # search current dir for any files with test*.py

python -m unittest discover -s tests # search tests dir of root for any files with test*.py

python -m unittest discover -s tests -t src # search tests dir of src for any files with test*.py



```


### References
https://realpython.com/python-testing/#automated-vs-manual-testing
