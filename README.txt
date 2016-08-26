This git repository contains the SPDX License List data used internally by the SPDX legal team to maintain the license license available at http://spdx.org/licenses and in the Github repository spdx/license-list-data.

Since the internal formats are subjct to change, it is strongly recommended to use the license list data available at http://spdx.org/licenses or in the license-list-data git repo (https://github.com/spdx/license-list-data) rather than using the internal formats of the license list.  The license list data is available in HTML, JSON and RDFa formats (see https://github.com/spdx/license-list-data and https://spdx.org/publications/tool-documentation/accessing-spdx-licenses for more details).
 
NOTE: The legal team is planning to replace this repository by a set of XML representations of the licenses.
 

There are two types of files maintained for each release of the license list:

• Spreadsheet:  A spreadsheet file named spdx_licenselist_vX.XX where X.XX is the license list version.  
There are two formats stored, an Microsoft Excel (.xls) file and a Open Office Calc (.ods) file.  The spreadsheet includes a worksheet for the licenses, exceptions, and deprecated licenses.
The current spreadsheet column definition can be found in the Explanation of License List Fields on the License List Overview webpage http://spdx.org/spdx-license-list/license-list-overview.  The spreadsheet may include additional columns (that are not official fields) for the purposes of tracking other work on or changes to the SPDX License List. 

• Text files: The actual text for each license is contained in a text file (.txt) with a filename corresponding to the SPDX License List Identifier. Text for the license exceptions is included in the exceptions worksheet. Some license or exception text may include template markup as specified in the License Matching Guidelines and Appendix II License Matching Guidelines and Templates in the SPDX specification version 1.2 or later.  

Instructions for updating the spdx.org website can be found in the file "Updating the SPDX Licenses.txt"