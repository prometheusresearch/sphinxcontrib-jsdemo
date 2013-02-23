HTML/Javascript Demos
=====================

This document demonstrates usage of the ``demo`` directive.

Regular layout
--------------

.. demo::

   <button style="color: green">Regular layout</button>

Source first
------------

.. demo::
   :layout: source, demo

   <button style="color: brown">Source first</button>

Hidden source
-------------

.. demo::
   :layout: +demo, -source

   <button style="color: red">Hidden source</button>

Hidden demo
-----------

.. demo::
   :layout: +source, -demo

   <button style="color: magenta">Hidden demo</button>

No source
---------

.. demo::
   :layout: demo

   <button style="color: blue">No source</button>


