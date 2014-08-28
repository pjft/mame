# rvest

[![Build Status](https://travis-ci.org/hadley/rvest.png?branch=master)](https://travis-ci.org/hadley/rvest)

rvest helps you scrape information from web pages. It currently provides two main features:

* Select parts of a document using css selectors: `html_node(doc, "table td")`

* Extract important components of html tags with `html_tag()`, `html_text()`,
  `html_attr()` and `html_attrs()`.

* Parse tables into data frames with `html_table()`.

* Extract, modify and submit forms with `html_form()`, `set_values()` and
  `submit_form()`

* Navigate around a website as if you're in a browser with `html_session()`,
  `jump_to()`, `follow_link()`, `back()`, `forward()`, `submit_format()` and
  so on.

To see examples of these function in use, check out the demos.

# Inspirations

* Python: [Robobrowser](http://robobrowser.readthedocs.org/en/latest/readme.html)
