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

**Steps to reproduce:**

1.Enter the test environment using the agent/underwriter credentials.

2.Select the INPATIENT type of policy

3.Choose the Policy option from the side bar menu

4.Search for the “duration of insurance” field which is not enabled.

**Expected Result:** A field should be enabled allowing you to search by the number of months of every insurance that was created previously.

**Actual Result:** You cannot search since the field is not enabled.


## Bug report #5:

**Title:** You can’t search using the date the policy was created.

**Steps to reproduce:**

1.Enter the test environment using the agent credentials.

2.Select the INPATIENT type of policy

3.Choose the New policy option

4.Introduce the details of the new policy up to the last screen which is the one with information regarding the duration of the contract

5.Skip completing the “Offer starting date” in the last screen.

**Expected Result:** An error should appear telling you that you forgot to complete the “Offer starting date”.

**Actual Result:** You are allowed to create the policy.


## Bug report #6:

**Title:** You can generate the policy without inputing the complete address.

**Steps to reproduce:**

1.Enter the test environment using the agent credentials.

2.Select the INPATIENT type of policy

3.Choose the New policy option

4.Introduce the details of the new policy up to the last screen which is the one with information regarding the duration of the contract

5.Skip completing the name of the street field from the insured address section. 

**Expected Result:** An error should appear telling you that you forgot to complete the address

**Actual Result:** The only error you get is related to the postal code which is not sufficient to correctly identify the exact address of the person insured.


## Bug report #7:

**Title:** If the insured data is the same as the policy holder the data isn’t transferred automatically as it should.

**Steps to reproduce:**

1.Enter the test environment using the agent credentials.

2.Select the INPATIENT type of policy

3.Choose the New policy option

4.Introduce the details regarding the policy holder and proceed to the next step.

5.Choose the affirmative answer button for insured person is the same as the policy holder.

**Expected Result:** The data should be transferred with no problem.

**Actual Result:** You are prompted with an error regarding the name and surname of the person that needs to be completed which results from an error of the transfer of the data introduced earlier.


## Bug report #8:

**Title:** Incorrect data in the footer of policy and offer documents.

**Steps to reproduce:**

1.Enter the test environment using the agent credentials.

2.Select the INPATIENT type of policy

3.Choose the New policy option

4.Introduce the data regarding the client and generate the offer and policy

5.Inspect the .pdf files generated for the offer and policy to see if they match the previous introduced values.

**Expected Result:** The footer should provide information regarding the company

**Actual Result:** The footer doesn’t show the information that we wanted.


## Bug report #9:

**Title:** Wrong type of field completion method for the insured person

**Steps to reproduce:**

1.Enter the Salesforce test environment using the agent credentials.

2.Create a new opportunity 

3.Complete information regarding the policy type.

4.Enter policy holder data

5.Enter insured person data.

**Expected Result:** You should be able to enter the insured data in all the mentioned fields.

**Actual Result:** You are not allowed to choose from a list for the “Relationship with Insured Person” field. Instead you have to the type the values which isn’t correct.


## Bug report #10:

**Title:** Identical citizenship not prompting an error as it should be

**Steps to reproduce:**

1.Enter the Salesforce test environment using the agent credentials.
2.Create a new opportunity 
3.Complete the information regarding the policy type.
4.Enter the policy holder data
5.Enter the insured person data.
6. Reach the FATCA/DAC/CRS introduction step and give an affirmative answer for the tax residence to a different country than Romania.
7.Introduce the first citizenship(the second one is not mandatory and you are not prompted to enter this one too)

**Expected Result:** You shouldn’t be able to introduced the same citizenship in the “Citizenship 1” and “Citizenship 2” fields.

**Actual Result:** You are allowed to enter the same citizenship both fields.


