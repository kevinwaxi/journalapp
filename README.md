### Tauri Journaling Application Documentation

Tauri is a framework for building desktop applications with web technologies (HTML, CSS, and JavaScript/TypeScript). There are several reasons why developers might choose to use Tauri for their desktop applications:

1. Cross-Platform Development: Tauri enables the creation of desktop cross-platform apps. It is not necessary to maintain separate codebases for Windows, macOS, and Linux when you can design programmes that work on all three platforms with a single codebase.
2. Web Technology Stack: Tauri makes use of web technologies to enable developers with knowledge of HTML, CSS, and JavaScript/TypeScript to utilise it. For people who are already experienced with web development, this lowers the learning curve
3. Native-Like Performance: Tauri apps are made to function as if they were native to the system. Applications seem responsive and perform well as a result of the framework's utilisation of the operating systems' native web view components.
4. Minimal package Sizes: When compared to certain other desktop application frameworks, tauru applications usually have lesser package sizes. This is beneficial for less memory utilisation and quicker application load times.
5. Security: Tauri prioritises security and offers features like end-to-end data encryption and secure storage alternatives. This is essential, particularly for apps that deal with sensitive user data. And since its build ontop of rust it offers security out of the box by default

The projects contains tests that are carried out by github workflow
The user can safeguard their journals using password in a hash alggorithm

Used vue js as the main javascript framework

#### Features
- Add entries for your days to the journal.
- Do dream journaling and keep the contents of your dreams.
- Search through your entries for tags and titles, and look back on them.

to replicate the project run 
```code 
npm run tauri dev
```

you can also have a standalone application using
```code
npm run tauri build
```

#### Prerequisite
Before building the application we need to first follow the prerequisite given by the tauri site https://tauri.app/v1/guides/getting-started/prerequisites


