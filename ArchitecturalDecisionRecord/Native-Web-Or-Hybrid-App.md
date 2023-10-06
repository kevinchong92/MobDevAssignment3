# Native, Web, or Hybrid App

**Status:** Proposed

**Deciders:** Kevin, Yuen Chong || Greg, Kuan-Ling Wu

**Date:** 2023-10-04

**Scenario 1**

Contents:

- [Context and Problem Statement](#context-and-problem-statement)
- [Decision Drivers](#decision-drivers)
- [Considered Options](#considered-options)
- [Decision Outcome](#decision-outcome)
- [Positive Consequences](#positive-consequences)
- [Negative Consequences](#negative-consequences)
- [Pros and Cons of the Options](#pros-and-cons-of-the-options)
- [Links](#links)

### Context and Problem Statement

The retail company is developing a new mobile app that needs to support various features such as offline mode, push notifications, payment gateways, and localization. We need to decide whether to build a native app, a web app, or a hybrid app to meet these requirements.

### Decision Drivers

- **Performance:** The app should provide a smooth and responsive user experience.

- **Offline Support:** The app must work in offline mode for browsing products and viewing order history.

- **Native Features:** Leveraging device-specific features is important for push notifications and optimal user experience.

- **Cross-Platform Compatibility:** The app needs to be available on both iOS and Android platforms.

### Considered Options

1. **Native App:** Develop separate native apps for iOS or Android using platform-specific languages and tools.

2. **Web App:** Build a web app that users can access via their mobile browsers.

3. **Hybrid App:** Create a hybrid app using React Native or Flutter, so users can access it on both iOS and Android.

### Decision Outcome

**Chosen option:** "Hybrid App" and using React Native because it provides a good balance between performance and cross-platform compatibility.

### Positive Consequences

- **Performance:** It offers native-like performance and UI, ensuring a smooth user experience.

- **Cross-Platform Compatibility:** With a single codebase, we can target both iOS and Android, reducing development effort and maintenance.

- **Development Efficiency:** Only one codebase for iOS and Android, making future maintenance easier.

- **Native Features:** It allows us to access native device features and APIs for push notifications and other requirements.

### Negative Consequences

- **Learning Curve:** The team may need some time to learn React Native if they are not already familiar with it.

- **Limited Native Features:** While it supports many native features, there might still be some limitations compared to fully native development.

### Pros and Cons of the Options

**Native App**

- Good, because it provides the best possible performance and access to native features.

- Good, because it can offer a seamless user experience.

- Bad, because it requires developing and maintaining two separate codebases for iOS and Android.

- Bad, because it might increase development time and cost.

**Web App**

- Good, because it is platform-independent and accessible via mobile browsers.

- Good, because it is relatively easy to develop and deploy.

- Bad, because it may not provide the same level of performance and access to native features.

- Bad, because it may not work well in offline mode without additional complexity.

**Hybrid App**

- Good, because it offers a balance between performance, development efficiency, and cross-platform compatibility.

- Good, because it allows access to native features.

- Good, because it supports offline mode and sync functionality.

- Bad, because there might be a slight learning curve for the team.

### Links

- [React Native](https://reactnative.dev/) - Official website for React Native for reference and further information.

- [React Native Documentation](https://reactnative.dev/docs/getting-started) - React Native's official documentation for development guidance.
