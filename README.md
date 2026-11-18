# ![anay goyal](profile/title2.svg)

![software developer building web, iOS and machine learning systems.](profile/subtitle2.svg)

## ![experience](profile/h2-experience.svg)

**trilegal** · intern  
made presentations and analyzed cases at a tier 1 law firm.

**nature's note** · founder  
built the [website and online store](https://naturesnotefragrances.com) for a natural fragrance brand ([project breakdown](https://github.com/anaygoyal7878-del/natures-note-website)).

**[fire risk modeling](https://github.com/anaygoyal7878-del/fire-risk-modeling)** · machine learning project  
a model that predicts fire risk.

## ![building now](profile/h2-building.svg)

**[moodsync](https://github.com/anaygoyal7878-del/moodsync)** · wearable data meets the smart home  
reads recovery, sleep and heart rate from a wearable, decides what the environment should do, then adjusts lighting, music and notifications.

```mermaid
flowchart LR
    A["Wearables<br/>WHOOP, Google Health, Fitbit"] --> B["Normalized<br/>daily reading"]
    B --> C{"Decision engine<br/>rules, wellness scores,<br/>safety bounds"}
    C --> D["Lighting<br/>Philips Hue"]
    C --> E["Music<br/>Spotify"]
    C --> F["Notifications"]
    C --> G["Plain language<br/>decision log"]
    G --> H["Weekly reports<br/>and insights"]
```

```mermaid
flowchart TB
    subgraph Clients
        W["Next.js web app"]
        I["iOS companion app<br/>HealthKit"]
    end
    W --> API["Fastify API<br/>auth, REST, orchestration"]
    I --> API
    API --> DB[("PostgreSQL<br/>Prisma")]
    WK["Background workers<br/>data sync, decision runs"] --> DB
    WK --> INT["Integration clients<br/>wearables, Hue, Spotify"]
    WK --> ENG["Decision engine<br/>TypeScript"]
```

## ![what i work with](profile/h2-stack.svg)

typescript · python · react · next.js · node.js · fastify · postgresql · sql · supabase · tailwind · swift

looking for software engineering opportunities. reach me at [anay.goyal7878@gmail.com](mailto:anay.goyal7878@gmail.com) or on [linkedin](https://www.linkedin.com/in/anay-goyal-4b7090382).
