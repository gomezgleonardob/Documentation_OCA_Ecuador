Facturación Electrónica
#######################

Clientes
========

Factura
~~~~~~~

:guilabel:`Customer invoices` are electronic documents that, when validated, are sent to SRI. These
documents can be created from your sales order or manually. They must contain the following data:

- :guilabel:`Customer`: type the customer's information.
- :guilabel:`Journal`: select the option that matches the printer point for the customer invoice.
- :guilabel:`Document Type`: type document type in this format `(01) Invoice`.
- :guilabel:`Payment Method (SRI)`: select how the invoice is going to be paid.
- :guilabel:`Products`: specify the product with the correct taxes.

.. image:: ecuador/customer-invoice.png
   :align: center
   :alt: Customer invoice for Ecuador.


Nota de Crédito
~~~~~~~~~~~~~~~

The :doc:`Customer credit note <../accounting/customer_invoices/credit_notes>` is an
electronic document that, when validated, is sent to SRI. It is necessary to have a validated
(posted) invoice in order to register a credit note. On the invoice there is a button named
:guilabel:`Credit note`, click on this button to be directed to the :guilabel:`Create credit note`
form, then complete the following information:

- :guilabel:`Credit Method`: select the type of credit method.

  - :guilabel:`Partial Refund`: use this option when you need to type the first number of documents
    and if it is a partial credit note.
  - :guilabel:`Full Refund`: use this option if the credit note is for the total invoice and you
    need the credit note to be auto-validated and reconciled with the invoice.
  - :guilabel:`Full refund and new draft invoice`: use this option if the credit note is for the
    total invoice and you need the credit note to be auto-validated and reconciled with the invoice,
    and auto-create a new draft invoice.

- :guilabel:`Reason`: type the reason for the credit note.
- :guilabel:`Rollback Date`: select the :guilabel:`specific` options.
- :guilabel:`Reversal Date`: type the date.
- :guilabel:`Use Specific Journal`: select the printer point for your credit note, or leave it empty
  if you want to use the same journal as the original invoice.

Once reviewed, you can click on the :guilabel:`Reverse` button.

.. image:: ecuador/add-customer-credit-note.png
   :align: center
   :alt: Add Customer Credit Note for Ecuador.

When the :guilabel:`Partial Refund` option is used, you can change the amount of the credit note and
then validate it. Before validating the credit note, review the following information:

- :guilabel:`Customer`: type the customer's information.
- :guilabel:`Journal`: select the printer point for the customer Credit Note.
- :guilabel:`Document Type`: this is the document type `(04) Credit Note`.
- :guilabel:`Products`: It must specify the product with the correct taxes.

.. image:: ecuador/customer-credit-note.png
   :align: center
   :alt: Customer Credit Note for Ecuador.

Nota de Débito
~~~~~~~~~~~~~~

The :guilabel:`Customer debit note` is an electronic document that, when validated, is sent to SRI.
It is necessary to have a validated (posted) invoice in order to register a debit note. On the
invoice there is a button named :guilabel:`Debit Note`, click on this button to be directed to the
:guilabel:`Create debit note` form, then complete the following information:

- :guilabel:`Reason`: type the reason for the debit note.
- :guilabel:`Debit note date`: select the :guilabel:`specific` options.
- :guilabel:`Copy lines`: select this option if you need to register a debit note with the same
  lines of invoice.
- :guilabel:`Use Specific Journal`: select the printer point for your credit note, or leave it empty
  if you want to use the same journal as the original invoice.

Once reviewed you can click on the :guilabel:`Create Debit Note` button.

.. image:: ecuador/add-customer-debit-note.png
   :align: center
   :alt: Add Customer Debit Note for Ecuador.

You can change the debit note amount, and then validate it. Before validating the debit note, review
the following information:

- :guilabel:`Customer`: type the customer's information.
- :guilabel:`Journal`: select the printer point for the customer Credit Note.
- :guilabel:`Document Type`: this is the document type `(05) Debit Note`.
- :guilabel:`Products`: It must specify the product with the correct taxes.

.. image:: ecuador/customer-debit-note.png
   :align: center
   :alt: Customer Debit Note for Ecuador.


Proveedores
===========

Factura
~~~~~~~

The :guilabel:`Vendor bill` is a non-electronic document for your company, this document is issued
by your vendor when your company generates a purchase.

The bills can be created from the purchase order or manually, it must contain the following
information:

- :guilabel:`Vendor`: type the vendor's information.
- :guilabel:`Bill Date`: select the date of invoice.
- :guilabel:`Journal`: it is the journal for vendor bills.
- :guilabel:`Document Type`: this is the document type `(01) Invoice`
- :guilabel:`Document number`: type the document number.
- :guilabel:`Payment Method (SRI)`: select how the invoice is going to be paid.
- :guilabel:`Products`: specify the product with the correct taxes.

.. image:: ecuador/purchase-invoice.png
   :align: center
   :alt: Purchases for Ecuador.

.. important::
   When creating the purchase withholding, verify that the bases (base amounts) are correct. If you
   need to edit the amount of the tax in the :guilabel:`Vendor bill`, click the :guilabel:`Edit`
   button. Otherwise, from the :guilabel:`Journal Items` tab click the :guilabel:`Edit` button and
   set the adjustment to go where you want.