
Factory Rationale
=================

Both the ``master`` and ``develop`` branch are supposed to be working for
people at all times. For experiments in the context of issues and generally
features not yet ready for prime time, there we have personal branches.

You have probably come here, because you were asked to checkout a change made
for you on ``factory`` or ``jorj``.

How to get ``factory``
======================

git
---

.. code-block:: sh

   git clone --branch factory http://git.nuitka.net/Nuitka.git

pip
---

.. code-block:: sh

   pip install -U "https://github.com/Nuitka/Nuitka/archive/factory.zip"


How to get ``jorj``
===================

git
---

.. code-block:: sh

   git clone --branch jorj http://git.nuitka.net/Nuitka.git

pip
---

.. code-block:: sh

   pip install -U "https://github.com/Nuitka/Nuitka/archive/jorj.zip"


Word of Warning
===============

These personal branches may include all kinds of stupid mistakes, e.g. not
being executable with all versions, crashing, not working at all. They also
frequently change without notice. So please use it only for the issue at hand
or even more than usually on your own risk.

Once confirmed and found good, fixes will normally appear on develop branch
relatively shortly, try to use those instead from then on.
