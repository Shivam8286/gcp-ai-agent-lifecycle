# 🧩 Dialogflow CX Project Workflow

This file outlines the step-by-step process followed during the Dialogflow CX agent development and deployment.

---

## 1. Agent Initialization
- Created a new Dialogflow CX agent in the GCP console.
- Defined default language and region.
- Set up initial intents and test flows.

## 2. Importing Virtual Agent (.blob)
- Used the `.blob` import feature to upload a pre-built agent structure.
- Verified that all flows, intents, and entities imported successfully.

## 3. Testing in Draft Environment
- Used the default testing tool to simulate conversation scenarios.
- Identified edge cases and adjusted flow routes accordingly.

## 4. Creating Custom Environments
- Created environments such as:
  - **staging**
  - **qa**
  - **beta**
- Each with its own purpose for testing or review.

## 5. Version Control
- Created multiple versions for each milestone:
  - v1.0 (MVP)
  - v1.1 (Post feedback changes)
  - v2.0 (Major flow update)

## 6. Deployment
- Deployed specific versions to selected environments.
- Compared agent behavior in different stages (draft vs deployed).

## 7. Monitoring & Iteration
- Collected feedback during testing.
- Updated flows, fallback routes, and training phrases.

