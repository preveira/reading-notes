# reading-41

### Name three Core Components of React Native and describe what they do.

1. **View**: This is the most fundamental component for building UI in React Native. It is analogous to a `<div>` in HTML and serves as a container for other components, including `Text`, `Image`, and `Button`. It supports layout with flexbox, styling, and touch handling.

2. **Text**: This component is used for displaying text. It allows you to style your text with various properties like font size, color, and alignment. Unlike plain HTML, every piece of text in React Native must be wrapped in a `Text` component.

3. **Image**: This component is used to display images. It supports different sources, such as static resources, local images, and network images. The `Image` component also allows for styling and resizing.

### What problem does React Native solve (why call it native)?

React Native solves the problem of code duplication across different platforms. Traditionally, developing mobile apps for iOS and Android required writing separate codebases in Objective-C/Swift and Java/Kotlin, respectively. React Native allows developers to write a single codebase in JavaScript (or TypeScript), which then translates into native components for each platform. This approach maintains the performance and look-and-feel of truly native apps, hence the term "native."

### What are the building blocks of a React Native app? How does that compare to a React app?

The building blocks of a React Native app are components. In React Native, components such as `View`, `Text`, and `Image` are used to construct the app’s UI, similar to how `div`, `span`, and `img` are used in a React app for the web. Both frameworks use a component-based architecture and JSX syntax, allowing for reusable, modular, and maintainable code. The primary difference is that React Native components render to native UI elements, whereas React components render to the DOM.

### What solution does expo provide?

Expo provides a set of tools and services built around React Native, simplifying the development process. It includes a managed workflow that handles many of the complex aspects of building and deploying React Native applications, such as configuration, building, and testing. Expo allows developers to focus more on writing their app rather than managing the build process.

### Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.

Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the **managed** workflow.

### What is the difference between React Native and Expo?

React Native is a framework for building native apps using React. Expo, on the other hand, is a framework and platform built on top of React Native that provides a set of tools and services to streamline the development process. While React Native gives developers full control over their app's configuration and dependencies, Expo simplifies this by offering a managed workflow that abstracts many of these details, making it easier for developers to get started and maintain their applications.

### Checkout this tool. What does snack allow you to do?

[Snack](https://snack.expo.dev/) is an online editor provided by Expo that allows developers to write and test React Native code directly in their web browser. It provides an interactive environment where you can see the results of your code changes in real-time on a virtual device. Snack is useful for quickly prototyping, sharing code snippets, and debugging.

### What does “eject” mean within the context of Expo?

Within the context of Expo, “eject” means to exit the managed workflow and gain full control over your project's configuration. This process involves converting an Expo project into a standard React Native project with native code for iOS and Android, allowing for more complex customizations and the use of native modules not supported by Expo.

### When should you not eject?

You should not eject if your project requirements can be met within the constraints of Expo's managed workflow. If you do not need custom native code or advanced configurations and want to benefit from Expo's simplicity, ease of updates, and managed build process, it is best to stay within the Expo environment.

### Why might you choose to eject?

You might choose to eject if your project requires custom native code, uses third-party libraries that require native linking, or if you need more control over the build configuration than what Expo's managed workflow provides. Ejecting gives you the flexibility to modify native code and settings that are not accessible in the managed workflow.

## Things I want to know more about