<!--
**harchcode/harchcode** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# My Projects

- https://github.com/harchcode/ubur
- https://github.com/harchcode/web-digraph
- https://github.com/harchcode/gaguna
- https://github.com/harchcode/simple-sudoku-ts
- https://github.com/harchcode/kisstastic
- https://github.com/harchcode/portfolio

My other projects/repos other than the ones above are either outdated or abandoned :see_no_evil:

# About me

I am just an ordinary software engineer focused on FE Web development. If you see my projects above, I hope you have noticed that my interest is really on web game development.

I don't know what else to say, so instead let me just tell you my opinions on what to or not to do when working on a web project:
1. If creating a new project, do not use any framework/library by default. Every time you want to add a dependencies, you must be sure that it will really have more pros than cons (yes, this includes things like React, Vue, etc), because i have seen people using React just to create a simple, static landing page.
2. Do not use Javascript except if it is a really small project. Use Typescript or other languages if possible and thank everyone later.
3. This might be controversial, but do not write unit tests for UI if you want to maintain your sanity. This means I am against using library like the [testing-library](https://testing-library.com/), because there are simply too many things on the UI that is really hard to write unit test for. From my experience, everyone (including myself) will just aim for high coverage, even though it doesn't really test anything useful.
4. If creating a real time application using WebSocket for example, avoid sending/receiving text data (usually in JSON format), instead try to just use binary data, it is far smaller in size. Even for normal REST API, if it is called often and the response is usually a big data, you should consider just using binary data instead of JSON.
5. You should often check your web performance with tools like Lighthouse. Try to aim for as high score as possible.

Also, if you want to learn about web development, here are some advices from me (of course, these are only my opinions):
1. You must learn from basic on HTML, CSS, and especially Javascript. I have seen too many people calling themselves something like "Front End Web Engineer", but only know how to use React, Vue, etc, and don't even know how to do simple DOM manipulation using vanilla JS. That is also true for CSS. I have seen many people who can use Bootstrap, Tailwind, etc, but don't know how to do simple CSS.
2. Many people also thought that FE web is easy because it is only about giving a little interactivity to the UI. They don't know there are things like Canvas, WebGL, WebSocket, WebRTC, WebAssembly, etc, and there will be new things like WebGPU, HTTP/3 with QUIC protocol. Of course, those are only needed in some type of applications, but you will stand out from others if you know those things.
3. If JS was your first programming language, as soon as you think you are quite good with it, you should learn other lower-level language like C/C++ or at least Rust, because they will force you to learn about how memory works. Yes, JS has something called a GC and make the user think that they don't need to worry about memory at all. I see many people try to create a simple web game but the game is stuttering a lot because they are creating too many "garbage" (I am looking at React and its Virtual DOM). Also, after learning somthing like Rust, you will realize how ugly some parts of JS is.
4. Even though you want to only focus on FE web, you must also learn about BE web development, you must know the tools and concepts, and you must at least know how to do simple CI/CD. In other words, you must be a Full Stack web developer first before you can focus on one side. There is a huge misunderstanding that a Full Stack developer is better than a FE/BE developer. In my experience, most of those who call themselves "Full-stack web developer" are usually a beginner in web development.

That is all i can think of for now. Sorry if it look more like rants than advices, i will update this in the future xD
