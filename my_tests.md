# Hillel Calculator Project: Test Documentation

This repository contains test documentation for the **Hillel Calculator** application. The primary goal is to verify the addition functionality for integers within the range of `-99` to `99`
## 📋 Test Cases (Manual Testing)

| ID | Title | Priority |
|:---|:---|:---:|
| **TC-01** | Verify Successful Addition of Positive Integers | High |
| **TC-02** | Verify Error Message for Out-of-Range Input | Critical |
| **TC-03** | Verify "Clear" Button Functionality | Medium |
| **TC-04** | Verify "Random" Button Functionality | Medium |
| **TC-05** | Verify "Rows Up/Down" Buttons Functionality | Low |

---

### TC-01: Verify Successful Addition of Positive Integers
[cite_start]**Description:** Ensure the app correctly adds two valid positive integers[cite: 5].

**Steps:**
1. [ ] Enter `54` in the first input field.
2. [ ] Enter `48` in the second input field.
3. [cite_start][ ] Click the **"Add"** button[cite: 5].

[cite_start]**Expected Result:** - The result field displays `102`[cite: 8].

---

### TC-02: Verify Error Message for Out-of-Range Input
[cite_start]**Description:** Verify that entering numbers outside the range of -99 to 99 triggers a validation error[cite: 4, 11].

**Steps:**
1. [ ] Enter `100` in the first input field.
2. [ ] Enter `5` in the second input field.
3. [ ] Click the **"Add"** button.

[cite_start]**Expected Result:** - Error message appears: `"Please input an Integer between -99 and 99 only"`[cite: 11].
- [cite_start]The input field is highlighted in **red**[cite: 11].

---

### TC-03: Verify "Clear" Button Functionality
[cite_start]**Description:** Check if the "Clear" button resets all fields[cite: 6].

**Steps:**
1. [ ] Enter any valid integers in both fields.
2. [ ] Click **"Add"**.
3. [cite_start][ ] Click **"Clear"**[cite: 6].

[cite_start]**Expected Result:** - Both input fields and the result field are cleared and become **empty**[cite: 6].

---

### TC-04: Verify "Random" Button Functionality
[cite_start]**Description:** Ensure the "Random" button generates integers within the allowed range[cite: 7].

**Steps:**
1. [cite_start][ ] Click the **"Random"** button[cite: 7].

[cite_start]**Expected Result:** - Both fields are populated with random integers between `-99` and `99`[cite: 7].

---

### TC-05: Verify "Rows Up/Down" Buttons Functionality
[cite_start]**Description:** Verify that the arrow buttons change the input value by 1[cite: 8].

**Steps:**
1. [ ] Enter `10` in the first field.
2. [cite_start][ ] Click the **"Up"** arrow once[cite: 8].
3. [cite_start][ ] Click the **"Down"** arrow twice[cite: 8].

[cite_start]**Expected Result:** - Value increments to `11` after the "Up" click[cite: 8].
- [cite_start]Value decrements to `9` after two "Down" clicks[cite: 8].

---
*Created by TylLeiche for QA Portfolio.*
