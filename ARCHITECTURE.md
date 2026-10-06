

*### `ARCHITECTURE.md`*

*```markdown*

*# NER-LogiAI System Architecture*



*## Overview*



*NER-LogiAI follows a client-server architecture with shared application modules and database-related configuration.*



*## Client*



*The `client` directory contains the frontend application and user interface.*



*It provides the interface through which users interact with the disaster intelligence and emergency response features.*



*## Server*



*The `server` directory contains the backend application and server-side functionality.*



*It handles application logic and API-related operations required by the client.*



*## Shared*



*The `shared` directory contains modules that can be used across the client and server portions of the application.*



*## Database*



*The `drizzle` directory contains database schema and migration-related configuration used by the project.*



*## Patches*



*The `patches` directory contains project-specific package patches.*



*## Configuration*



*Important project configuration files are located at the project root, including:*



*- `package.json`*

*- `tsconfig.json`*

*- `vite.config.ts`*

*- `drizzle.config.ts`*

*- `vitest.config.ts`*



*## Application Flow*



*The general application flow is:*



*1. The user interacts with the client interface.*

*2. The client communicates with server-side functionality.*

*3. The server processes application requests and data.*

*4. Shared modules provide reusable functionality.*

*5. Database configuration supports persistent application data where configured.*

