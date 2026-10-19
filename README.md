<h1 align="center">Nithishkumar Anandharaj</h1>

<p align="center">
  Full stack developer from Coimbatore. Backend systems, AI products, and apps that people actually use.
</p>

<p align="center">
  <a href="https://nithish9020.dev"><img src="https://img.shields.io/badge/Resume-nithish9020.dev-111111?style=for-the-badge&logo=readme&logoColor=white"/></a>
  <a href="https://linkedin.com/in/nithish9020"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:nithishkumar9020@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

### About me

I'm a final-year IT student at SKCET, Coimbatore. Most of what I know I picked up by shipping things for real users, from a gym owner's app to a retail shop that bills customers on my ERP every day.

Recently I spent five months at **SWS AI** building Yellow Owl, an assessment platform where AI writes and grades the tests. I worked on all of it: the backend, the Flutter app, the React dashboards, and the release pipeline that pushes builds to the Play Store and TestFlight.

The work I like most is the part users never see. Background jobs that don't lose work. AI calls that fail over to another provider instead of erroring out. Apps that keep billing when the shop's internet drops.

### Things I've built

**Yellow Owl** · *SWS AI, 2026*
AI-graded assessments plus daily and weekly challenges, used by 200+ people on web, Android and iOS. Question generation and test evaluation run in the background on Redis and BullMQ. The AI provider sits behind its own layer, so we can switch models without touching business logic. The app and dashboards both use API clients generated from one OpenAPI spec, and releases go out through Fastlane on a Mac mini we run as a CI runner.
`Node.js` `TypeScript` `MongoDB` `Redis` `BullMQ` `Azure` `Flutter` `React` `Fastlane`

**[TP-ERP](https://github.com/nithish9020/tp-erp)** · *billing and inventory for a retail shop*
Live in production and used by the shop's staff every day. I sat with them to understand how they actually work, then cut the usual ERP features down to what they needed. It has a web app and a mobile app in one monorepo that share the same validation schemas, plus offline billing that syncs when the connection is back and a PIN login so the counter stays fast.
`TypeScript` `React` `React Native` `Expo` `PostgreSQL` `Drizzle` `Zod`

**[Coligo](https://github.com/nithish9020/coligo-college-admission-assistant)** · *WhatsApp admissions assistant (team project)*
A RAG backend that answers cutoff questions from official admission data and shows where each answer came from. It's based on an SIH problem statement. It has a primary and a fallback LLM, and lint, type checks and tests run in CI before anything is deployed.
`Python` `FastAPI` `PostgreSQL` `pgvector` `Celery` `Redis`

**[VTone](https://github.com/nithish9020/vtone-gym-suite)** · *freelance gym app*
A gym app with separate access for admins, trainers and members. It tracks workouts and diets, and sends fee reminders over WhatsApp automatically so the owner doesn't have to chase people.
`React Native` `Express` `Firebase` `WhatsApp API`

Older side projects: [NammaBus](https://github.com/nithish9020/NammaBus) (live bus tracking) and [Interview Scheduler](https://github.com/nithish9020/Interview_Schedular) (Spring Boot + React).

### What I work with

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,py,react,flutter,tailwind,nodejs,express,fastapi,redis,postgres,mongodb,docker,githubactions,azure,firebase,git,linux&perline=9" />
</p>

### Right now

Open to full-time backend or full stack roles for 2027. If you're building something interesting, my inbox is open.
