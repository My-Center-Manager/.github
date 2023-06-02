<!-- logo -->
<p align="center">
  <img width='300' src="profile/readme/logo.svg">
</p>
<!-- title -->
<h1 align="center" style="display:flex;justify-content:center;align-items:center;width:100%;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
    My Center Manager
</h1>
<!-- powered by -->
<p align="center">
  <a aria-label="Vercel logo" href="https://vercel.com">
    <img src="https://img.shields.io/badge/POWERED%20BY%20Vercel-000.svg?style=for-the-badge&logo=Vercel&labelColor=000">
  </a>
</p>
<!-- brief description -->
<p align="center">
  <a href="#" target="_blank">
    <img alt="License" src="https://img.shields.io/github/license/my-center-manager/My-Manager-Center?style=flat-square&labelColor=343b41.svg"/>
  </a>
  <img alt="Stars" src="https://img.shields.io/github/stars/aiherrera/My-Manager-Center?style=flat-square&labelColor=343b41.svg"/>
  <img alt="Issues" src="https://img.shields.io/github/issues/aiherrera/My-Manager-Center?style=flat-square&labelColor=343b41"/>  
  
  <p align="center">My Manager Center is a SAAS app that allow users to manage their centers of service</p>
</p>

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/overview.svg" />
  <span>Quick overview</span>
</h2>

<p align="center">To be defined</p>

<p align="center">
  <a href="https://mycenter.mx">Website</a> •
  <a href="https://github.com/My-Center-Manager/legal/blob/main/LICENSE">License</a> •
  <a href="CONTRIBUTING.md">Contributing</a>
</p>

&nbsp;

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/architecture.svg" />
  <span>High Level Architecture</span>
</h2>

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#006CFC',
      'primaryTextColor': '#ffffff',
      'primaryBorderColor': '#1F2937',
      'lineColor': '#E5E7EB',
      'secondaryColor': '#008227',
      'tertiaryColor': '#1F2937'
    }
  }
}%%
graph TB
  accTitle: High level diagram
  accDescr: This is a high level diagram for the SAAS template project

  subgraph User Interface
    Next.js["Next.js"]
    Authentication["Authentication"]
    Admin["Admin Dashboard"]
    Database["MongoDB | Supabase"]
    AWSS3["AWS S3"]
    Subscriptions["Subscription Management"]
    UI["Vercel"] -- Hosting --> Next.js
  end

  S3["S3 Bucket"]
  payments["Stripe | Paypal"]
  MongoDBInstance["MongoDB Instance"]
  PostgresInstance["Postgres Instance"]
  SupabaseAuth["Supabase Auth"]
  MongoDBAuth["MongoDB Atlas - Auth"]

  Next.js -- Database layer --> Database
  Next.js -- Auth layer --> Authentication
  Next.js --> Admin
  Next.js -- File management --> AWSS3
  Next.js -- Payments --> Subscriptions

  Authentication -. API Requests .-> Clerk
  Authentication -. API Requests .-> MongoDBAuth
  Authentication -. API Requests .-> SupabaseAuth
  Database -. API Requests .-> MongoDBInstance
  Database -. API Requests .-> PostgresInstance
  AWSS3 -. API Requests .-> S3
  Subscriptions -. API Requests .-> payments

```

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/features.svg" />
  <span>Features</span>
</h2>

- 🌱 **Tips and Suggestions**: To be defined

- 📈 **Progress Tracking**: To be defined

- 🌍 **Community Interaction**: To be defined

- 📆 **Notifications/Reminders**: To be defined

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/author.svg" />
  <span>Author</span>
</h2>

**Alain Iglesias**

- Website: https://aiherrera.com
- Blog: https://blog.aiherrera.com
- Twitter: [@\_aiherrera](https://twitter.com/_aiherrera)
- Github: [@aiherrera](https://github.com/aiherrera)
- LinkedIn: [@-aiherrera](https://linkedin.com/in/-aiherrera)

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/contribute.svg" />
  <span>Contribute</span>
</h2>

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/My-Center-Manager/mycenter/issues). You can also take a look at the [contributing guide](https://github.com/My-Center-Manager/mycenter/blob/master/CONTRIBUTING.md)

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/support.svg" />
  <span>Support the project</span>
</h2>

<p style="margin-bottom:20px">If you consider this project worthy give it a ⭐️ and, why not, invite me a coffee 👇🤘🫶</p>

<p align="center">
  <a href="https://www.buymeacoffee.com/aiherrera" target="_blank">
    <img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=aiherrera&button_colour=5F7FFF&font_colour=ffffff&font_family=Lato&outline_colour=000000&coffee_colour=FFDD00" />
  </a>
</p>

<h2 style="display:flex;justify-content:center;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57"></h2>
<p align="center">Copyright © 2023 Alain Iglesias | This project is MIT licensed</p>
