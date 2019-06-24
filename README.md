# salad-browserstack

A sample to run salad tests over BrowserStack Automate.

1. First install depenedencies:
* sudo pip install nose
* sudo pip install salad
* sudo pip install selenium

To run the tests, add you credentials to `features/terrain.py` and execute(from root of project):

```sh
salad
```


__NOTE: Currently `lettuce` is not compatible with Python 3. For more info check this issue [link](https://github.com/gabrielfalcao/lettuce/issues/458)__

