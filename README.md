## Project Overview
<pre>
<b>Project:</b>   Pilgrim's Career Site
<b>Role:</b>      UI/UX Designer & Lead UI Developer
<b>Tools:</b>     Figma, Liquid, HTML5, CSS3, JS/jQuery, Foundation
</pre>
&nbsp;<strong><a href="https://jobs.pilgrims.com/">View project</a></strong>

<p><a href="https://jobs.pilgrims.com/"><img src="https://doylesee.github.io/plgrms-cws/thumbnail.jpg" /></a></p>
<br />

## The Challenge
Pilgrim's required a modern, high-performance career site to drive talent acquisition, but faced a major barrier: they didn't have any designs ready for the build.

To execute this project, I had to operate as a solo powerhouse, stepping in to own the entire product lifecycle from initial layout concepts to deployment. The core challenge was twofold: creating a beautiful digital experience under limited resources that seamlessly matched their existing corporate aesthetic, and build a flexible architecture that allowed completely non-technical recruitment team to add, update, and reorder full-page sections dynamically.

<br />

## Core Objectives
🟠 **End-to-End Product Delivery**<br />
Serve as both the sole designer and core developer to translate their brand vision into a live digital platform.

🟠 **Cohesive Brand Implementation**<br />
Reverse-engineer the company's existing corporate footprint to establish an identical, seamless candidate user experience.

🟠 **Tag-Based Content Management System**<br />
Build a dynamic, tag-driven template compiler to turn a rigid backend text database into a modular page builder.

🟠 **Comprehensive Client Enablement**<br />
Deliver production-ready user documentation ensuring long-term project viability and handoff success.

🟠 **Flawless Front-End Execution**<br />
Ensure mobile-first responsiveness, cross-browser compatibility, and strict adherence to web accessibility standards.

<br />

## My Approach & Implementation
### 1. Visual Strategy & Interactive UI Design
Operating with highly restricted creative resources, I kicked off the project by reviewing Pilgrim's existing public-facing assets and corporate brand guidelines. Using Figma, I conceptualized and built an entirely new layout system for the career portal. I meticulously extracted color palettes, typographic styles, and stylistic hierarchies to ensure the new career site felt like an organic extension of Pilgrim’s corporate site.

### 2. Engineering the Tag-Driven Dynamic Compiler
To build a content management strategy that a non-technical recruitment team could easily maintain, I leveraged Liquid to engineer an innovative layout router. Instead of forcing users to handle complex layout blocks inside text modules, I wired the backend to check directly for system Page Tags. The template engine loops through page sequences, queries pages containing localized tags, and checks if a specific structural block layout is requested (e.g., layout-hero). If true, it dynamically fetches and injects the target layout snippet file, built as separate content blocks.

### 3. Smart Theme & Accessibility
I programmed the template compiler to handle global utility styles automatically based on user-applied tags. If a content manager appends a tag labeled background-1 or background-3 within the CMS, the script automatically parses the string, hooks into our layouts, and appends a responsive padded-v-xlarge container and a background-dark class. This automatically flipped text elements to accessible light-on-dark palettes without risking layout breakage or human design errors.

### 4. Client Enablement
To conclude the product handoff, I wrote a comprehensive, step-by-step Content Management Documentation Guide. This document served as a blueprint for the Pilgrim's recruitment team, giving them straightforward technical directions on how to leverage the tag-based platform architecture to create pages, modify backgrounds, and swap layouts seamlessly.

<br />

## Results & Impact
✅ **Frictionless UX**<br />
Successfully designed and delivered a beautiful, brand-accurate career site that maintained structural design compatibility with Pilgrim's core corporate presence.

✅ **Zero-Code Structural Content Management**<br />
Empowered a completely non-technical team to rapidly add, reorganize, and manage custom layout pages simply by modifying basic tags inside their dashboard.

✅ **Fullproof Production Quality**<br />
Shipped a production-grade codebase achieving absolute device optimization, cross-browser compatibility, and seamless compliance with global web accessibility standards.

✅ **Flawless Operational Handoff**<br />
Provided a solid user documentation that entirely eliminated post-launch support overhead, making the client transition independent and highly successful, and lowering future costs.

<br /><strong><a href="https://jobs.pilgrims.com/">View project</a></strong>
