# <img src="docs/mage.svg" alt="Logo" height="35"> Metric Mage README

Metric Mage is an open-source analytics platform designed to empower indie developers and game companies by providing detailed insights into their games' performance and player behavior. With a focus on affordability and efficiency, Metric Mage offers a powerful solution for projects targeting at least 100,000 Monthly Active Users (MAU) without incurring significant costs. The server is optimized to run smoothly on a simple $5 VPS, ensuring that even the smallest projects can benefit from powerful analytics.

## Goal

The primary goal of Metric Mage is to help indie developers and game companies improve their games by making data-driven decisions. By offering a cost-effective, easy-to-deploy solution, Metric Mage aims to lower the barrier to entry for analytics in the gaming industry, especially for projects with limited budgets.

## Features

- **Effortless Integration:**
    - **One-Click Docker Deployment:** A pre-configured Docker image for quick setup on any infrastructure.
    - **Unity SDK:** A seamless integration with Unity, the leading game engine for mobile development.
    - **Future SDKs:** SDKs for other popular game engines (Unreal, Cocos2d, etc.) will be added based on demand.
- **Essential Analytics:**
    - **Event Tracking:** Track custom in-game events (e.g., level starts, purchases, achievements) with granular details.
    - **User Segmentation:** Define custom user segments based on demographics, behavior, or in-game actions.
    - **Funnel Analysis:** Visualize and analyze user journeys through critical conversion funnels.
    - **Retention Analysis:** Measure player retention over time to identify drop-off points.
    - **Revenue Tracking:** Track in-app purchases and revenue generated from different sources.
    - **Real-time Dashboards:** Monitor key metrics in real-time to make quick, data-driven decisions.
- **Mobile-First Focus:**
    - **Device-Specific Metrics:** Track mobile-specific data like device type, OS version, screen resolution, and carrier.
    - **Attribution Tracking:** Measure the effectiveness of marketing campaigns and user acquisition channels.
- **Optimized for Scale:** Designed to handle at least 100k MAU efficiently, ensuring your analytics grow with your game.
- **Cost-Effective:** Runs on minimal hardware requirements, such as a $5 VPS, without compromising performance.

## Technologies

- **Backend API:** Golang
- **Frontend Dashboard:** React
- **Database:** MySQL (chosen for its accessibility and popularity among beginners)

## Data Handling

- **Real-Time Data:** Data is processed in a 30-minute timeframe, with the game client capable of sending data offline up to 21 days, ensuring that all historical data is updated accurately.

## Getting Started

To get started with Metric Mage, please refer to the [installation guide](/docs/installation.md) and [configuration documentation](/docs/configuration.md). These resources will help you set up Metric Mage and tailor it to your project's needs.

## Contributing

Contributions are welcome! Whether you're fixing a bug, adding a new feature, or improving the documentation, your help is appreciated. Please see [CONTRIBUTING.md](/CONTRIBUTING.md) for more details on how to contribute.

## Roadmap

### Current Focus: Open-Source Community Version

Our immediate focus is on developing and enhancing the open-source community version of Metric Mage. This version is built with Golang, uses MySQL for database management, and is optimized for running on a simple $5 VPS. It is designed to scale vertically, making it ideal for indie developers and small studios.

#### Version 0.1: Basic Analytics
- **Core Analytics:** Implement basic but crucial analytics features such as tracking DAU, WAU, MAU, time spent per session, and D1 to D360+ retention.

#### Version 0.2: Menu Interaction Tracking
- **Menu Analytics:** Track time spent in each menu (e.g., shop, main menu, gameplay, loading screen).

#### Version 0.3: Event Tracking
- **Event Analytics:** Introduce more detailed event tracking. Examples include level completions, power-up uses, and in-game purchases.

#### Version 0.4: Distant Configuration and A/B Testing
- **Configuration & Testing:** Enable distant configuration settings and A/B testing capabilities to optimize game features based on player interactions.

#### Version 0.x: Core Feature Completion
- **Feature Expansion:** Continue to add all the core features of Metric Mage, ensuring a comprehensive analytics platform (excluding AI and predictive capabilities).

## Future Plans, Commitments, and Transparency

### Open-Source Community Version: Our Top Priority

We're fully committed to building a powerful open-source version of Metric Mage. This is our main focus until all core features are complete. Our goal is to empower indie developers and small studios with a robust, cost-effective analytics platform.

### Beyond Open Source: Expanding Our Offering

Once the open-source version is feature-complete, we plan to expand Metric Mage with additional versions to cater to different needs. Here are the planned versions:

- **Community (Open Source):** All core features, vertical scalability, database, and API can be separated.
- **Core (SaaS):** Fully managed servers (with horizontal scalability) with commercial and technical support.
- **Enterprise (SaaS):** Advanced AI and predictive insights for larger studios.

### Ongoing Commitment to Open Source

Even as we develop SaaS versions, we're dedicated to maintaining and improving the open-source version. The SDK will remain open source, ensuring seamless compatibility between versions. We believe a strong open-source foundation benefits everyone. By fostering collaboration, we ensure Metric Mage remains valuable and accessible to all game developers.

## License

Metric Mage is licensed under the Server Side Public License (SSPL). For more information, please see the [LICENSE](LICENSE) file.

## Copyright

Metric Mage is the brainchild of Jimmy Frai, aimed at supporting the indie game development community by providing a robust, cost-effective analytics solution. By leveraging Metric Mage, developers can focus on what they do best—creating amazing games—while we handle the data.

**Copyright © 2024 Jimmy Frai. All rights reserved.**
