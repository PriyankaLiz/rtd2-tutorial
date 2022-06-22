Usage
=====

.. _installation:

Installation
------------

To use Lumache, first install it using pip:

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

**You can add it if required for a more flavoursome experience.**
parsley You can add it if required for a more flavoursome experience.
parsley You can add it if required for a more flavoursome experience.
parsley You can add it if required for a more flavoursome experience.

**You can add it if required for a more flavoursome experience.**

parsley You can add it if required for a more flavoursome experience.
parsley You can add it if required for a more flavoursome experience.
parsley You can add it if required for a more flavoursome experience.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

**Removed table class name**

.. list-table:: Ingredients
    :header-rows: 1
    :align: center

    * - Ingredient
      - Veg or Non-Veg
      - Mandatory or not
    * - parsley You can add it if required for a more flavoursome experience.
      - veg. You can add it if required for a more flavoursome experience.
      - Not mandatory. You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience.
    * - thyme You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience.
      - veg
      - Yes You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience.

.. list-table:: Ingredients to be used
    :header-rows: 1
    :class: wy-table-responsive
    :align: center

    * - Ingredient
      - Veg or Non-Veg
      - Mandatory or not
    * - parsley You can add it if required for a more flavoursome experience.
      - veg. You can add it if required for a more flavoursome experience.
      - Not mandatory. You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience.
    * - thyme You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience.
      - veg
      - Yes You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience.

