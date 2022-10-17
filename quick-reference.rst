Block
=====

Paragraph
---------

paragraph 1 text.
text text.

paragraph 2 text.
text text.

Section
-------

-----------------------
title (罫線を上下に配置)
-----------------------

title (罫線を下のみ配置)
-----------------------

罫線には -=*#^~ を使用可
同じ文字・配置で同じレベル

TOC
---

.. contents::

Bullet List
-----------

* item 1
  * item 1-1
    * item 1-1-1
    * item 1-1-2
  * item 1-2
    * item 1-2-1
    * item 1-2-2
* item 2

* new item 1

※シンボルには*+-を使用可能

Ordered List
------------

#. item 1
   #. item 1-1
      #. item 1-1-1
      #. item 1-1-2
   #. item 1-2
      #. item 1-2-1
      #. item 1-2-2
#. item 2

#. new item 1

Description List
----------------

term
  item 1

  term
    item 1-1

    term
      iterm 1-1-1

    term
      iterm 1-1-2

  term
    item 1-2

    term
      iterm 1-2-1

    term
      iterm 1-2-2

term
  item 2


term
  new item 1

Check List
----------

なし

Literal BLock / Preformatted Block
----------------------------------

::

  literal text
  literal text

Block Quote
-----------

paragraph

  text
  text

    text

  text

  new text

paragraph

Code Block
----------

.. code:: lang

   text

Admonition
----------

.. WARNING::
   text

※ATTENTION, CAUTION, DANGER, ERROR, HINT, IMPORTANT, NOTE, TIP, WARNING を指定可能

Horizontal Line
---------------

----

Page Break
----------

なし

Table
-----

====== ====== ======
data11 data12 data13
data21 data22 data23
====== ====== ======

.. table:: 
   :align: left left center write

   +--------+--------+--------+--------+
   | head1  | head2  | head3  | head4  |
   +========+========+========+========+
   | data11 | data12 | data13 | data14 |
   +--------+--------+--------+--------+
   | data21 | data22 | data23 | data24 |
   +--------+--------+--------+--------+

Inline
======

Emphasis
--------

The *emphasis* text.

Strong
------

The **strong** text.

Emhasis + Strong
----------------

なし

Superscript
-----------

The :sup:`super` text.

Subscript
---------

The :sub:`sub` text.

Underline
---------

なし

Strikeout
---------

なし

Line Break
----------

| The line 1.
| The line 2.

Code
----

The ``code`` text.

Quote
-----

なし

Keyboard / Button / Menu
------------------------

Type :kbd:`Ctrl+A`.
Push :guilabel:`OK`.
Select :menuselection:`File --> Quit`.

Hyper Link
----------

`text <url>`_

Cross Reference
---------------

:ref:`Block`

Image
-----

text |name| text

.. |name| image:: url

.. image:: url ※ブロック要素

Footnote
--------

text text.[#1]_
text text.[#2]_
text text.[#2]_

.. [#1] footnote-text
.. [#2] footnote-text

Endnote
-------

なし

Reference / Bibliography
------------------------

text text.[1]_
text text.[2]_
text text.[2]_

.. [1] biblio-text
.. [2] biblio-text

Math
----

:math:`e^{i\pi} + 1 = 0`

No Markup
---------

The \*no strong\* text.
