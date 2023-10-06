# UI Framework

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

We need to select a UI framework for the mobile app that will provide a consistent and visually appealing user interface while meeting the requirements of the retail company's app.

### Decision Drivers

- **Native-Like Look and Feel:** The UI should resemble native app interfaces to ensure a familiar and comfortable user experience.

- **Cross-Platform Compatibility:** The selected framework should work seamlessly on both iOS and Android.

- **Customization:** The framework should allow for custom UI elements to match the retail company's branding.

- **Developer Community and Support:** Availability of resources and a strong developer community is essential for troubleshooting and updates.

- **Internationally Compatibility:** Support multiple languages and localization techniques.

### Considered Options

1. **React Native's Built-in Components:** Using React Native's built-in components for UI development.

2. **Custom UI Components:** Building custom UI components from scratch to achieve a unique look and feel.

3. **Third-Party UI Framework:** Utilizing a third-party UI framework like NativeBase or Shoutem.

### Decision Outcome

**Chosen option:** "React Native's Built-in Components," because they provide a balance between native-like appearance and cross-platform compatibility, which aligns with the React Native framework.

### Positive Consequences

- **Native-Like UI:** React Native's built-in components offer native-like UI elements for both iOS and Android.

- **Cross-Platform Compatibility:** By using React Native's components, we ensure a consistent look and feel on both platforms.

- **Development Efficiency:** React Native components are ready to use and save development time.

- **Customization:** React Native allows customization of components to match the retail company's branding.

- **Localization and Internationalization:** React Native supports easy localization and internationalization.

### Negative Consequences

- **Limited Uniqueness:** While React Native's components are highly customizable, they may still resemble typical mobile app UI styles.

### Pros and Cons of the Options

**React Native's Built-in Components**

- Good, because it provides native-like UI elements for both platforms.

- Good, because it ensures cross-platform compatibility and consistency.

- Good, because it supports easy localization and internationalization.

- Bad, because it might limit some unique branding elements.

**Custom UI Components**

- Good, because it allows for complete customization.

- Bad, because it can be time-consuming and may lead to inconsistencies between platforms.

- Bad, because it may require more development effort.

**Third-Party UI Framework**

- Good, because it can provide a unique look and feel.

- Good, because it might save development time compared to building custom components from scratch.

- Bad, because it may introduce additional dependencies and compatibility issues.

### Links

- [React Native Components](https://reactnative.dev/docs/components-and-apis) - Reference to React Native's official documentation on components for further information.

- [Internationalization and localization in React Native - LogRocket Blog](https://blog.logrocket.com/internationalization-and-localization-in-react-native/) - Reference for Internationalization and localization in React Native.

