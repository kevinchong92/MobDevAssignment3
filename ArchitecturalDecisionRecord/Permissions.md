# Permissions

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

The mobile app requires access to various device permissions for features such as push notifications and location tracking (for deliveries). We need to decide on the permissions model for the app and how we will handle user consent.

### Decision Drivers

- **User Privacy:** We must respect user privacy and ensure that permissions are requested and used appropriately.

- **Feature Functionality:** The app's core features, like push notifications and location tracking, rely on specific permissions.

- **User Experience:** The permissions request process should be user-friendly and not hinder the app's usability.

### Considered Options

1. **Just-in-Time Permissions:** Request permissions from users only when they are required for specific app features.

3. **Preemptive Permissions:** Request permissions from users during the onboarding or setup process, explaining why each permission is needed.

5. **Progressive Permissions:** Gradually request permissions as users use different features of the app, avoiding a single overwhelming request.

### Decision Outcome

**Chosen option:** "Preemptive Permissions" because it offers transparency and allows users to make informed decisions about granting access.

### Positive Consequences

- **User Privacy:** Requesting permissions upfront and providing explanations build trust with users by showing transparency in data access.

- **Feature Functionality:** Ensures that necessary permissions are granted before users encounter features that require them, preventing interruptions in app functionality.

- **User Experience:** While this approach may require more initial effort from users, it provides clarity and allows for smoother subsequent app usage.

### Negative Consequences

- **User Consent Fatigue:** Users might feel overwhelmed by multiple permission requests during onboarding.

### Pros and Cons of the Options

**Just-in-Time Permissions**

- Good, because it minimizes the number of initial permission requests.

- Bad, because users may be surprised by permission requests when using specific features.

**Preemptive Permissions**

- Good, because it ensures that necessary permissions are granted before they are needed.

- Good, because it builds trust by explaining why permissions are required.

- Bad, because it may result in a longer onboarding process.

**Progressive Permissions**

- Good, because it gradually introduces permissions, reducing user consent fatigue.

- Bad, because it may delay access to certain features until the necessary permissions are granted.

### Links

- [Guidelines for Requesting App Permissions](https://developer.android.com/training/permissions/requesting?) - Android documentation on requesting app permissions for reference.

- [iOS Human Interface Guidelines - Privacy](https://developer.apple.com/design/human-interface-guidelines/privacy) - iOS guidelines on requesting permissions for reference.
