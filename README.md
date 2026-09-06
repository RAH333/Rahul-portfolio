# Rahul-portfolio
Engineer Rahul Saini Portfolio

As a 2019 Mechanical Engineering graduate from Rajasthan Technical University (RTU), Kota, and My current transition into AI by joining the AssemblyAI Voice Agent Hackathon on lablab.ai, I have designed a professional developer portfolio website.

This architecture uses clean, semantic HTML and modern Tailwind CSS (via CDN).
## Project Directory Structure
To deploy this cleanly to Vercel, organize your local folder exactly like this:
```
Rahul-portfolio/
│
├── index.html        # Main landing page & professional portfolio
├── project.html      # Dedicated page for your AssemblyAI Voice Agent hackathon project
└── vercel.json       # Configuration file for clean Vercel routing
```
------------------------------
## Component Source Codes## 1. index.html (Main Portfolio Page)
Create a file named index.html and paste the following code. It includes sections for your Mechanical Engineering background, your pivot to AI, your skills, and placeholders for your social links.


AssemblyAI
JavaScript
AI Agents




Explore Project Framework →


Engineering Utility
Fluid Dynamics Sim Tool

A browser-based calculation toolkit built to map numerical simulations for mechanical engineering problems.


Codebase updating soon...



Let's Build Something Together

Whether you want to discuss AI Agent capabilities, physical system modeling, or team collaborations, my inbox is always open.











© 2026 Portfolio. Built for Vercel deployment.


---

#### 2. `project.html` (Dedicated Hackathon Project Page)
Create a file named `project.html`. This page showcases your project documentation, framework screenshots, and architecture breakdown.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AssemblyAI Voice Agent Project Details</title>
    <script src="https://jsdelivr.net"></script>
    <link rel="stylesheet" href="https://cloudflare.com">
</head>
<body class="bg-slate-900 text-slate-100 font-sans antialiased">

    <!-- Simple Navigation Back -->
    <nav class="max-w-4xl mx-auto px-4 py-6">
        <a href="index.html" class="inline-flex items-center gap-2 text-sm text-teal-400 hover:text-teal-300 transition-colors">
            <i class="fa-solid fa-arrow-left"></i> Back to Main Portfolio
        </a>
    </nav>

    <!-- Project Presentation Content -->
    <main class="max-w-4xl mx-auto px-4 pb-20">
        <header class="mb-12">
            <div class="text-xs font-bold text-teal-400 uppercase tracking-widest mb-2">Lablab.ai Hackathon Initiative</div>
            <h1 class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight">
                AssemblyAI Voice Agent Ecosystem
            </h1>
            <p class="text-slate-400 mt-2 text-base">
                An exploration into modern speech processing architecture, semantic text-to-speech loops, and intelligent fallback algorithms.
            </p>
        </header>

        <!-- Screenshot / UI Showcase Container -->
        <section class="border border-slate-800 bg-slate-950 rounded-2xl p-4 mb-12 shadow-2xl">
            <div class="bg-slate-900 border border-slate-800 rounded-xl overflow-hidden aspect-video flex flex-col justify-center items-center p-8 text-center text-slate-500 relative">
                <!-- DYNAMIC PLACEHOLDER FOR SCREENSHOT -->
                <i class="fa-solid fa-image text-4xl mb-4 text-slate-700"></i>
                <span class="text-sm font-medium text-slate-400">[ Replace this container with your Hackathon Dashboard Screenshot ]</span>
                <span class="text-xs text-slate-600 max-w-sm mt-1">To change this, edit project.html to add an &lt;img src="your-image.png"&gt; element here.</span>
            </div>
        </section>

        <!-- Architectural Details -->
        <section class="space-y-8">
            <div>
                <h3 class="text-xl font-bold text-white mb-3">Project Concept</h3>
                <p class="text-sm text-slate-400 leading-relaxed">
                    By implementing AssemblyAI’s production speech streams, this engine takes live spoken input from human operators, performs instant transactional transcription, maps intent profiles via custom prompt trees, and executes real-time operations.
                </p>
            </div>

            <div>
                <h3 class="text-xl font-bold text-white mb-3">Key Structural Modules</h3>
                <ul class="grid md:grid-cols-2 gap-4 text-sm text-slate-400">
                    <li class="bg-slate-900 border border-slate-800 p-4 rounded-xl">
                        <strong class="text-teal-400 block mb-1">🎙️ Real-time Stream Hook</strong>
                        Establishes secure data handshakes with transcription microservices over ultra-low latency WebSockets.
                    </li>
                    <li class="bg-slate-900 border border-slate-800 p-4 rounded-xl">
                        <strong class="text-cyan-400 block mb-1">🧠 Mechanical Engineering Logic</strong>
                        Applying structural pipeline patterns to handle concurrent computational flow and unexpected execution exceptions.
                    </li>
                </ul>
            </div>
        </section>
    </main>

</body>
</html>
```

---

#### 3. `vercel.json` (Vercel Configuration)
Create a file named `vercel.json` to handle smooth routing so Vercel serves your pages natively without appending the `.html` extensions.

```json
{
  "cleanUrls": true
}
```


