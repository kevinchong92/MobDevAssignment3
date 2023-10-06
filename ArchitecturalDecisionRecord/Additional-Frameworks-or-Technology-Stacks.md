# Additional Frameworks or Technology Stacks

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

In addition to the core decisions related to the app's architecture, we need to decide on additional frameworks and technology stacks to address specific requirements, such as push notifications, analytics, image optimization, and localization.

### Decision Drivers

- **Feature Integration:** The selected frameworks should seamlessly integrate with the app's core features.

- **Performance:** The chosen technologies should enhance the app's performance and user experience.

- **Scalability:** Scalable solutions are preferred to accommodate future growth.

### Considered Options

1. **Push Notification Service:** Utilize Firebase Cloud Messaging (FCM) for push notifications.

2. **Analytics Tool:** Implement Google Analytics for tracking user behavior.

3. **Image Optimization:** Use a combination of content delivery networks (CDNs), caching, and image compression libraries.

4. **Localization Framework:** Implement the built-in localization support provided by React Native.

### Decision Outcome

**Chosen options:**

- **Push Notification Service:** Firebase Cloud Messaging (FCM) for handling push notifications.

- **Analytics Tool:** Google Analytics for tracking user behavior.

- **Image Optimization:** A combination of Amazon CloudFront (CDN), React Native's built-in image caching, and the React Native Fast Image library.

- **Localization Framework:** React Native's built-in localization support.

### Positive Consequences

- **Feature Integration:** All selected frameworks integrate well with React Native, ensuring smooth functionality.

- **Performance:** FCM offers efficient push notification delivery, Google Analytics provides insights without impacting performance, and the image optimization stack ensures fast loading times.

- **Scalability:** These solutions are scalable and can accommodate the app's growth.

### Negative Consequences

- **Dependency:** Depending on external services like FCM and Google Analytics introduces some level of dependency on third-party providers.

### Pros and Cons of the Options

**Push Notification Service (FCM)**

- Good, because it is well-integrated with React Native.

- Good, because it provides efficient push notification delivery.

- Bad, because it introduces a dependency on Firebase.

**Analytics Tool (Google Analytics)**

- Good, because it offers valuable insights into user behavior.

- Good, because it integrates seamlessly with React Native.

- Bad, because it relies on Google's services.

**Image Optimization (CDN, Caching, Compression)**

- Good, because it ensures fast image loading times.

- Good, because it can be tailored to the app's specific needs.

- Bad, because it may require additional configuration and management.

**Localization Framework (React Native)**

- Good, because it is built-in and well-supported by React Native.

- Bad, because it might not provide advanced localization features offered by third-party libraries.

### Links

- [Firebase Cloud Messaging (FCM)](https://firebase.google.com/docs/cloud-messaging) - Documentation for Firebase Cloud Messaging, a push notification service.

- [Google Analytics](https://analytics.google.com/) - Information about Google Analytics for tracking user behavior.

- [React Native Fast Image](https://github.com/DylanVann/react-native-fast-image) - A React Native library for optimizing and caching images.

- [React Native Localization](https://github.com/stefalda/ReactNativeLocalization) - A library for React Native to support app localization.
