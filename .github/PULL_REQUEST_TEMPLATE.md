## What Does This PR Do?
Merge User onboarding from dev to staging with the following updates

- Added `business_verified` to organization lib schema
- Set `business_verified` status to `pending` by default on creation of a new organization
- Added endpoint to update an organization verification status to `verified`
- Updated welcome email template to match figma design
- Send an email to notify user once business has been verified succesfully

## Issue List
#1

## Dependency List
1. AppSync PR - https://github.com/Flex-Finance/flexAppSync/pull/250
2. Wallet Lambda PR - https://github.com/Flex-Finance/flexWallet_lambda/pull/250

## Test Scenarios
[Read here]()

## How to test - Endpoint Flow / How to test - UI Flow
[Read here]()

## Success Criteria
[Read here]()

## Screenshot/Recording (optional)
[Read here]()