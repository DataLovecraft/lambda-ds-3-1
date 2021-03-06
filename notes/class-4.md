

# Notes and Reference Materials - Class 4


Lambda Materials:
  + https://learn.lambdaschool.com/ds/module/recq9eVVCzZpgeH58/
  + https://github.com/LambdaSchool/DS-Unit-3-Sprint-1-Software-Engineering/tree/master/module4-software-testing-documentation-and-licensing

(BONUS / FYI) Testing Notes:
  + https://github.com/prof-rossetti/intro-to-python/blob/master/notes/software/testing.md

(BONUS / FYI) Previous Lecture and Materials on Testing:
  + https://www.youtube.com/watch?v=pS8pzmtqxVA
  + https://github.com/prof-rossetti/lambda-lecture-pytest

See also the [example test code](/test/).

## Part I

Testing Frameworks (Unittest):
  + https://docs.python.org/3.5/library/unittest.html

Running tests:

```sh
python -m unittest test.team_test
```

> NOTE: may need to add "`__init__.py`" files to both the "app" and "test" directories for this to work from the root directory

## Part II

Testing Frameworks (Pytest):
  + https://docs.pytest.org/en/latest/
  + (FYI / BONUS) https://github.com/prof-rossetti/intro-to-python/blob/master/notes/python/packages/pytest.md
  + (FYI / BONUS) https://github.com/prof-rossetti/intro-to-python/tree/master/exercises/testing-123

(BONUS / FYI) More Pytest resources:
  + https://github.com/prof-rossetti/intro-to-python/blob/master/notes/python/packages/pytest.md
  + https://github.com/prof-rossetti/intro-to-python/tree/master/exercises/testing-123

Installing pytest as a development dependency:

```sh
pipenv install pytest --dev
```
Running tests:

```sh
pytest
```

## Part III

(BONUS / FYI) Continuous Integration:
  + https://travis-ci.com/
  + https://travis-ci.com/s2t2/playlist-service-py/builds/142617662
  + https://github.com/s2t2/playlist-service-py/pull/7
  + https://github.com/prof-rossetti/intro-to-python/blob/master/notes/devtools/travis-ci.md
  + https://github.com/prof-rossetti/intro-to-python/tree/master/exercises/ci-123
