#### 5.2.4.4. Development Evidence for Sprint Review

En este Sprint, el equipo avanzó en la implementación de los principales productos de la solución: Landing Page, Web Services y la documentación del Report, cubriendo las funcionalidades priorizadas en el Sprint Backlog. A continuación se detallan los commits realizados por cada integrante en los repositorios correspondientes, evidenciando la colaboración del equipo durante el ciclo de desarrollo.

**Landing Page**

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| AgroTrack-Project/Landing-Page (DuDu-0912) | develop | a4c9970 | Merge branch 'develop' | Integrates the latest changes from develop into the main working branch to keep the Landing Page in sync with recent updates. | 10/07/2026 |
| AgroTrack-Project/Landing-Page (DuDu-0912) | develop | 3b9c7db | Merge branch 'develop' | Merges pending feature updates from develop to consolidate progress before the next review. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (Miler2003) | develop | b33f4a1 | merge branch 'feature/changes' into develop | Brings recent UI adjustments from the feature branch into develop for integration testing. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (Miler2003) | feature/changes | 5f05ae4 | feat: update README to clarify landing page link and remove license section | Rewrites the README to point clearly to the deployed Landing Page URL and removes an outdated license reference no longer applicable to the project. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (Miler2003) | feature/changes | 0c94e42 | merge branch 'feature/changes' into develop | Consolidates documentation fixes from the feature branch into develop. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (elprrr) | develop | 4402245 | Merge branch 'develop' of https://github.com/AgroTrack-Project/Landing-Page into develop | Syncs local changes with the remote develop branch to avoid divergence before pushing new features. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (elprrr) | develop | 661e613 | feat: Update authentication buttons and navigation with animation support | Adds smooth transition animations to the login/register buttons and navigation menu to improve visual feedback on user interaction. | 09/07/2026 |
| AgroTrack-Project/Landing-Page (Edu-VLL) | main | f12e53e | Merge branch 'main' of https://github.com/AgroTrack-Project/Landing-Page | Pulls the latest changes published on main to keep the local branch up to date before deploying. | 22/06/2026 |
| AgroTrack-Project/Landing-Page (Edu-VLL) | main | 017b9f2 | feat: update url | Updates the external panel URL referenced in the navigation links to point to the correct production endpoint. | 22/06/2026 |
| AgroTrack-Project/Landing-Page (Edu-VLL) | main | 6d82380 | Update panel URL for navigation | Fixes the navigation link so users are redirected to the correct dashboard panel after login. | 22/06/2026 |

**Web Application**

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| AgroTrack-Project/web-application (elprrr) | main | e36b401 | feat: update logout method to redirect to landing page | Modifies the logout flow so that, after clearing the session, the user is redirected to the public Landing Page instead of the login screen. | 16/05/2026 |
| AgroTrack-Project/web-application (elprrr) | main | 74af4bc | feat: implement entry animation for app layout and clean up imports | Adds a fade-in animation on the main app layout when it loads, and removes unused imports left over from previous refactors. | 16/05/2026 |
| AgroTrack-Project/web-application (elprrr) | main | 263796b | feat: add support ticket functionality with CRUD operations | Implements the full CRUD flow for support tickets, allowing users to create, view, update and close tickets from the application. | 16/05/2026 |
| AgroTrack-Project/web-application (DuDu-tech / Eder-09) | main | 3f18c9c | chore: remove .claude folder and add to gitignore | Removes local AI-assistant configuration files from version control and updates .gitignore to prevent them from being tracked in the future. | 16/05/2026 |
| AgroTrack-Project/web-application (DuDu-tech / Eder-09) | main | 0f45ce0 | Merge branch 'develop' | Merges the latest updates from develop into main to prepare for the upcoming release. | 10/07/2026 |
| AgroTrack-Project/web-application (Miler2003) | develop | 4bda6b2 | merge branch 'feature/changes' into develop | Integrates documentation and structural changes made in the feature branch into the shared develop branch. | 10/07/2026 |
| AgroTrack-Project/web-application (Miler2003) | develop | e42e728 | docs: update README for clarity and structure improvements | Reorganizes the README sections and improves wording for better readability by new contributors. | 10/07/2026 |
| AgroTrack-Project/web-application (Miler2003) | develop | 812c543 | docs: update README for clarity and structure improvements | Further refines the README structure, adding missing setup steps and correcting formatting inconsistencies. | 10/07/2026 |
| AgroTrack-Project/web-application (Edu-VLL) | main | 2423fa8 | docs: add translations for login, register, alerts and profile | Adds Spanish and English translation strings for the login, register, alerts and profile views to support internationalization. | 09/07/2026 |
| AgroTrack-Project/web-application (Edu-VLL) | main | 5f6e58e | chore: fix dev api base url and add missing auth endpoint path | Corrects the development environment's API base URL and adds a missing path for the authentication endpoint that was causing failed requests. | 09/07/2026 |
| AgroTrack-Project/web-application (Edu-VLL) | main | bbf6c9c | fix: remove default 0 from numeric plot and soil-record inputs | Removes the default value of 0 pre-filled in numeric plot and soil-record form fields, preventing users from submitting unintended zero values. | 09/07/2026 |

