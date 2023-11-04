# Bug Reports

## Bug report #1:

**Title:** Can’t revert the option if you accidentally cancel a policy 

**Steps to reproduce:**

1.Enter the test environment using the underwriting credentials.

2.Select the INPATIENT type of policy

3.Choose the Offer option from the side bar menu

4.Select the policy you want to revert from the cancelled state

5.Press the button to revert to the previous state.

**Expected Result:** The policy moves back to the active state.

**Actual Result:** The following error is generated.


## Bug report #2:

**Title:** BMI field accepts negative values

**Steps to reproduce:**

1.Enter the test environment using the agent credentials.

2.Select the INPATIENT type of policy

3.Choose the New Offer option from the side bar menu

4.Start introducing the data regarding the client and move to the next step in the process

5.Select the affirmative answer for the first question of the medical questionnaire and introduce negative values for Height and Weight to determine the BMI for the client.

**Expected Result:** You receive an error message that shows you are not allowed to have negative values for height and weight

**Actual Result:** The BMI value is calculated as a negative value and lets you procede to the next step.

