#  React Native


----

#### getting started with react native

1. Name three Core Components of React Native and describe what they do.

> * View: It's like a container for stuff on the screen, like a box where you put things.
> * Text: This shows words on the screen, like putting text in a book.
> * Image: It displays pictures on the screen, just like in a photo frame.


2. What problem does React Native solve (why call it native)?

> React Native helps make mobile apps that look and feel like regular apps on your phone. It's called "native" because it uses the same building blocks that actual mobile apps use. This way, you can write code once and use it on different types of phones.

3. What are the building blocks of a React Native app? How does that compare to a React app?

> * React Native:
Native Stuff: It uses real mobile parts for the screen.
JavaScript Code: This makes things happen in the app.
Styles: It's like giving your app a unique look.

> * React (for the web):
Virtual Sketch: It's like drawing a plan before making a real drawing.
HTML and Styles: It's like using words and colors to build web pages.
Web Stuff: It uses things just for websites, not mobile apps.

----

#### expo

1. What solution does expo provide?

>Expo simplifies mobile app development with React Native by offering tools and services to handle tasks like setup, building, and deployment, streamlining the process

2. Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.

>Managed

3. What is the difference between React Native and Expo?

> React Native is the core framework for building mobile apps, offering flexibility but requiring developers to manage more complexities. Expo builds on React Native, providing a simplified, beginner-friendly environment with less configuration and more convenience. Developers choose based on their project needs and expertise.

----

#### expo snack

1. Checkout this tool. What does snack allow you to do?

> Snack is a development tool that enables you to write, test, and share React Native code in a convenient and interactive way.

----

#### ejecting

1. What does “eject” mean within the context of Expo?

>In Expo, "eject" means leaving the standard Expo development environment to gain more control over your native Android and iOS projects.

2. When should you not eject?

>Avoid ejecting if you prefer Expo's simplified development environment and don't need extensive customization of native code.

3. Why might you choose to eject?

>Ejecting is chosen when you need full control over native projects, specific native code integrations, or when using Expo APIs in a standard native project. It offers flexibility but requires managing build configurations and native code. ExpoKit ejection is deprecated after SDK 38.