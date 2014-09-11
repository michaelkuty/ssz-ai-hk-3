
Otázky na státnice AI3 ver. 2014!
==============================================

PROG
===========

.. toctree::
   :numbered:
   :maxdepth: 2

   prog/1
   prog/2
   prog/3
   prog/4
   prog/5
   prog/6
   prog/7
   prog/8
   prog/9
   prog/10
   prog/11
   prog/12
   prog/13

TECH
===========

.. toctree::
   :numbered:
   :maxdepth: 2

   tech/1
   tech/2
   tech/3
   tech/4
   tech/5
   tech/6
   tech/7
   tech/8
   tech/9
   tech/10
   tech/11
   tech/12
   tech/13
   tech/14
   tech/15
   tech/16


Přednášky
--------

* `ZT1`_
* `ZT2`_
* `PSIT4`_

Syntaxe - **reStructuredText**
------

* http://sphinx-doc.org/rest.html
* SublimeText plugin https://sublime.wbond.net/packages/RestructuredText%20Improved
* SublimeText plugin https://github.com/mgaitan/sublime-rst-completion
* dostupné formáty pro export http://sphinx-doc.org/builders.html
* Auto build https://pypi.python.org/pypi/sphinx-autobuild
	* pip install watchdog  
	* watchmedo shell-command --patterns=*.rst --recursive --command='sphinxuild -b html ./source/ ./' 
* pro build bootstrap skinu *pip install sphinx_bootstrap_theme*

Jak přispět ?
------

1. Fork na githubu
2. Editace v source/..
3. Build sphinx-build -b html ./source/ ./
4. Pull request

Většina textů převzata a upravena z http://ai-fim-uhk.wikispaces.com/

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. _ZT1: https://github.com/michaelkuty/ssz-ai-hk-3/tree/gh-pages/source/prednasky/zt1/
.. _ZT2: https://github.com/michaelkuty/ssz-ai-hk-3/tree/gh-pages/source/prednasky/zt2/
.. _PSIT4: https://github.com/michaelkuty/ssz-ai-hk-3/tree/gh-pages/source/prednasky/psit4/
