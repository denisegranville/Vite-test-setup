# Vite-test-setup

Adapted from https://github.com/teyim/Vite-test-setup 


# Folder Structure

/backend - Backend related code and artefacts.
/frontend - Frontend related code and artefacts. Frontend code is in frontend/src. Static files are in frontend/public. The code includes mocks for API calls to the backend project so that the UI works and feels right. These live in src/mocks/handlers.ts and are implemented using service worked hooks through the msw library.
/infra - Terraform files for setting up infrastructure.


/docs/architecture - Architecture documentation.
/docs/decision_log - Architecture Decision Records.