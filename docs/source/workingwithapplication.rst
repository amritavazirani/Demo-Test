========================
Working with Demo Test
========================

In this section, you will learn the following:

* :ref:`Opening Demo Test <openingapp>`

* :ref:`Working with Tables <workingtable>`

* :ref:`Closing Demo Test <closingtest>`

.. _openingapp:

-------------------
Opening Demo Test
-------------------


To open Demo Test, proceed as follows:

1. Double-click the **Demo Test** application icon present on desktop.

2. Click **New Project** to create new project.

The process of opening the application is now complete.


.. _workingtable:

------------------------
Working with Tables
------------------------

To work with tables, proceed as follows:

1. Grid Table:

.. csv-table:: Easy way of creating tables
        :header: "Field", "Description", "Default Value"
        :widths: 10, 30, 10

        "Field 1", "Arbitary Field", "0"
        "Field 2", "Mandatory Field", "1"
        "Field 3", "Optional Field", "2"

2. Check the note below.


.. note:: This is just a test note. It includes link to `external website`_.
.. _external website: http://www.python.org/


.. list-table::
   :widths: 20 20 60
   :header-rows: 1 

   * - Field
     - Type
     - Details
   * - ``correct_map``
     - dict
     - For each problem ID value listed by ``answers``, provides:

       * ``correctness``: string; 'correct', 'incorrect'
       * ``hint``: string; Gives optional hint. Nulls allowed.
       * ``hintmode``: string; None, 'on_request', 'always'. Nulls allowed.
       * ``msg``: string; Gives extra message response.
       * ``npoints``: integer; Points awarded for this ``answer_id``. Nulls allowed.
       * ``queuestate``: dict; None when not queued, else ``{key:'', time:''}``
         where ``key`` is a secret string dump of a DateTime object in the form
         '%Y%m%d%H%M%S'. Nulls allowed.
   * - ``grade``
     - integer
     - Current grade value.
   * - ``max_grade``
     - integer
     - Maximum possible grade value.


.. _closingtest:

------------------------------
Closing Demo Test
------------------------------


To close the application, proceed as follows:

1. Click **Close**.
2. Click Yes to confirm or **No** to cancel.

.. seealso:: This is a simple see also example.

.. warning:: This is a sample warning box.



