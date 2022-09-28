Dashboard
=====

.. _Overview:

Què és el Dashboard?
------------

El **DASHBOARD** és tracta d'un panell visor que permet la visualització d'informació molt variada. És possible veure'n gràfics i resums sobre l'activitat actual en temps real. Permet veure totes les incidències dels VIALS. És personalitzable, tot i així s'ha d'activar en funció de l'usuari que en fa ús.


Imatges
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

