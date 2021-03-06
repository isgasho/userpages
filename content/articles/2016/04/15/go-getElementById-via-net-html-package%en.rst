[Golang] getElementById via net/html Package
############################################

:date: 2016-04-15T21:24+08:00
:tags: Go, Golang, DOM, Go net/html, Web Scrape, html
:category: Go
:summary: Equivalent of JavaScript_ getElementById_ via Go_ `net/html`_ package.
:adsu: yes
:og_image: http://www.homeandlearn.co.uk/JS/images/chapter_1/getElementById_2.gif


Introduction
++++++++++++

Equivalent of JavaScript_ getElementById_ via Go_ `net/html`_ package.

Install `net/html`_ package
+++++++++++++++++++++++++++

.. code-block:: bash

  $ go get -u golang.org/x/net/html

getElementById_
+++++++++++++++

.. show_github_file:: siongui userpages content/code/go-net-html-getelementbyid/getelementbyid.go
.. adsu:: 2

Usage & Test:

.. show_github_file:: siongui userpages content/code/go-net-html-getelementbyid/getelementbyid_test.go
.. adsu:: 3

.. rubric:: `Run Code on Go Playground <https://play.golang.org/p/Ykl4NAxrbsH>`__
   :class: align-center

----

Tested on: ``Ubuntu Linux 15.10``, ``Go 1.6.1``.

----

References:

.. [1] `jquery iterate over elements - Google search <https://www.google.com/search?q=jquery+iterate+over+elements>`_

.. [2] | `net/html go - Google search <https://www.google.com/search?q=net/html+go>`_
       | `A Simple Web Scraper in Go | Gregory Schier <http://schier.co/blog/2015/04/26/a-simple-web-scraper-in-go.html>`_
       | `golang.org/x/net/html GoDoc <https://godoc.org/golang.org/x/net/html>`_

.. [3] `github.com/PuerkitoBio/goquery - GoDoc <https://godoc.org/github.com/PuerkitoBio/goquery>`_

.. [4] `[Golang] Iterate over All DOM Elements in HTML <{filename}../10/go-iterate-over-all-dom-elements-in-html%en.rst>`_


.. _Go: https://golang.org/
.. _Golang: https://golang.org/
.. _net/html: https://godoc.org/golang.org/x/net/html
.. _JavaScript: https://www.google.com/search?q=JavaScript
.. _getElementById: https://www.google.com/search?q=getElementById
