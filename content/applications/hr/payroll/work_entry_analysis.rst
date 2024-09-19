===================
Work entry analysis
===================

The default :guilabel:`Work entry analysis` report provides an overview of the validated work
entries for the current month. To view this report, navigate to :menuselection:`Payroll app -->
Reporting --> Work Entry Analysis`.

The work entries appear in a pivot table, with the default filters of :guilabel:`Current month:
(Month)(Year)` and :guilabel:`Validated`. The various types of :doc:`work_entries` are listed on the
left-hand side (x-axis), while the :guilabel:`Total` values appear along the top (the y-axis).

To change the displayed view, click :icon:`fa-plus-square` :guilabel:`Total` at the top of the main
column, then click on one of the grouping options. The available options are :guilabel:`Work Entry
Type`, :guilabel:`Employee`, and :guilabel:`Department`. If in a multi-company database, a
:guilabel:`Company` option also appears.

To add a new group to sort the data, click :guilabel:`Add Custom Group`, then click one of the
presented options.

.. tip::
   Wherever a :guilabel:`➕ (plus)` icon appears on a pivot table, the information can be further
   grouped. Click on a :guilabel:`➕ (plus)` icon to reveal the available grouping options.

   Click on a :guilabel:`➖ (minus)` icon anywhere on the pivot table to remove that respective
   grouping.

It is possible to compare the current :guilabel:`Work entry analysis` report to the previous month
or the previous year. To view these comparisons, click the :guilabel:`⬇️ (down arrow)` icon in the
search bar to reveal the various :ref:`filter <payroll/filters>` and grouping options.

In the section titled :guilabel:`Comparison`, click on either :guilabel:`Current Month: Previous
Period` or :guilabel:`Current Month: Previous Year`. The report updates and displays the previous
time period values, as well as the :guilabel:`Variation` between the two.

.. image:: work_entry_analysis/work-entry-comparison.png
   :align: center
   :alt: A pivot table comparing the work entries of the current month and the previous month.

To export the data in an XLSX format, click the :guilabel:`Download xlsx` button, represented by a
:guilabel:`⬇️ (down arrow above a horizontal bar)` icon, located at the far-right of the available
icons. The information is then downloaded into a spreadsheet.

The data can also be inserted into a spreadsheet. Click the :guilabel:`Insert in Spreadsheet` button
and a :guilabel:`Select a spreadsheet to insert your (type of report)` pop-up window appears, asking
which spreadsheet to place the information in. Select an existing spreadsheet or dashboard, or
select a new :guilabel:`Blank spreadsheet`. Click the :guilabel:`Confirm` button to move to a
spreadsheet view with the report added to it.

.. note::
   The work entry analysis spreadsheet is :ref:`stored in the same locations <payroll/doc-storage>`
   as a pivot table.
