## What Does This PR Do?
Merge User onboarding from dev to staging with the following updates

- Added `business_verified` to organization lib schema
- Set `business_verified` status to `pending` by default on creation of a new organization
- Added endpoint to update an organization verification status to `verified`
- Updated welcome email template to match figma design
- Send an email to notify user once business has been verified succesfully

## Issue List
#92 #90 #91 #87 #86 #88 #83 

## Dependency List
1. AppSync PR - https://github.com/Flex-Finance/flexAppSync/pull/250
2. Wallet Lambda PR - https://github.com/Flex-Finance/flexWallet_lambda/pull/250

## None of the functionality to be implemented exists
- [ ]  I’ve broken this task down into different functions
- [ ]  I’ve gone through utility files related to this task
- [ ]  None of the utility files contain similar functions
- [ ]  I’ve asked another team member if this functionality exists

## Test Scenarios
[Read here]()

## How to test - Endpoint Flow / How to test - UI Flow
[Read here]()

## Success Criteria
[Read here]()

## Screenshot/Recording (optional)
[Read here]()