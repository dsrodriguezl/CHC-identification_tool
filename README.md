# CHC-identification_xlsx-tool

Here I have developed an excel file tool for aiding the process of identifying insect cuticular hydrocarbons (CHC).
The Excel file is divided in three pages, CHC-Identification, Carlson(1998)-methyl alkanes, and post-DMDS.

The CHC-Identification page is the main tool, it relies on several formulas, conditional formatting, and data validation settings to display/indicate the user the total mass diagnostic ions (Tm), as well as the fragmentation diagnostic ions of hydrocarbons with specified molecular traits (e.g. chain length). It can also indicate the position of methylation(s) for mono-, di-, and trimethyl-branched alkanes of a given chain length, if the theoretical fragmentation ions are provided by the user.

The Carlson(1998)-methyl alkanes displays two figures on the elution pattern of mono-, di-, tri- and tetramethyl-branched alkanes of the same chain length (33 carbons), which have been taken from Carlson _et. al_ (1998) paper (The link to the paper is included in the page as source). This figures are helpful in the process of identifying methyl-branched alkanes, and complementary to the CHC-identification tool of the first page.

The Post-DMDS page is to be used, as its name suggests, after a DMDS derivatization. These page is empty, but the plan is to set it similarly to the first page, its purpose would be aiding to determine the position of unsaturation(s) in the hydrocarbon chain lengths of alkenes (maybe also alkadienes) which requires the derivatization of the sample.

## How to use it?

When you open the XLSX file at first, you get a message asking to open it as a read-Only file. Accept this, in the Read-Only mode you can still edit the data input cells to use the tool, but no modification will be saved, so you cannot alter the functioning of the formulas and settings in which the tools relies.

Note: Here is assumed that you will be using Microsoft office software (i.e. Excel) to operate the XLSX tool.

### CHC-Identification
After you open the file you will see the first page, which is called CHC-Identification. Here you can see some explanatory text and several tables, with different types of cells (regarding their color).

The two type of cells are the information display cells (yellow/dark purple) and data input cells (blue).
The information display cells, as their name indicates, display information in response to the input you provide on the data input cells. They contain formulas that operate with the input provided in the corresponding input cell(s), and due to a conditional formatting rules they change between from purple to yellow, to indicate that they are showing information from a complete input (i.e. The information you provided is enough to show relevant information for you to use/interpret).
