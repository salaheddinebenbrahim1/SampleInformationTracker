# Sample Information Tracker

An Excel workbook for organizing sample records and checking them for common data-entry issues.

## Workbook

Open [SampleInformationTracker.xlsx](SampleInformationTracker.xlsx) in Microsoft Excel or another spreadsheet application that supports `.xlsx` files.

- **Sample Register**: Enter one sample per row. Blue cells are for data entry; the **Data Check** column evaluates the record.
- **Checks**: Shows counts of samples entered, records ready, records needing review, and duplicate IDs.
- **Lists**: Contains the dropdown options used by the register. This sheet is hidden; unhide it in the spreadsheet application to edit the options.

## Entering Records

Start at row 6 in **Sample Register**. Each record can include a sample ID, collection date, sample type, source or location, collector, status, condition, quantity and unit, storage location, checker, check date, and notes. Use a unique sample ID. Dropdowns are provided for sample type, status, condition, and unit.

The **Data Check** column is blank for unused rows, shows **OK** for a complete record that passes its checks, and shows **Review** if a required field is missing, the ID is duplicated, a date is invalid, the quantity is not positive, or a checker is listed without a check date. A check date may be left blank when no checker is listed.

The **Checks** sheet updates from the register. Filters are available on the header row, and the register header remains visible while scrolling.

## Example Data

The workbook includes five fictional example records to demonstrate the fields and checks. Replace or remove them before using the register for real information. The workbook is a general-purpose organizational template, not a validated laboratory or regulatory record system.
