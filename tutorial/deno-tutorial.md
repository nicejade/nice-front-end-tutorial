**导语：** [Deno](https://nicelinks.site/redirect?url=https://deno.land/)（发音："蒂诺"）是 Ryan Dahl 在 2017 年创立的编程语言。作为 [Node.js](https://nicelinks.site/post/5f376ebe1751843ef894c899) 的替代品，[Deno](https://nicelinks.site/redirect?url=https://deno.land/) 也是一个服务器运行时，但是支持多种语言，可以直接运行 JavaScript、TypeScript 和 WebAssembly 程序。`Deno` 内置了 V8 引擎，用来解释 JavaScript。同时，也内置了 tsc 引擎，解释 TypeScript。

[Deno](https://nicelinks.site/redirect?url=https://deno.land/) 使用 Rust 语言开发，由于 Rust 原生支持 WebAssembly，所以它也能直接运行 WebAssembly。它的异步操作不使用 libuv 这个库，而是使用 Rust 语言的 [Tokio](https://nicelinks.site/redirect?url=https://github.com/tokio-rs/tokio) 库，来实现事件循环（event loop）。额外的，Deno 还有以下特性：

- Deno 只提供一个可执行文件，所有操作都通过这个文件完成。它支持跨平台（Mac、Linux、Windows）；
- Deno 支持 Web API，尽量跟浏览器保持一致；所有的异步操作，一律返回 Promise；
- Deno 只支持 ES 模块，跟浏览器的模块加载规则一致。没有 npm，没有 npm_modules 目录，没有`require()`命令，也不需要`package.json`文件；
- Deno 只支持从 URL 加载模块，不能通过模块名加载，所以必须带有脚本后缀名；
- Deno 原生支持 TypeScript 语言，可以直接运行，不必显式转码（根据文件后缀名，选择使用不同的引擎运行）；
- Deno 拥有内置的实用工具，如依赖性检查器（deno info）和代码格式化器（deno fmt）；打包、格式清理、测试、安装、文档生成等，都有专门命令，不再需要外部工具；
- Deno 拥有一组经过审核的标准模块，保证与 Deno 一起工作：deno.land/std；

目前，Deno 尚处于密集开发中，功能不稳定，不建议用于生产环境。但，它已经是一个可用的工具，感兴趣的朋友，不妨尝试学习、体验下。考虑到它设计上的诸多优点，相信在将来，[Deno](https://nicelinks.site/redirect?url=https://deno.land/) 会比 Node.js 更具优势。

## 基础篇

### 官方信息

- [Deno 官方网站](https://deno.land/?utm_source=nicelinks.site)： <sub>A secure runtime for JavaScript and TypeScript.</sub>
- [Deno API TypeDoc](https://doc.deno.land/builtin/stable): <sub>Automatically generated documentation for builtin@stable.</sub>
- [Deno Manual](https://deno.land/manual): <sub>Search the docs.</sub>
- [Third Party Modules](https://deno.land/x): <sub>deno.land/x is a hosting service for Deno scripts. It caches releases of open source modules stored on GitHub and serves them at one easy to remember domain.</sub>
- [Deno News](https://deno.land/posts): <sub>Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.</sub>

### Github 资源

- [denolib/awesome-deno](https://github.com/denolib/awesome-deno): <sub>Curated list of awesome things related to Deno</sub>

### Online Playgrounds

[deno.town](https://deno.town/): <sub>A web REPL for experimenting with the Deno API</sub>

### 教程文章

- [Deno 运行时入门教程：Node.js 的替代品](https://www.ruanyifeng.com/blog/2020/01/deno-intro.html)
- [Getting Started With Deno – Deno.js Tutorial 2020](https://dotnetcrunch.in/getting-started-with-deno/)

### 项目实践

- [nicejade/nicelinks-weekly](https://github.com/nicejade/nicelinks-weekly): <sub>基于 Deno、TypeScript 编写，一键生成「倾城之链（旨在云集全球优质网站）」周刊文章，每周五发布。</sub>

### Deno 资源

- [The React Framework in Deno](https://alephjs.org/): <sub>The Full-stack Framework for React and other in Deno.</sub>

## 进阶篇
