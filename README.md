<div align="center">
  <img src="https://raw.githubusercontent.com/igorskyflyer/project-nextwave/main/media/nextwave.png" alt="Icon of Project Next-Wave" width="256" height="256">
<h1 align="center">Project NextWave</h1>
</div>

<br>

<div align="center">
  🌊 Project NextWave: Migration of Packages to a New Username and Scope 🚀
</div>

<br>

<div align="center">
    <a href="https://github.com/igorskyflyer/project-nextwave/milestone/1"><img src="https://img.shields.io/github/milestones/progress/igorskyflyer/project-nextwave/1?style=for-the-badge&label=Progress" alt="Progress"></a>
</div>


<br>

### Welcome to NextWave! 🌊

🌊 Project NextWave: A living log of a large‑scale npm username/package scope migration sparked by technical issues, engineered for reproducibility, minimal disruption, and ecosystem trust. 🚀

<br>

### Why NextWave?

This migration was prompted by a long‑standing Windows‑specific compatibility issue affecting npm package scopes that contain a dot (.).

<br>

> [!TIP]
> See more about the issue in the [official discussion](https://github.com/orgs/community/discussions/169922).
>

<br>

While such scopes are valid per the [npm specification](https://docs.npmjs.com/creating-a-package-json-file#required-name-and-version-fields):

>
> A package.json file must contain "`name`" and "`version`" fields.
>
> The "`name`" field contains your package's name and must be lowercase without any spaces. May contain hyphens, dots, and underscores.
>

they can fail in modern Windows environments due to PowerShell parsing quirks and cross‑platform path resolution edge cases. These inconsistencies disrupt installs and build pipelines, creating friction for maintainers and consumers alike. Project NextWave documents the full remediation process: from planning to execution, turning a one‑time fix into a reproducible blueprint other projects can adapt with minimal disruption.

<br>

## Progress

Follow along in the [official tracker](https://github.com/igorskyflyer/project-nextwave/milestone/1) as we check off packages, close out sub‑issues, and move steadily towards a fully migrated, cross‑platform‑safe ecosystem.

<br>

### Join the NextWave

Follow along as Project NextWave turns a Windows‑only scope fix into a reproducible migration pattern the whole community can build on. 🌊

<br>

**Due date: 31 Aug 2025.**
