# SOP for managing WISE github issues (DRAFT)

Note: In general this is the SOP for Issues and Pipleines may change but the spirit of the SOP should remain inteact.

The Project Executive is currently made up of:
- Neal McLoughlin 
- Brett Moore
- Franco Nogarin

## Using ZenHub
For issue administration the Executive will use ZenHub, which is a browser plugin/Web Service that builds upon Github and Github Issues.


### performing TRIAGE

When an issue is created it is initially made with the TRIAGE label, this is to indicate the first round of issue management needs to be performed. 
Someone on the exec will see new issues marked TRIAGE, and perform TRIAGE on the issue.

## DOING TRIAGE

- Determine who the issue should be assigned to and asssign it.
- IF the issue is a task 
  - move it to the approrpiate pipeline
  - make a comment directed to the asignee and indicate why you assigned it to them and what is expected.
  - Add appropriate labels
- IF the issue is a Bug or Enhancement
  - move it to the approrpiate pipeline
  - Add the label "Needs Plan" 
  - Assign it to a developer(s) 
  - make a comment directed to the asignee(s) and indicate why you assigned it to them and what is expected.
  - IF the issue additionaly needs executive input, 
    - add the label "Needs Discussion"
    - Add a comment referncing the execs by name and ask for comment

## Developer Plan

When a developer is assigned an issue marked "Needs Plan"

- Devoper submits a plan (An approach to achieve the goal) as a comment to the issue
  - The plan does not need to be elaborate BUT must hold enough information for the exec to determine if the plan is viable and perferably without causing to much back and forth of questions.   
- Developer removes the needs plan label 
- assign back to exec

## Exec Plan Review

- Exec reviews the proposal
- IF the Exec is not happy with the plan, they will dialog back and forth with the developer in the issue until they are content. Remember it is public.
- Exec approves the approach in comments 
- Exec asks for an estimate (Number of Effort Hours) by adding label "Needs Estimate"
- Exec assigns back to Developer.

## Developer Estimate
The developer needs to estimate the number of work hours the plabn outlines will take
- developer Adds estimate to the issue (Using the estimate field in the issue)
- Developer removes the "Needs Estimate" label and assigns back to exec.

## Exec Estimate Review
The exec will review and discuss the estimate, if the Hours are too much, it will be rejected
- Exec approves the estimate in comments
- Exec asks for a Quote (Detailed breakdown of hours - emailed to section lead - Not posted in these tickets) by adding the "Needs quote" label
- Exec assigns back to Devloper.

## Developer Quote
The developer must then do a formal quote indicating the Estimate and the Plan, and breaking down expenses, the quote must include build costs, rates for developer hours and GST.
- Developer Emails an estimate to the lead
- Developer removes the "Needs Quote" label 
- Developer adds the "Needs Approval" Label 
- Developer assigns the issue back to the Exec

## Exec Quote Review
The Exec reviews the quote and will ether reject it, ask for a revision or approve it
- Exec Revews the quote as a group and based on concensus approves
- Exec removes the "Needs Approval" label
- Exec adds the "Approved" label
- Exec moves the issue to the correct backlog.

## Developer Works the Issue to completion
The Developer then works the issue to completion, then either marks of for testing or for signoff.
- IF The issue needs testing
  - Developer removes "Approved" label
  - Developer adds "Needs Testing" Label
  - Assign to either a tester or Exec 
  - Explain the testing required and instructions in a comment mentioning the assignee
  - Provide the data required for testing (FGM, kml or Whatever) by attatching to the issue.
  - Developer Moves it to the "Testing" Pipeline.
- IF The issue is fully finished by the developer and needs no testing
  - Developer removes "Approved" label
  - Developer adds "Needs Signoff" Label
  - Developer Moves it to the "Work Signoff" Pipeline.


 ## Testing the issue
 When an issue needs testing it is marked as "needs testing" and is found in the "Testing" Pipeline.
 If the issue is assigned to the Exec, the issue will either be tested by the Exec or Assigned to a tester to complete the work.

- Tester tests the issue as per testing instructions and data provided. 
- IF Testing passes
  - Tester documents test results in the issue 
  - Tester adds the label "Testing Passed"
  - Tester removes the "Needs Testing" Label
  - Tester adds the label "Needs Signoff"
  - Tester Moves it to the "Work Signoff" Pipeline.
  - Assign to the exec
- IF Testing Fails
  - Tester documents test failure in the issue 
  - Tester adds the label "Testing Failed"
  - Tester assigns back to the developer


  ## When testing fails
  When tests fail, issues are assigned back to the developer, the developer needs to fix what is wrong and try again.
  - Developer must resolve the issue, 
  
  
  ## Developer Issue Scanning



 
