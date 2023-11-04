#List of Bug Reports:

## Bug Report #1:

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


## Bug report #3:

**Title:** You can’t search for an older policy generated in the system which is eligible for renewal ( every policy is eligible for renewal starting within 30 days until it’s year anniversary).

**Steps to reproduce:**

1.Enter the test environment using the administrator credentials.

2.Select the INPATIENT type of policy

3.Choose the New Offer option from the side bar menu

4.Start introducing the policy number in the renewal field 

5.Press the search button in order to find the eligible policy.

**Expected Result:** You are not able to find it and the system gives you an erorr.

**Actual Result:** You are able to find it and the system redirects you to the policy details.


## Bug report #4:

**Title:** “Duration of the insurance” field is missing so we can’t search by using it as a criteria.

1.Enter the test environment using the agent/underwriter credentials.

2.Select the INPATIENT type of policy

3.Choose the Policy option from the side bar menu

4.Search for the “duration of insurance” field which is not enabled.

**Expected Result:** A field should be enabled allowing you to search by the number of months of every insurance that was created previously.

**Actual Result:** You cannot search since the field is not enabled.


## Bug report #5:

**Title:** “Duration of the insurance” field is missing so we can’t search by using it as a criteria.

1.Enter the test environment using the agent credentials.

2.Select the INPATIENT type of policy

3.Choose the New policy

4.Introduce the details of the new policy up to the last screen which is the one with information regarding the duration of the contract

5.Skip completing the “Offer starting date” in the last screen.

**Expected Result:** An error should appear telling you that you forgot to complete the “Offer starting date”.

**Actual Result:** You are allowed to create the policy.



