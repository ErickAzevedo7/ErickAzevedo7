# Érick Azevedo

**Engine & graphics programmer** · Computer Science, UFRRJ (2026) · Rio de Janeiro, Brazil

I build game engines from the ground up. My main project is **VKE**, a 3D engine and editor written in C++ on Vulkan — renderer, editor, scripting and tooling, about 31,000 lines across 14 modules. I'm looking for a junior role in engine, graphics, tools or gameplay programming, remote or abroad.

<a href="https://github.com/ErickAzevedo7/Vulkan_Engine">
  <img src="https://raw.githubusercontent.com/ErickAzevedo7/Vulkan_Engine/main/media/editor.png" alt="The VKE editor with the Sponza scene open" width="100%">
</a>

## VKE — 3D game engine & editor

`C++` `Vulkan` `GLSL` `CMake` · **[View the repository →](https://github.com/ErickAzevedo7/Vulkan_Engine)**

- **Modular from the GPU up.** 14 CMake modules in an acyclic dependency graph. Vulkan sits behind an RHI, and no file outside it touches the graphics API.
- **Renderer.** Forward PBR, HDR tonemapping, image-based lighting, clustered lighting and a shadow atlas sized by importance — 400 moving lights in Sponza at ~8 ms a frame in a Debug build.
- **C++ scripting with hot reload.** Game code builds into its own DLL against an SDK and swaps in during Play in ~0.7 s, keeping object state. A crashing script stops the game, not the editor.
- **Editor.** Reflection-driven Inspector, YAML scenes, prefabs with overrides, GPU picking, gizmos, Play/Pause/Stop and a standalone runtime.

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="https://raw.githubusercontent.com/ErickAzevedo7/Vulkan_Engine/main/media/hot-reload.gif" alt="Editing a script while the game keeps running" width="100%"><br>
      <sub>Changing a script while the game runs</sub>
    </td>
    <td width="50%" valign="top">
      <img src="https://raw.githubusercontent.com/ErickAzevedo7/Vulkan_Engine/main/media/lights.gif" alt="400 coloured lights moving through the Sponza atrium" width="100%"><br>
      <sub>400 moving lights, 8 of them casting shadows</sub>
    </td>
  </tr>
</table>

VKE started as my undergraduate thesis: a single Vulkan application where one header was included by 20 files. I rewrote it into the modular engine above, and the [repository README](https://github.com/ErickAzevedo7/Vulkan_Engine#readme) walks through what it can do.

## Other projects

| Project | Stack | What it is |
| --- | --- | --- |
| **[Compiler](https://github.com/ErickAzevedo7/Compiler)** | C++, Yacc, Lex | A programming language and its compiler, built from scratch: lexical analysis, semantic parsing, intermediate code generation and a scoped symbol table. |
| **[WebProject](https://github.com/ErickAzevedo7/WebProject)** | TypeScript, AdonisJS | A game storefront driven by the Steam API, with Stripe payments — 18 REST endpoints and 8 data models. |

## Right now

- Software developer intern at **CoppeTEC**, building features for an AI platform used daily by Brazil's Public Defender's Office (React, TypeScript, LLMs).
- Next in VKE: GPU particles on compute shaders, a job system, and frame profiling with RenderDoc.

## Tools

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Vulkan](https://img.shields.io/badge/Vulkan-AC162C?style=flat-square&logo=vulkan&logoColor=white)
![GLSL](https://img.shields.io/badge/GLSL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Contact

**Email:** [erick.azevedo701@gmail.com](mailto:erick.azevedo701@gmail.com)
<!-- Add your LinkedIn here and remove this comment:
**LinkedIn:** [linkedin.com/in/your-handle](https://www.linkedin.com/in/your-handle)
-->

Portuguese (native) · English (fluent)

<!--
**ErickAzevedo7/ErickAzevedo7** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
