python-Wappalyzer
=================

This is a fork of https://github.com/chorsley/python-Wappalyzer.

The original creator is no longer maintaining the library.

```
pip install git+https://github.com/reznok/python-Wappalyzer
```

```
>>> from Wappalyzer.Wappalyzer import Wappalyzer,WebPage
>>> wappalyzer = Wappalyzer.latest()
>>> webpage = WebPage.new_from_url('https://github.com')
>>> wappalyzer.analyze(webpage)
{'GitHub Pages', 'Ruby', 'Bootstrap', 'jQuery', 'jQuery-pjax', 'Ruby on Rails'}
```
