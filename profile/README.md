![github-header-image (2) (1)](https://github.com/descope/.github/assets/32936811/d904d37e-e3fa-4331-9f10-2880bb708f64)

Welcome to the Official GitHub repository for Descope. We provide an easy-to-use and secure service to seamlessly handle user management and authentication across various applications.

Our integration approaches range from utilizing Descope Flows to create authentication with a no-code drag-and-drop workflow, to integrating directly with your application server.

You can either use Descope with our wide variety of SDKs or use Descope as an [OpenID Connect](https://www.descope.com/learn/post/oidc) provider with another IdP.

Beyond traditional auth, Descope also powers AI & MCP use cases, making it simple to add authentication and authorization for AI agents and services. Learn more in our [AI & MCP section](#-descope-ai--mcp-use-cases) or visit [descope.ai](https://descope.ai).

[![GitHub followers](https://img.shields.io/github/followers/descope?label=Followers&style=social)](https://github.com/descope) [![Website](https://img.shields.io/badge/Website-descope.com-blue?style=flat)](https://descope.com)

## 🚀 SDKs Supported

Descope offers both client and backend SDKs for many languages and frameworks. 

## 🖥️ Client SDKs

Descope Client SDKs are used to create and manage authentication flows, management widgets, and session management. They are especially useful when integrating Descope into your client application.

- **[React](https://github.com/descope/descope-js/tree/main/packages/sdks/react-sdk)**
- **[NextJS](https://github.com/descope/descope-js/tree/main/packages/sdks/nextjs-sdk)**
- **[Angular](https://github.com/descope/descope-js/tree/main/packages/sdks/angular-sdk)**
- **[Vue](https://github.com/descope/descope-js/tree/main/packages/sdks/vue-sdk)**
- **[Web Component (HTML)](https://github.com/descope/descope-js/tree/main/packages/sdks/web-component)**

## 📱 Mobile SDKs

Descope Mobile SDKs are used to create and manage authentication flows and session management. They are especially useful when integrating Descope within a mobile application.

- **[Swift](https://github.com/descope/swift-sdk)**
- **[Kotlin](https://github.com/descope/descope-kotlin)**
- **[Flutter](https://github.com/descope/descope-flutter)**
- **[React Native](https://github.com/descope/descope-react-native)**

## ⚙️ Backend SDKs

Descope Backend SDKs are typically used for JWT validation after user authentication with Descope. They are also used for RBAC-related authorization checks, when protecting various APIs. These are essential when integrating with your backend application server.

- **[Python](http://github.com/descope/python-sdk)**
- **[Go](https://github.com/descope/go-sdk)**
- **[Node](http://github.com/descope/node-sdk)**
- **[PHP](http://github.com/descope/php-sdk)**
- **[Java](https://github.com/descope/descope-java)**
- **[.NET](https://github.com/descope/descope-dotnet)**
- **[Ruby](https://github.com/descope/descope-ruby-sdk)**

## 🧩 Additional Frameworks / Integrations

Descope also has guides and templates you can use, to see how Descope integrates with other frameworks and services listed below:

### Frameworks
- **[Django](https://github.com/descope/django-descope)** - ([Sample App](https://github.com/descope-sample-apps/django-sample-app))
- **[Passport.js Strategy](https://github.com/descope/passport-descope)** - ([Sample App](https://github.com/descope-sample-apps/passportjs_sample))

### Integrations
- **[Okta](https://docs.descope.com/sso/sso-configuration/setup-guides/okta)**
- **[Webflow](https://docs.descope.com/web-development-platforms/setup-guides/webflow)** - ([Template](https://webflow.com/made-in-webflow/website/terminal-descope))
- **[Retool](https://docs.descope.com/sso-integrations/applications/setup-guides/retool-oidc)**

### Browser Extensions
- **[Chrome Extension](https://github.com/descope-sample-apps/chrome-extension)**

## 🔗 Descope and OpenID Connect

If you're using Descope as a Federated IdP (Identity Provider), you can refer to either the [main documentation](https://docs.descope.com/customize/auth/oidc/) on how to set it up, or you can review a few of the tutorials published that showcase how to use Descope with many major existing identity providers:

### Descope with: 

- **[Auth0](https://docs.descope.com/sso-integrations/applications/setup-guides/auth0/auth0-oidc)**
- **[Cognito](https://docs.descope.com/sso-integrations/applications/setup-guides/aws-cognito)**
- **[Firebase](https://docs.descope.com/sso-integrations/applications/setup-guides/firebase-oidc)**

## 🤖 Descope AI & MCP Use Cases

Descope also powers **AI agent authentication and authorization** through our [AI site](https://descope.ai), where you’ll find an overview of how Descope helps secure AI use cases.

We provide tools, SDKs, and examples to make it easy to integrate **Model Context Protocol (MCP)** with Descope, including authentication and session management for your AI agents and services.

### 📦 MCP Examples

You can explore our growing collection of [MCP server examples](https://github.com/descope/ai/tree/main/examples), including:

* **FastMCP** – FastAPI-powered MCP server
* **FastAPI MCP** – Build MCP services with FastAPI
* **Vercel MCP Adapter** – Deploy MCP services easily to Vercel
* **MCP Auth SDK** – Secure authentication for MCP services with Descope

### 🛠️ MCP Auth SDK

For projects building secure MCP services, check out the [Descope MCP Auth SDK](https://github.com/descope/mcp-express), which makes it easy to add authentication and authorization to your AI workflows.

### ✨ Development with Cursor, Windsurf, and VS Code

We also provide [Cursor rules](https://github.com/descope/ai/tree/main/rules) so you can easily build with Descope SDKs in **Cursor**, **Windsurf**, and **VS Code**, streamlining the development experience for AI integrations.

## 📝 Blogs

Our blogs are very informative, and showcase new features as well as important and interesting use cases for our product. You can read these on the [Blog section](https://www.descope.com/blog) of our main website. 

## 📚 Descope Docs

Please visit the official [Descope Documentation](https://docs.descope.com) for detailed guides and tutorials on using our SDKs and services.

## 🖥️ Descope CLI

You can install `descopecli` on your local machine to perform common tasks on your Descope project. See the [Descope CLI](https://github.com/descope/descopecli) repository for more details.

## 🍿 Descope Sample Apps

- **[B2B Sample App](https://github.com/descope-sample-apps/b2b-react-sample-app)**, see a preview of it [here](https://b2b-react-sample-app.preview.descope.org/)
- **[B2C Sample App](https://github.com/descope-sample-apps/b2c-react-sample-app)**, see a preview of it [here](https://www.tee-hee-tees.store/)

For those looking for working examples and best practices of our various SDKs and blogs, check out our [Descope Sample Apps](https://github.com/descope-sample-apps) repository.

## ❓ Need Help?

🧠 For articles on how to perform certain tasks or troubleshoot, please refer to our [Docs page](https://docs.descope.com).

🔔 Stay tuned for more updates and enhancements in our [CHANGELOG](https://docs.descope.com/changelog) as we continue to expand our services and SDK offerings.

🗨️ Join our [AuthTown Community](https://www.descope.com/community), where thousands of Descopers can ask questions, provide knowledge and feedback, and share cool projects they're working on.

🎓 Visit our [Learning Center](https://www.descope.com/learn) to learn more about Authentication concepts, and how different aspects of Descope work under the hood.

## 💬 Feedback

If you have any feedback or issues, please file a GitHub issue on any one of our repositories.
