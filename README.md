ShaderDSL.js
============

[![Join the chat at https://gitter.im/kpalacz/shaderdsl](https://badges.gitter.im/kpalacz/shaderdsl.svg)](https://gitter.im/kpalacz/shaderdsl?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


A compiler from a subset of JavaScript to GLSL.

Based on the RiverTrail JIT.
Some examples use the Gladder library.

FAQ
===


**What is ShaderDSL.js?**

ShaderDSL.js allows you to write GLSL shaders in plain JavaScript,
instead of the C like (GLSL) language used today.

**Why ShaderDSL.js?**

We wanted to experiment with a more approachable way for web
developers to author shaders, hence the use of JavaScript.

**Do I need to enable special flags or use a specific browser to play with ShaderDSL.js?**

No, ShaderDSL.js relies only on the portable, pure Javascript part of
RiverTrail, and works in all the browsers with WebGL enabled (Firefox,
Chrome, Safari).

**What is the status of ShaderDSL.js?**

The project is an experiment and not intended to be used in
production. If you are interested in contributing, please do, we want
this project to be a playground for new ways of authoring shaders.
