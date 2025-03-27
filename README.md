## Architecture Overview

1. A common core module (shared library) - for common functionalities (logging, security, utilities)
2. Microservices (Deparmental repositories) - Finance, Customer Service etc,, all ectending the core module.
3. API Gateway - centralized entrypoint to route requests

## Common folder structure

# REST Backend

|- src/main/java/com/beluga/common/
| |- config/ #sevice specific config
| |- security/ #security config (JWT)
| |- dto/ #data transfer objects
| |- exception/ #global exception handling
| |- logging/ #logging config - (Aspect logging)
| |- repository/ #database layer
| |- utils/
|-

# graphql Backend

