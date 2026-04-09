\# Hillel Calculator Project: Test Documentation



This repository contains test documentation for the \*\*Hillel Calculator\*\* application. The goal is to verify that the app correctly adds integers within the range of `-99` to `99`.



\## 📋 Test Cases (Manual Testing)



| ID | Title | Priority |

|:---|:---|:---:|

| \*\*TC-01\*\* | Verify Successful Addition of Positive Integers | High |

| \*\*TC-02\*\* | Verify Error Message for Out-of-Range Input | Critical |

| \*\*TC-03\*\* | Verify "Clear" Button Functionality | Medium |

| \*\*TC-04\*\* | Verify "Random" Button Functionality | Medium |

| \*\*TC-05\*\* | Verify "Rows Up/Down" Buttons Functionality | Low |



\---



\### TC-01: Verify Successful Addition of Positive Integers

\*\*Description:\*\* Ensure the app correctly adds two valid positive integers.



\*\*Steps:\*\*

1\. \[ ] Enter `54` in the first input field.

2\. \[ ] Enter `48` in the second input field.

3\. \[ ] Click the \*\*"Add"\*\* button.



\*\*Expected Result:\*\* - The result field must display `102`.



\---



\### TC-02: Verify Error Message for Out-of-Range Input

\*\*Description:\*\* Check validation when a user enters a number greater than 99.



\*\*Steps:\*\*

1\. \[ ] Enter `100` in the first input field.

2\. \[ ] Enter `5` in the second input field.

3\. \[ ] Click the \*\*"Add"\*\* button.



\*\*Expected Result:\*\* - Error message appears: `"Please input an Integer between -99 and 99 only"`.

\- The input field is highlighted in \*\*red\*\*.



\---



\### TC-03: Verify "Clear" Button Functionality

\*\*Description:\*\* Check if the form resets correctly.



\*\*Steps:\*\*

1\. \[ ] Enter `10` and `20` in the input fields.

2\. \[ ] Click \*\*"Add"\*\*.

3\. \[ ] Click \*\*"Clear"\*\*.



\*\*Expected Result:\*\* - Both input fields and the result field are \*\*empty\*\*.



\---



\### TC-04: Verify "Random" Button Functionality

\*\*Description:\*\* Ensure the "Random" button generates values within the allowed range.



\*\*Steps:\*\*

1\. \[ ] Click the \*\*"Random"\*\* button.



\*\*Expected Result:\*\* - Both fields are filled with integers between `-99` and `99`.



\---



\### TC-05: Verify "Rows Up/Down" Buttons Functionality

\*\*Description:\*\* Check manual increment/decrement of values.



\*\*Steps:\*\*

1\. \[ ] Enter `10` in the first field.

2\. \[ ] Click the \*\*"Up"\*\* arrow button.

3\. \[ ] Click the \*\*"Down"\*\* arrow button twice.



\*\*Expected Result:\*\* - Value becomes `11` after the first click.

\- Value becomes `9` after the final click.



\---

\*Created with ❤️ by TylLeiche as part of QA Learning Path.\*

