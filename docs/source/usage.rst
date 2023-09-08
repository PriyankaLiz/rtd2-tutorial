Usage
=====

.. _installation:

Installation - Test with max width
----------------------------------

To use Lumache, first install it using pip:

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

.. _ABC-555:

Testing Uppercase in Tags
-------------------------

Testing

.. _CREATEREC:

Creating recipes - Test with max width
--------------------------------------

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

**TEST WITH BREAK-WORD**

.. list-table:: Ingredients
    :header-rows: 1
    :align: center

    * - Ingredient
      - Veg or Non-Veg
      - Mandatory or not
    * - PARSLEY_VEG_THYME_ROSEMARY
      - PARSLEY_VEG_THYME
      - Not mandatory. You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience.
    * - PARSLEY_VEG_THYME_ROSEMARY_BASIL
      - PARSLEY_VEG_THYME, PARSLEY_VEG_THYME_ROSEMARY, PARSLEY_VEG_THYME_ROSEMARY_BASIL
      - Not mandatory. You can add it if required for a more flavoursome experience. You can add it if required for a more flavoursome experience.

**Removed table class name**

parsley You can add it if required for a more flavoursome experience.
parsley You can add it if required for a more flavoursome experience.


.. list-table:: Ingredients
    :header-rows: 1
    :align: center

    * - Ingredient_Ingredient_Ingredient_Veg_NonVeg
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

.. list-table:: Ingredients Not to be used
    :header-rows: 1
    :class: wy-table-responsive
    :align: center

    * - Ingredient
      - Veg_or_Non-Veg_Veg_Nonveg_Nonveg
      - Only_Mandatory_orOnly_Optional_or_Both
    * - parsley You can add it if required for a more flavoursome experience.
      - veg. You can add it if required for a more flavoursome experience.
      - Not mandatory. You can add it if required for a more flavoursome experience.
