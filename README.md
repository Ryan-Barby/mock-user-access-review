# Apex Allied Health: Mock User Access Review

## Overview

In this self-directed exercise, I reviewed fictional user access records for Apex Allied Health, a small allied health practice. I compared staff roles and employment status against access to the fictional Apex Client Portal.

The aim was to practise identifying access mismatches, explaining potential risks, recommending follow-up actions and recording how those actions would be verified.

**All people, accounts, records and systems in this project are fictional.** No live accounts were reviewed or changed.

## Scope and evidence

I compared the following fictional records dated **11 November 2026**:

- A staff list showing each person's role and employment status.
- A Client Portal user list showing each account's access level and status.
- The stated access rules for the exercise.

The review covered six portal accounts: five current staff members and one former employee.

### Access rules

| Role or account | Expected access |
|---|---|
| Practice Manager | Administrator; also the nominated access approver |
| Practice Coordinator | Standard |
| Clinician | Standard |
| Former employee | Account disabled |

Administrator access is restricted to the Practice Manager unless an exception has been approved.

## Access review

| Person | Expected access | Observed access | Review result |
|---|---|---|---|
| Alex Morgan | Administrator; current Practice Manager | Administrator; active | Matches the stated access rule |
| Sam Lee | Standard; current Practice Coordinator | Standard; active | Matches the stated access rule |
| Taylor Reed | Standard; current Clinician | Administrator; active | Requires confirmation of an approved exception |
| Jordan Patel | Standard; current Clinician | Standard; active | Matches the stated access rule |
| Casey Brown | Standard; current Clinician | Standard; active | Matches the stated access rule |
| Jamie Wilson | Disabled; former employee | Standard; active | Does not meet the stated leaver rule |

The four accounts marked as matching the rules were assessed only against the role, employment status and portal access shown in the supplied records.

## Findings and recommendations

### 1. Former employee account remained active

Jamie Wilson left Apex on 30 October 2026, but the Client Portal snapshot dated 11 November showed an active account with Standard access. This did not meet the stated rule that leavers' accounts should be disabled.

An active account could allow someone who no longer works at the practice to access or change client information. No login history was supplied, so the review did not establish whether the account was used after Jamie left.

**Recommended action:** Ask the Practice Manager to arrange for the account to be disabled promptly. Record the decision and verify the account status using an updated, dated Client Portal account list.

### 2. Clinician had Administrator access

Taylor Reed was listed as a Clinician but had an active Administrator account. The stated rule calls for Standard access unless an approved exception exists.

Administrator access may allow changes to users or settings beyond those needed for the Clinician role. This could increase the potential impact of accidental changes, misuse or account compromise.

No approved exception was supplied, but the review could not confirm whether one existed elsewhere. No evidence of misuse was provided.

**Recommended action:** Ask the Practice Manager to confirm whether an approved exception exists. If no exception is confirmed, seek approval to change Taylor's access to Standard. Record the decision and verify the change using an updated, dated account list.

## Remediation tracker

| Finding | Proposed action | Proposed owner | Status |
|---|---|---|---|
| Jamie's account remained active after leaving | Disable the Client Portal account promptly and verify the updated status | Practice Manager | Unresolved |
| Taylor had Administrator access as a Clinician | Confirm whether an approved exception exists; if not, seek approval to change access to Standard and verify the change | Practice Manager | Pending Practice Manager confirmation |

I prioritised Jamie's account for prompt action because it was a **known mismatch with the leaver rule**. I recommended checking Taylor's access at the same time because it involved potentially unnecessary Administrator privileges.

Both findings remain open in this exercise. No follow-up decision or updated account evidence has been added to the project records.

## What I learned

- **Least privilege** means considering whether a person's access is appropriate for their responsibilities, rather than assuming that more access is harmless.
- A mismatch needs careful wording: Taylor's access requires investigation, but the supplied records do not prove it was unauthorised.
- A former employee's active account creates a risk, but it is not evidence that the account was used.
- A manager saying a change was made is useful, but updated account evidence is needed to verify the change before closing a finding.
- An access review should record both accounts that match the rules and those requiring follow-up.

I used AI as a tutor to work through the fictional records, challenge my reasoning and help refine the wording of my findings.

## Limitations

This was a small, fictional document-review exercise. I did not access a live system, make changes to accounts or verify real remediation.

The supplied evidence did not include approved exception records, login history, activity logs or information about access to other systems. The review therefore cannot establish whether Taylor's Administrator access was approved, whether either account was misused, or whether Jamie retained access outside the Client Portal.
