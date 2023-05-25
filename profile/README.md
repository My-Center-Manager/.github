<!-- logo -->
<p align="center">
  <img width='300' src="profile/readme/logo.png">
</p>
<!-- title -->
<h1 align="center" style="display:flex;justify-content:center;align-items:center;width:100%;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
    EcoTracker
    <img width="25" height="25" style="flex" src="profile/readme/title.svg" />
</h1>
<!-- powered by -->
<p align="center">
  <a aria-label="Vercel logo" href="https://vercel.com">
    <img src="https://img.shields.io/badge/POWERED%20BY%20Vercel-000.svg?style=for-the-badge&logo=Vercel&labelColor=000">
  </a>
  <a aria-label="Vercel logo" href="https://appwrite.io">
    <img src="https://img.shields.io/badge/AND%20appwrite-f02e65.svg?style=for-the-badge&labelColor=f02e65">
  </a>
</p>
<!-- brief description -->
<p align="center">
  <a href="#" target="_blank">
    <img alt="License" src="https://img.shields.io/github/license/aiherrera/ecotracker?style=flat-square&labelColor=343b41.svg"/>
  </a>
  <img alt="Stars" src="https://img.shields.io/github/stars/aiherrera/ecotracker?style=flat-square&labelColor=343b41.svg"/>
  <img alt="Issues" src="https://img.shields.io/github/issues/aiherrera/ecotracker?style=flat-square&labelColor=343b41"/>  
  
  <p align="center">EcoTracker is an app that offers tips and tracks progress towards living a more sustainable lifestyle.</p>
</p>

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/overview.svg" />
  <span>Quick overview</span>
</h2>

<p align="center">In an era where sustainability is more important than ever, EcoTracker seeks to provide an accessible and engaging platform for anyone looking to make a difference. Whether you're just starting on your sustainability journey or you're an eco-warrior, EcoTracker is designed to support and guide you. Give it a try and take your first (or next) step towards a more sustainable future.</p>

<p align="center">
  <a href="https://ecotracker.life">Website</a> •
  <a href="https://github.com/EcoTracker/legal/blob/main/LICENSE">License</a> •
  <a href="CONTRIBUTING.md">Contributing</a>
</p>

&nbsp;

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/architecture.svg" />
  <span>High Level Architecture</span>
</h2>

```mermaid
graph LR
    A[User] -- Actions --> B[Frontend: Next.js + TailwindCSS]
    B -- API Requests --> C[Backend: Appwrite]
    C -- Data Management --> D[Database]
    C -- User Management --> E[Account Service]
    C -- Realtime Updates --> F[Realtime Service]
    C -- Storage --> G[Storage Service]
```

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/features.svg" />
  <span>Features</span>
</h2>

- 🌱 **Tips and Suggestions**: EcoTracker offers tips and suggestions on various categories of sustainability - like waste reduction, energy efficiency, and sustainable eating, providing a starting point for anyone looking to adopt a more eco-friendly lifestyle.

- 📈 **Progress Tracking**: With EcoTracker, users can set sustainability goals and track their progress over time. The platform offers a visual representation of progress, fostering motivation and adherence.

- 🌍 **Community Interaction**: EcoTracker isn't just a tool, but also a community. Users can share their own tips and experiences, fostering discussion and mutual growth towards a common goal of sustainability.

- 📆 **Notifications/Reminders**: To aid users in achieving their sustainability goals, EcoPath sends reminders and motivational messages. This helps users maintain consistency and progress towards a greener lifestyle.

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

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/aiherrera/ecotracker/issues). You can also take a look at the [contributing guide](https://github.com/aiherrera/ecotracker/blob/master/CONTRIBUTING.md)

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