**Web Services**

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| AgroTrack-Project/web-services (elprrr) | main | 4658527 | feat(dashboard): implement REST interface layer with resources, assemblers and controllers | Adds the REST interface layer for the dashboard bounded context, including resources, assemblers and controllers to expose dashboard data through the API. | 19/06/2026 |
| AgroTrack-Project/web-services (elprrr) | main | e613a62 | feat(dashboard): implement infrastructure layer with persistence entities, repositories, assemblers and data seeder | Implements the infrastructure layer for the dashboard context, including persistence entities, repositories, assemblers and a data seeder for local testing. | 19/06/2026 |
| AgroTrack-Project/web-services (elprrr) | develop | ea29a76 | Merge branch 'develop' of https://github.com/AgroTrack-Project/web-services into develop | Synchronizes local develop branch with the remote repository to incorporate teammates' latest commits. | 19/06/2026 |
| AgroTrack-Project/web-services (DuDu-tech) | feature/changes | 2f105e8 | merge branch 'origin/feature/changes' into feature/changes | Pulls remote updates into the local feature branch to keep it aligned before continuing work. | 09/07/2026 |
| AgroTrack-Project/web-services (DuDu-tech) | feature/changes | e23b1d7 | docs(farming): document REST transform assemblers | Adds brief class-level Javadoc to each resource-to-command/query mapper and notes that path-variable ids take precedence over any id present in the request body. | 09/07/2026 |
| AgroTrack-Project/web-services (DuDu-tech) | feature/changes | ed6dbac | docs(farming): document REST controllers and request/response resources | Adds Javadoc documentation to the farming REST controllers and their associated request/response resource classes to clarify their responsibilities. | 09/07/2026 |
| AgroTrack-Project/web-services (Miler2003) | develop | 837e91d | docs: update README with project description, installation instructions, and deployment details | Expands the README with a clearer project description, step-by-step installation instructions and deployment details for the backend service. | 10/07/2026 |
| AgroTrack-Project/web-services (Miler2003) | develop | 7eb3514 | docs: add description into readme.md | Adds a short project description section at the top of the README for better first-time context. | 10/07/2026 |
| AgroTrack-Project/web-services (Miler2003) | develop | 9b6197c | docs: add newline at the end of README.md for consistency | Adds a trailing newline at the end of the README file to follow standard formatting conventions. | 10/07/2026 |
| AgroTrack-Project/web-services (Edu-VLL) | main | 134bb9a | feat: add JWT authentication module with sign-up and sign-in | Implements the JWT-based authentication module, including sign-up and sign-in endpoints, token generation and validation logic. | 09/07/2026 |
| AgroTrack-Project/web-services (Edu-VLL) | main | 7491fd5 | feat: link business profiles to IAM accounts via iam_useR_id | Adds a relationship between business profiles and IAM accounts using the iam_user_id field, enabling profile lookup by authenticated identity. | 09/07/2026 |
| AgroTrack-Project/web-services (Edu-VLL) | main | 9412ced | fix: allow profile updates without resending the current password | Fixes the profile update endpoint so users can update their information without being required to re-enter their current password. | 09/07/2026 |
