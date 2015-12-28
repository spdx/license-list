This git repository contains the SPDX License List input data files.

There are two types of files maintained for each release of the license list:

• Spreadsheet:  A spreadsheet file named spdx_licenselist_vX.XX where X.XX is the license list version.  
There are two formats stored, an Microsoft Excel (.xls) file and a Open Office Calc (.ods) file.  The spreadsheet includes a worksheet for the licenses, exceptions, and deprecated licenses.
The current spreadsheet column definition can be found in the Explanation of License List Fields on the License List Overview webpage http://spdx.org/spdx-license-list/license-list-overview.  The spreadsheet may include additional columns (that are not official fields) for the purposes of tracking other work on or changes to the SPDX License List. 

• Text files: The actual text for each license is contained in a text file (.txt) with a filename corresponding to the SPDX License List Identifier. Text for the license exceptions is included in the exceptions worksheet. Some text may including template markup as specified in the License Matching Guidelines and Appendix II License Matching Guidelines and Templates in the SPDX specification version 1.2 or later.  

Instructions for updating the spdx.org website can be found in the file "Updating the SPDX Licenses.txt"