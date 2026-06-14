# Hi there 👋

Welcome to my GitHub profile.

## Featured Projects

### 🔐 [Entra ID Conditional Access Policies Visualizer](https://github.com/edipal/entra-ca-policy-vizz)
A **Next.js web app** that helps you visualize and explore Microsoft Entra ID Conditional Access policies. Runs entirely in the browser — no backend, no server-side secrets.
- Import policies from a CSV export or fetch directly from Microsoft Graph (MSAL popup sign-in)
- Visual graph of policies and related entities (users, groups, roles, apps, named locations) with scopes, conditions, and grant/session controls
- Powerful AND/OR filtering, per-policy highlighting and coloring
- **Live at:** [entra-ca-policy-vizz.vercel.app](https://entra-ca-policy-vizz.vercel.app/)
- **Tech:** Next.js (App Router, TypeScript, Turbopack), Tailwind CSS, MSAL Browser, Microsoft Graph, Jest

### 🔑 [Entra ID OAuth 2.0 Playground](https://github.com/edipal/entra-oauth-playground)
An interactive **Next.js playground** for exploring Microsoft Entra ID OAuth 2.0 authentication flows step by step.
- Supported flows: Authorization Code (public & confidential clients), Client Credentials
- PKCE code generation, authorization URL builder, callback handling, token exchange
- Token decoding, validation, and API call testing in one place
- **Live at:** [entra-oauth-playground.vercel.app](https://entra-oauth-playground.vercel.app/)
- **Tech:** Next.js 16 (App Router, TypeScript), PrimeReact + PrimeFlex + Sass, `jose` (JWT), `next-intl`, Vercel-ready

### 🏗️ [Maven Git Auto-Versioner](https://github.com/edipal/maven-git-autover)
A **Maven extension** that automatically calculates project versions from Git tags — no manual `pom.xml` version management needed.
- Configured as a Maven extension via `.mvn/extensions.xml` — no POM changes required
- Configurable per-branch strategies: master, release, feature, bugfix, PR branches
- Supports annotated tags (next minor bump + SNAPSHOT) and lightweight tags (exact version)
- Reduces merge conflicts and version coordination overhead across teams
- **Tech:** Maven extension/plugin API, JGit

## Organizations

### 📋 [SCIM Sandbox](https://github.com/scimsandbox)
An open-source ecosystem for testing, validating, and experimenting with the **SCIM 2.0** provisioning protocol.
- SCIM 2.0 server implementation in both **Spring Boot** and **Go** flavors, plus management UIs for workspaces, tokens, and traffic inspection
- Standalone SCIM compliance validator that can test any SCIM endpoint, with its own UI for running suites and browsing results
- Ready-to-run infrastructure: Docker Compose for local use and Kubernetes/Kustomize for production
- **Live at:** [scimsandbox.net](https://scimsandbox.net/)

