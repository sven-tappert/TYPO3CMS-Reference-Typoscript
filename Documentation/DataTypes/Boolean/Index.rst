.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../../Includes.txt


.. _data-type-boolean:
.. _data-type-bool:

boolean
=======

.. container:: table-row

   Data type
         boolean

   Examples
         1

   Comment
         Possible values for boolean variables are "1" and "0"
         (meaning "TRUE" and "FALSE").

         Everything else is `evaluated to one of these values by PHP`__:
         Non-empty strings (but not "0") are treated as "TRUE",
         empty strings are evaluated to FALSE.

         __ http://php.net/manual/en/language.types.boolean.php

         Examples::

            dummy.enable = 0            # false, preferred notation
            dummy.enable = 1            # true, preferred notation
            dummy.enable =              # false, because the value is empty


