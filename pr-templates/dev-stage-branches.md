# 👮 Pull Request Checklist

## 📝 Description

- This PR contains the code from "testing" to "production" for the release v4.2.0 for the tickets that were missed .

## 🎫 Associated JIRA / Linear / Asana tickets
| **Jira Ticket**                                                | **Assignee**                                                                                            | **Summary**                                                                                                                                                        |
| -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [**LV3-3295**](https://antstack.atlassian.net/browse/LV3-3295) | [Albert](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=620d55d7f4d8af0070fe2053)     | [Key not populating for HNOA](https://antstack.atlassian.net/browse/LV3-3295)                                                                                      |
| [**LV3-3217**](https://antstack.atlassian.net/browse/LV3-3217) | [Albert](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=620d55d7f4d8af0070fe2053)     | [Proposal Listing Screen Timeout - Error 504](https://antstack.atlassian.net/browse/LV3-3217)                                                                      |
| [**LV3-3145**](https://antstack.atlassian.net/browse/LV3-3145) | [Albert](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=620d55d7f4d8af0070fe2053)     | [Handle new input types of HNOA](https://antstack.atlassian.net/browse/LV3-3145)                                                                                   |
| [**LV3-3130**](https://antstack.atlassian.net/browse/LV3-3130) | [Albert](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=620d55d7f4d8af0070fe2053)     | [A proposal for some other customer is being displayed in the proposal listing screen on a newly created customer](https://antstack.atlassian.net/browse/LV3-3130) |
| [**LV3-2929**](https://antstack.atlassian.net/browse/LV3-2929) | [Albert](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=620d55d7f4d8af0070fe2053)     | [Backend: Proposal for BOP & Cyber, hide cyber policy section if there are no questions](https://antstack.atlassian.net/browse/LV3-2929)                           |
| [**LV3-2893**](https://antstack.atlassian.net/browse/LV3-2893) | [Albert](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=620d55d7f4d8af0070fe2053)     | [Cyber Proposal - Error Message for format of Insured Contact Name](https://antstack.atlassian.net/browse/LV3-2893)                                                |
| [**LV3-3101**](https://antstack.atlassian.net/browse/LV3-3101) | [Manik](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=61fecb5d8d9e3c0068912d32)      | [SignIn OTP: Send OTP once in one signIn session.](https://antstack.atlassian.net/browse/LV3-3101)                                                                 |
| [**LV3-2816**](https://antstack.atlassian.net/browse/LV3-2816) | [Manik](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=61fecb5d8d9e3c0068912d32)      | [[Parent Bug] - (Admin/Customer Portal) Login: Sending OTP mail again if entering an invalid OTP](https://antstack.atlassian.net/browse/LV3-2816)                  |
| [**LV3-2431**](https://antstack.atlassian.net/browse/LV3-2431) | [Manik](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=61fecb5d8d9e3c0068912d32)      | [Use middleware API to generate Acord Form for 'BOP' policy type](https://antstack.atlassian.net/browse/LV3-2431)                                                  |
| [**LV3-3114**](https://antstack.atlassian.net/browse/LV3-3114) | [Pradeep G.](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=62e58ceb5f7842fb1294f727) | [Need to update script for clearing data, created by cypress user](https://antstack.atlassian.net/browse/LV3-3114)                                                 |
| [**LV3-2577**](https://antstack.atlassian.net/browse/LV3-2577) | [Pradeep G.](https://antstack.atlassian.net/secure/ViewProfile.jspa?accountId=62e58ceb5f7842fb1294f727) | [Cypress cleanup(CyCu)](https://antstack.atlassian.net/browse/LV3-2577)                                                                                            |


## ⚔️ Mandatory Checks

- [ ] Is the functionality working as expected?
- [ ] Does the UI match the design?
- [ ] Are the comments clear and useful, and mostly explain why instead of what?
- [ ] Does it match the required coding standards?
- [ ] Is the performance up to the mark?
- [ ] Verified in AWS?
- [ ] Verified if serverless.yml file is proper?

## 🛠️ Regular Checks

- [ ] Spell Checks.
- [ ] UI Alignment.

## 🗡️ Optional Checks

- [ ] Filter
- [ ] Search
- [ ] Pagination
- [ ] Date Formats

## 🤳 PR Self-Review

- **DRY**: Don't repeat yourself
- **YAGNI**: You aren't gonna need it. Make sure you're not over-complicating something just to try & make it more future-proof 🙅‍♂️
  - P.S. According to Fowler, "Yagni only applies to capabilities built into the software to support a presumptive feature, it does not apply to effort to make the software easier to modify."
- A link to some of the [best practices](https://github.com/andela/bestpractices/wiki/Git-naming-conventions-and-best-practices) for creating a PR

<br>

> ## ⚠️ Wait for PR status checks to complete before approving PR
