| Test Case ID | TC-001 |
|-------------|-------------------------------|
| **Test Description** | Verify the addition of two positive integers. |
| **Preconditions** | Calculator should be open and operational. |
| **Test Steps** | 1. Enter `5`. <br> 2. Enter `3`. <br> 3. Click `+`. <br> 4. Click `=`. |
| **Expected Result** | The result should be `8`. |

| Test Case ID | TC-002 |
|-------------|-------------------------------|
| **Test Description** | Verify the addition of a positive and a negative integer. |
| **Preconditions** | Calculator should be open. |
| **Test Steps** | 1. Enter `10`. <br> 2. Enter `-7`. <br> 3. Click `+`. <br> 4. Click `=`. |
| **Expected Result** | The result should be `3`. |

| Test Case ID | TC-003 |
|-------------|-------------------------------|
| **Test Description** | Verify subtraction of two positive numbers. |
| **Preconditions** | Calculator should be open. |
| **Test Steps** | 1. Enter `10`. <br> 2. Enter `4`. <br> 3. Click `-`. <br> 4. Click `=`. |
| **Expected Result** | The result should be `6`. |

| Test Case ID | TC-004 |
|-------------|-------------------------------|
| **Test Description**| Verify subtraction when the second number is larger. |
| **PreConditions** | Calculator should be open .|
| **Test Steps** | 1. Enter `3`.<br> 2. Enter `7` .<br> 3.Click `-`.<br> 4. Click `=`.|
|**Expected Result**| The result should be `-4`.|

| Test Case ID | TC-005 |
|-------------|-------------------------------|
| **Test Description** | Verify multiplication of two positive integers. |
| **Preconditions** | Calculator should be open. |
| **Test Steps** | 1. Enter `6`. <br> 2. Enter `4`. <br> 3. Click `×`. <br> 4. Click `=`. |
| **Expected Result** | The result should be `24`. |

| Test Case ID | TC-006 |
|-------------|-------------------------------|
| **Test Description** | Verify multiplication by zero. |
| **Preconditions** | Calculator should be open. |
| **Test Steps** | 1. Enter `9`. <br> 2. Enter `0`. <br> 3. Click `×`. <br> 4. Click `=`. |
| **Expected Result** | The result should be `0`. |

| Test Case ID | TC-007 |
|-------------|-------------------------------|
| **Test Description** | Verify division of two positive numbers. |
| **Preconditions** | Calculator should be open. |
| **Test Steps** | 1. Enter `10`. <br> 2. Enter `2`. <br> 3. Click `÷`. <br> 4. Click `=`. |
| **Expected Result** | The result should be `5`. |

| Test Case ID | TC-008 |
|-------------|-------------------------------|
| **Test Description** | Verify handling of division by zero. |
| **Preconditions** | Calculator should be open. |
| **Test Steps** | 1. Enter `8`. <br> 2. Enter `0`. <br> 3. Click `÷`. <br> 4. Click `=`. |
| **Expected Result** | The calculator should display `"Cannot divide by zero"`. |

| Test Case ID | TC-009 |
|-------------|-------------------------------|
| **Test Description** | Verify handling of non-numeric characters. |
| **Preconditions** | Calculator should be open. |
| **Test Steps** | 1. Enter `A`. <br> 2. Enter `5`. <br> 3. Click `+`. <br> 4. Click `=`. |
| **Expected Result** | The calculator should display `"Invalid input"`. |

| Test Case ID | TC-010 |
|-------------|-------------------------------|
| **Test Description** | Verify behavior when multiple operators are entered in sequence. |
| **Preconditions** | Calculator should be open. |
| **Test Steps** | 1. Enter `5`. <br> 2. Click `+`. <br> 3. Click `-`. <br> 4. Click `×`. <br> 5. Click `=`. |
| **Expected Result** | The calculator should show `"Invalid operation"`. |

| Test Case ID | TC-011 |
|-------------|-------------------------------|
| **Test Description** | Verify correct evaluation using BODMAS (Bracket, Order, Division, Multiplication, Addition, Subtraction). |
| **Preconditions** | Calculator should support BODMAS rule. |
| **Test Steps** | 1. Enter `5 + 2 × 3`. <br> 2. Click `=`. |
| **Expected Result** | The calculator should first multiply (`2 × 3 = 6`), then add (`5 + 6 = 11`). The output should be `11`. |



