---
theme: dracula
background: /earth.jpg
title: Beyond DevOps - The Missing Metric
info: |
  ## Beyond DevOps: The Missing Metric
  From Delivery to Organizational Value
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
---

# Beyond DevOps

<div class="pt-4 text-xl text-blue-200">The Missing Metric: Alignment</div>


<!--
Some text
-->

---
transition: fade-out
layout: center
class: text-center
---

# Have you heard of DORA metrics?

<v-click>
<div class="text-xl mt-8">How many of you currently <span class="text-yellow-300 font-bold">use</span> them?</div>
</v-click>

<v-click>
<div class="mt-8 p-6 bg-red-500 bg-opacity-20 rounded-lg text-2xl inline-block">
How many of you can name the <span class="text-red-300 font-bold">business outcome</span> they improved last quarter?
</div>
</v-click>


---
transition: slide-up
layout: image-right
image: /kamil_photo.png
---

# Who Am I?

<v-clicks>

-  **Kamil Senecki**
-  Agile Delivery Lead at **Pega**
-  Pega: Low-code platform for enterprise applications
-  Trying to understand people, systems, and why work matters

</v-clicks>

<v-click>
<div class="mt-6 p-4 bg-blue-500 bg-opacity-20 rounded-lg">
This talk comes from walking thousands of kilometers and thinking about one question...
</div>
</v-click>

---
layout: section
transition: slide-up
---

# Why Do We Do All of This?

---
layout: default
---

# So Often We Try to Answer "What?"

<div class="grid grid-cols-2 gap-8 mt-6">
<div>

<v-clicks>

Organizations ask us to:

- Build feature X
- Migrate to Kubernetes
- Automate deployments
- Reduce infrastructure costs

</v-clicks>

<v-click>
<div class="mt-4 p-4 bg-red-500 bg-opacity-20 rounded-lg">
Those are <span class="text-red-400 font-bold">tasks</span>. They describe work, not purpose or direction.
</div>
</v-click>

</div>

<v-click>
<div class="p-6 bg-blue-500 bg-opacity-20 rounded-lg">

### Every decision should answer:

<div class="text-2xl mt-4 text-cyan-500 font-bold">Who benefits — and how?</div>

<div class="mt-4 text-sm text-blue-500">If there is no clear benefit, there is no value — only <span class="text-yellow-500">activity</span>.</div>

</div>
</v-click>

</div>

<!--

-->

---
layout: center
class: text-center
---

# Activity ≠ Value

<div class="grid grid-cols-2 gap-8 mt-8 text-left max-w-3xl mx-auto">

<v-click>
<div class="p-6 bg-orange-500 bg-opacity-20 rounded-lg">
<div class="font-bold mb-3 text-orange-300">We obsessively measure activity:</div>

- Commits and deployments
- Velocity and story points
- Lead time and Mean Time To Recovery

</div>
</v-click>

<v-click>
<div class="p-6 bg-green-500 bg-opacity-20 rounded-lg">
<div class="font-bold mb-3 text-green-300">Almost nobody measures:</div>

- Customer outcomes and value
- Revenue, cost, and risk impact
- Learning, trust, and cooperation

</div>
</v-click>

</div>

---
layout: quote
class: text-center
---

# "When a measure becomes a target, it ceases to be a good measure."

<v-click>
<div class="mt-4 text-sm text-blue-200"> Goodhart's Law, 1975</div>
</v-click>

<v-click>
<div class="mt-8 p-6 bg-yellow-500 bg-opacity-20 rounded-lg inline-block text-xl">
When metrics become <span class="text-yellow-400 font-bold">targets</span>...<br/>
teams optimize them, not organizational outcomes.
</div>
</v-click>

---
layout: default
transition: slide-left
---

<div class="grid grid-cols-[1.15fr_0.85fr] gap-5 h-full">

<!-- LEFT COLUMN -->
<div>

# DevOps Became

<div class="mt-4 space-y-2 text-lg">

<v-click>

<div class="rounded-lg border border-slate-300 dark:border-slate-700 px-4 py-2 bg-slate-50 dark:bg-slate-800 shadow-sm">
🐳 Docker
</div>

</v-click>

<v-click>

<div class="rounded-lg border border-slate-300 dark:border-slate-700 px-4 py-2 bg-slate-50 dark:bg-slate-800 shadow-sm">
☸️ Kubernetes
</div>

</v-click>

<v-click>

<div class="rounded-lg border border-slate-300 dark:border-slate-700 px-4 py-2 bg-slate-50 dark:bg-slate-800 shadow-sm">
🏗 Terraform
</div>

</v-click>

<v-click>

<div class="rounded-lg border border-slate-300 dark:border-slate-700 px-4 py-2 bg-slate-50 dark:bg-slate-800 shadow-sm">
🌿 SysOps
</div>

</v-click>

<v-click>

<div class="rounded-lg border border-slate-300 dark:border-slate-700 px-4 py-2 bg-slate-50 dark:bg-slate-800 shadow-sm">
🚀 CI/CD Pipelines
</div>

</v-click>

</div>

<v-click>

<div class="mt-5 rounded-lg border-l-4 border-amber-500 bg-amber-50 dark:bg-amber-900/20 px-4 py-3 text-sm shadow-sm">

**Reality:** These are useful tools — but they are not the original DevOps idea.

</div>

</v-click>

</div>

<!-- RIGHT COLUMN -->
<div>

# It Was Always About

<div class="mt-4 space-y-4">

<v-click>

<div class="rounded-xl border border-blue-300/40 bg-blue-50 dark:bg-blue-900/20 p-4 shadow-sm">

<div class="font-semibold text-blue-700 dark:text-blue-300 text-xl">
Patrick Debois
</div>

<div class="text-xs opacity-70 mb-3">
Coined "DevOps" (2009)
</div>

Remove friction between **Dev** and **Ops**.

<div class="mt-3 italic opacity-80 text-sm">
A human/system problem — not a tooling problem.
</div>

</div>

</v-click>

<v-click>

<div class="rounded-xl border border-emerald-300/40 bg-emerald-50 dark:bg-emerald-900/20 p-4 shadow-sm">

<div class="font-semibold text-emerald-700 dark:text-emerald-300 text-xl">
Gene Kim
</div>

<div class="text-xs opacity-70 mb-3">
The Phoenix Project
</div>

Optimize the **flow of work** from idea to value.

<div class="mt-3 italic opacity-80 text-sm">
Not simply deployment automation.
</div>

</div>

</v-click>

</div>

</div>

</div>

<!--

-->

---
layout: default
---

# The Three Ways

<div class="grid grid-cols-3 gap-4 mt-8">

<v-click>
<div class="p-6 bg-blue-500 bg-opacity-30 rounded-lg text-center">
  <div class="text-4xl mb-3">🌊</div>
  <div class="font-bold text-xl mb-2">Flow</div>
  <div class="text-sm text-blue-200">Accelerate work from Dev through Ops to customer value</div>
</div>
</v-click>

<v-click>
<div class="p-6 bg-green-500 bg-opacity-30 rounded-lg text-center">
  <div class="text-4xl mb-3">🔁</div>
  <div class="font-bold text-xl mb-2">Feedback</div>
  <div class="text-sm text-green-200">Create fast, short feedback loops at every stage</div>
</div>
</v-click>

<v-click>
<div class="p-6 bg-purple-500 bg-opacity-30 rounded-lg text-center">
  <div class="text-4xl mb-3">🧪</div>
  <div class="font-bold text-xl mb-2">Continuous Learning</div>
  <div class="text-sm text-purple-200">Reduce risk through experimentation and learning</div>
</div>
</v-click>

</div>

<v-click>
<div class="mt-6 p-4 bg-yellow-500 bg-opacity-20 rounded-lg text-center text-xl">
Technology can <em>enable</em> these principles. It is not the principle itself.
</div>
</v-click>

---
layout: center
class: text-center
---

# The DORA Model

<v-click>
<div class="grid grid-cols-1 md:grid-cols-3 gap-4 mt-8 text-sm items-center">
<div class="p-4 bg-blue-500 bg-opacity-20 rounded-lg">
<div class="font-bold mb-2">Capabilities</div>
Technical practices → Culture → Feedback → Visibility → Leadership → Empowerment
</div>
<div class="flex items-center justify-center text-4xl">➡️</div>
<div class="p-4 bg-green-500 bg-opacity-20 rounded-lg">
<div class="font-bold mb-2">Software Delivery Performance</div>
Deploy frequency → Lead time → MTTR → Change failure rate
</div>
</div>
</v-click>

<v-click>
<div class="flex justify-center mt-4 text-4xl">⬇️</div>
<div class="p-4 bg-purple-500 bg-opacity-30 rounded-lg inline-block mt-2 text-xl font-bold">Organizational Performance</div>
</v-click>

<v-click>
<div class="mt-6 p-4 bg-red-500 bg-opacity-20 rounded-lg text-xl">
Software delivery performance is <span class="text-red-400 font-bold">not</span> the end goal.<br/>
<span class="text-green-300 font-bold text-2xl">Organizational performance is.</span>
</div>
</v-click>

---
layout: section
transition: slide-up
---

# What Is Value?
---
layout: center
class: text-center
---

# People Say "We Deliver Value"

<v-click>
<div class="text-3xl mt-8 text-blue-200">Nobody defines it.</div>
</v-click>

<v-click>
<div class="mt-8 p-6 bg-yellow-500 bg-opacity-20 rounded-lg inline-block text-xl">
Value is <span class="text-yellow-400 font-bold">contextual</span>.<br/>
Different stakeholders care about different outcomes.
</div>
</v-click>

---
layout: default
---

# Value Means Different Things

<div class="grid gap-4 mt-6 grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 auto-rows-fr">

<v-click>
<div class="p-4 bg-blue-500 bg-opacity-20 rounded-lg h-full flex flex-col">
<div class="font-bold text-blue-300">👤 Customer</div>
<div class="text-sm mt-2 text-blue-100">"I can solve my problem."</div>
</div>
</v-click>

<v-click>
<div class="p-4 bg-purple-500 bg-opacity-20 rounded-lg h-full flex flex-col">
<div class="font-bold text-purple-300">📈 CEO</div>
<div class="text-sm mt-2 text-purple-100">"We increased revenue."</div>
</div>
</v-click>

<v-click>
<div class="p-4 bg-green-500 bg-opacity-20 rounded-lg h-full flex flex-col">
<div class="font-bold text-green-300">🎧 Support</div>
<div class="text-sm mt-2 text-green-100">"Customers stopped calling."</div>
</div>
</v-click>

<v-click>
<div class="p-4 bg-yellow-500 bg-opacity-20 rounded-lg h-full flex flex-col">
<div class="font-bold text-yellow-300">🛠 Engineer</div>
<div class="text-sm mt-2 text-yellow-100">"We removed technical debt."</div>
</div>
</v-click>

<v-click>
<div class="p-4 bg-red-500 bg-opacity-20 rounded-lg h-full flex flex-col">
<div class="font-bold text-red-300">🔐 Security</div>
<div class="text-sm mt-2 text-red-100">"We reduced risk."</div>
</div>
</v-click>

<v-click>
<div class="p-4 bg-orange-500 bg-opacity-20 rounded-lg h-full flex flex-col">
<div class="font-bold text-orange-300">💰 Finance</div>
<div class="text-sm mt-2 text-orange-100">"We lowered operational cost."</div>
</div>
</v-click>

</div>

<v-click>
<div class="mt-6 p-4 bg-white bg-opacity-10 rounded-lg text-center text-xl">
Nobody is wrong. The challenge is <span class="text-cyan-400 font-bold">agreeing which value matters most now</span> — and aligning around it.
</div>
</v-click>

---
layout: section
transition: slide-up
---

# The Hammer Problem

---
layout: default
---

# If All You Have Is a Hammer...

<div class="grid grid-cols-2 gap-6 mt-6">

<div>
<v-click>
<div class="text-lg mb-4">Every discipline defaults to what it knows:</div>
</v-click>

<v-click>
<div class="p-3 bg-blue-500 bg-opacity-20 rounded-lg mb-2"> 🛠 <strong>Engineer:</strong> Kubernetes, platform, AI</div>
</v-click>
<v-click>
<div class="p-3 bg-purple-500 bg-opacity-20 rounded-lg mb-2"> 🧭 <strong>Leader:</strong> Reorganization, new process</div>
</v-click>
<v-click>
<div class="p-3 bg-yellow-500 bg-opacity-20 rounded-lg mb-2"> 💰 <strong>Finance:</strong> Budget cuts</div>
</v-click>
<v-click>
<div class="p-3 bg-orange-500 bg-opacity-20 rounded-lg"> ✅ <strong>Compliance:</strong> More approvals</div>
</v-click>
</div>

<v-click>
<div class="p-6 bg-red-500 bg-opacity-20 rounded-lg">

### Deployments are slow. Everyone has a solution:

<div class="text-sm mt-4 space-y-2">
<div>Engineer: <em>"Let's automate."</em></div>
<div>Leader: <em>"Let's restructure."</em></div>
<div>Manager: <em>"Let's create a meeting."</em></div>
<div>Security: <em>"Let's add approvals."</em></div>
</div>

<div class="mt-4 text-lg text-red-300 font-bold">
Nobody asks: <em>what problem are we actually solving?</em>
</div>

</div>
</v-click>

</div>

---
layout: section
transition: slide-up
---

# The Alignment Matrix

---
layout: default
---

# Three Dimensions of Optimization

<div class="grid grid-cols-3 gap-6 mt-8">

<v-click>
<div class="p-6 bg-blue-500 bg-opacity-20 rounded-lg text-center">
  <div class="text-4xl mb-3">🧑</div>
  <div class="font-bold text-xl text-blue-300 mb-3">Me</div>
  <div class="text-sm text-left space-y-1">
    <div>📚 Career growth</div>
    <div>🧠 Learning</div>
    <div>🏅 Recognition</div>
    <div>⬆️ Promotion</div>
  </div>
</div>
</v-click>

<v-click>
<div class="p-6 bg-green-500 bg-opacity-20 rounded-lg text-center">
  <div class="text-4xl mb-3">👥</div>
  <div class="font-bold text-xl text-green-300 mb-3">Team</div>
  <div class="text-sm text-left space-y-1">
    <div>🤝 Helping teammates</div>
    <div>🚚 Local delivery</div>
    <div>🛡 Psychological safety</div>
    <div>🔄 Shared ownership</div>
  </div>
</div>
</v-click>

<v-click>
<div class="p-6 bg-purple-500 bg-opacity-20 rounded-lg text-center">
  <div class="text-4xl mb-3">🏢</div>
  <div class="font-bold text-xl text-purple-300 mb-3">Organization</div>
  <div class="text-sm text-left space-y-1">
    <div>🎯 Business goals</div>
    <div>🧭 Strategy & mission</div>
    <div>👤 Customer outcomes</div>
    <div>🌱 Long-term success</div>
  </div>
</div>
</v-click>

</div>

<v-click>
<div class="mt-6 text-center text-xl text-blue-200">
Every employee optimizes all three — consciously or not.
</div>
</v-click>

---
layout: default
---

# The Alignment Patterns

<div class="mt-4 space-y-2 text-sm">

<v-click>
<div class="flex items-center gap-4 p-3 bg-orange-500 bg-opacity-20 rounded-lg">
  <div class="font-mono text-lg font-bold text-orange-400 w-16">100</div>
  <div class="font-bold w-52">Resume-Driven Development</div>
  <div class="text-gray-300">Personal growth at the expense of team and organization</div>
</div>
</v-click>

<v-click>
<div class="flex items-center gap-4 p-3 bg-blue-500 bg-opacity-20 rounded-lg">
  <div class="font-mono text-lg font-bold text-blue-400 w-16">010</div>
  <div class="font-bold w-52">Team Hero</div>
  <div class="text-gray-300">Great teammate, but low awareness of wider organizational goals</div>
</div>
</v-click>

<v-click>
<div class="flex items-center gap-4 p-3 bg-red-500 bg-opacity-30 rounded-lg border border-red-500">
  <div class="font-mono text-lg font-bold text-red-400 w-16">110</div>
  <div class="font-bold w-52">Engineering Silo</div>
  <div class="text-gray-300"><strong>Most common trap:</strong> local optimization without organizational impact</div>
</div>
</v-click>

<v-click>
<div class="flex items-center gap-4 p-3 bg-yellow-500 bg-opacity-20 rounded-lg">
  <div class="font-mono text-lg font-bold text-yellow-400 w-16">001</div>
  <div class="font-bold w-52">Lone Corporate Soldier</div>
  <div class="text-gray-300">Loyal to the organization, disconnected from the team. Risk: burnout</div>
</div>
</v-click>

<v-click>
<div class="flex items-center gap-4 p-3 bg-green-500 bg-opacity-20 rounded-lg">
  <div class="font-mono text-lg font-bold text-green-400 w-16">011</div>
  <div class="font-bold w-52">Aligned Realist</div>
  <div class="text-gray-300">Healthy sustainable state: team and organization aligned</div>
</div>
</v-click>

<v-click>
<div class="flex items-center gap-4 p-3 bg-cyan-500 bg-opacity-20 rounded-lg border border-cyan-500">
  <div class="font-mono text-lg font-bold text-cyan-400 w-16">111</div>
  <div class="font-bold w-52">Ideal State</div>
  <div class="text-gray-300">Full alignment: personal growth, team health, organizational success</div>
</div>
</v-click>

</div>

---
layout: center
class: text-center
---

<div class="text-6xl mb-6">⚠️</div>

# The Most Common Trap: 110 (Engineering Silo)

<v-click>
<div class="text-3xl font-mono mt-4 p-4 bg-red-500 bg-opacity-20 rounded-lg inline-block">
<span class="text-white">Me </span><span class="text-green-400">✓</span>
<span class="text-white ml-6">Team </span><span class="text-green-400">✓</span>
<span class="text-white ml-6">Org </span><span class="text-red-400">✗</span>
</div>
</v-click>

<v-click>
<div class="mt-6 text-2xl">
I succeed. My team succeeds. <span class="text-red-400 font-bold">The organization doesn't.</span>
</div>
</v-click>

<v-click>
<div class="mt-4 text-lg text-blue-200">
<em>"I implemented Kubernetes because I wanted the experience."</em><br/>
<em>"Our team has perfect velocity. Nobody else benefits."</em>
</div>
</v-click>

<v-click>
<div class="mt-6 p-4 bg-yellow-500 bg-opacity-20 rounded-lg text-xl">
This is common in large engineering organizations because local success is easier to see than organizational value.
</div>
</v-click>

---
layout: center
class: text-center
---

<div class="text-6xl mb-4">✅</div>

# The Goal: 111 (Ideal State)

<v-click>
<div class="text-3xl font-mono mt-4 p-4 bg-cyan-500 bg-opacity-20 rounded-lg inline-block">
<span class="text-white">Me </span><span class="text-green-400">✓</span>
<span class="text-white ml-6">Team </span><span class="text-green-400">✓</span>
<span class="text-white ml-6">Org </span><span class="text-green-400">✓</span>
</div>
</v-click>

<v-clicks>
<div class="mt-6 text-xl">Personal growth</div>
<div class="text-xl">+ Healthy team</div>
<div class="text-xl">+ Organizational success</div>
</v-clicks>

<v-click>
<div class="mt-4 p-4 bg-green-500 bg-opacity-20 rounded-lg text-xl">
Not perfect harmony — but a clear line of sight between growth, teamwork, and outcomes.<br/>
<span class="text-cyan-400 font-bold">Rare, but worth designing for.</span>
</div>
</v-click>

---
layout: center
class: text-center
---

# The Metric You Choose Shapes the Culture You Get

<v-clicks>
<div class="mt-6 p-4 bg-blue-500 bg-opacity-20 rounded-lg text-lg">Optimize individual metrics → people optimize <strong>themselves</strong></div>
<div class="p-4 bg-yellow-500 bg-opacity-20 rounded-lg text-lg">Optimize team metrics → teams optimize <strong>locally</strong></div>
<div class="p-4 bg-green-500 bg-opacity-20 rounded-lg text-lg">Optimize organizational outcomes → teams <strong>cooperate</strong></div>
</v-clicks>

<v-click>
<div class="mt-6 p-6 text-2xl">
The optimization target determines the behavior.
</div>
</v-click>

---
layout: section
transition: slide-up
---

# Alignment Requires Visibility

---
layout: default
---

# Questions Everyone Should Answer

<div class="text-2xl text-orange-300 mb-6">
You cannot optimize what you don't understand.
</div>

<div class="grid grid-cols-2 gap-4">

<v-click>

<div class="p-4 rounded-lg border border-blue-400/30 bg-blue-500/10">
<div class="text-sm uppercase tracking-wide text-blue-300 mb-1">Strategy</div>

**What is our company strategy this year?**
</div>

</v-click>

<v-click>

<div class="p-4 rounded-lg border border-blue-400/30 bg-blue-500/10">
<div class="text-sm uppercase tracking-wide text-blue-300 mb-1">Success</div>

**What does success look like for our team this quarter?**
</div>

</v-click>

<v-click>

<div class="p-4 rounded-lg border border-blue-400/30 bg-blue-500/10">
<div class="text-sm uppercase tracking-wide text-blue-300 mb-1">Alignment</div>

**How does my work contribute to that?**
</div>

</v-click>

<v-click>

<div class="p-4 rounded-lg border border-blue-400/30 bg-blue-500/10">
<div class="text-sm uppercase tracking-wide text-blue-300 mb-1">Customer</div>

**What customer problem am I solving?**
</div>

</v-click>

</div>

<v-click>

<div class="mt-8 text-center text-2xl">

Most people **can't answer these.**

<div class="mt-2 text-lg text-gray-300">
Not because they don't care.
</div>

<div class="text-red-300 font-semibold text-xl">
Because nobody told them.
</div>

</div>

</v-click>

---
layout: default
---

# Value Stream Mapping

<v-click>

<div class="flex items-center justify-between gap-2 mt-10 text-center text-sm">

<div class="flex-1 p-3 rounded-lg bg-blue-500/15 border border-blue-400/30">
💡<br/>
<b>Idea</b>
</div>

<div class="text-3xl">→</div>

<div class="flex-1 p-3 rounded-lg bg-blue-500/15 border border-blue-400/30">
🛠<br/>
<b>Development</b>
</div>

<div class="text-3xl">→</div>

<div class="flex-1 p-3 rounded-lg bg-blue-500/15 border border-blue-400/30">
🚀<br/>
<b>Deployment</b>
</div>

<div class="text-3xl">→</div>

<div class="flex-1 p-3 rounded-lg bg-yellow-500/15 border border-yellow-400/30">
👤<br/>
<b>Customer Use</b>
</div>

<div class="text-3xl">→</div>

<div class="flex-1 p-3 rounded-lg bg-green-500/20 border border-green-400/40 font-semibold">
📈<br/>
<b>Business Outcome</b>
</div>

</div>

</v-click>

<v-click>

<div class="mt-10 text-center text-2xl">

Most organizations stop at
<span class="text-blue-300 font-bold">Deployment.</span>

<div class="mt-2 text-green-400 font-bold text-3xl">
Value ends at Business Outcome.
</div>

</div>

</v-click>

---
layout: section
transition: slide-up
---

# Can We Measure Alignment?

---
layout: center
class: text-center
---

# We Don't Measure It Directly

<v-click>
<div class="text-xl mt-8 text-blue-200">
Just like DORA does not measure "engineering excellence" directly — it measures <span class="text-yellow-400 font-bold">observable signals</span> that predict it.
</div>
</v-click>

<v-click>
<div class="mt-8 p-6 bg-blue-500 bg-opacity-20 rounded-lg text-2xl inline-block">
Alignment works the same way.<br/>
<span class="text-cyan-400 font-bold">We measure its signals.</span>
</div>
</v-click>

---
layout: default
---

# Signal 1: Strategy Awareness 🧭

<v-click>
<div class="p-4 bg-blue-500 bg-opacity-20 rounded-lg mb-4">Ask every engineer on your team:</div>
</v-click>

<v-clicks>

- What are this quarter's **three company priorities**?
- How does your team's work **support them**?
- What **business outcome** does your current project improve?

</v-clicks>

<v-click>
<div class="mt-6 grid grid-cols-2 gap-4">
<div class="p-4 bg-red-500 bg-opacity-20 rounded-lg text-center">
Everyone gives <span class="text-red-400 font-bold">different answers</span><br/>alignment is low
</div>
<div class="p-4 bg-red-600 bg-opacity-30 rounded-lg text-center">
Nobody can answer<br/>alignment is <span class="text-red-400 font-bold">absent</span>
</div>
</div>
</v-click>

<v-click>
<div class="mt-4 p-4 bg-green-500 bg-opacity-20 rounded-lg text-center text-lg">
This is the <span class="text-green-400 font-bold">fastest alignment diagnostic</span> available. Run it today.
</div>
</v-click>

---
layout: default
---

# Signal 2: Goal Traceability 🔗

<div class="text-xl text-gray-300 mb-6">
Can every ticket be traced back to strategy?
</div>

<v-click>

<div class="flex flex-wrap items-center justify-center gap-2 text-center text-sm">

<div class="px-3 py-2 rounded bg-gray-700">
Task
</div>

<div class="text-2xl text-gray-400">←</div>

<div class="px-3 py-2 rounded bg-gray-700">
User Story
</div>

<div class="text-2xl text-gray-400">←</div>

<div class="px-3 py-2 rounded bg-gray-700">
Epic
</div>

<div class="text-2xl text-gray-400">←</div>

<div class="px-3 py-2 rounded bg-gray-700">
Objective
</div>

<div class="text-2xl text-gray-400">←</div>

<div class="px-3 py-2 rounded bg-gray-700">
Business Goal
</div>

<div class="text-2xl text-gray-400">←</div>

<div class="px-3 py-2 rounded bg-blue-600 font-semibold">
Strategy
</div>

</div>

</v-click>

<v-click>

<div class="mt-10 text-center">

<div class="text-2xl font-semibold">
If the chain breaks anywhere,
<span class="text-yellow-400">alignment breaks there too.</span>
</div>

<div class="mt-4 text-lg text-gray-300">
Try this with five random Stories or Tickets your Team is working on right now.
</div>

</div>

</v-click>

---
layout: default
---

# Signal 3: Decision Feedback 🔁

After every major initiative, ask in sequence:

<v-clicks>
<div class="p-3 bg-green-500 bg-opacity-20 rounded-lg mt-2">1. ✅ Did we build it?</div>
<div class="p-3 bg-yellow-500 bg-opacity-20 rounded-lg mt-2">2. 👀 Did customers use it?</div>
<div class="p-3 bg-yellow-500 bg-opacity-20 rounded-lg mt-2">3. 🔄 Did it change their behavior?</div>
<div class="p-3 bg-yellow-500 bg-opacity-20 rounded-lg mt-2">4. 📈 Did it improve a business metric?</div>
<div class="p-3 bg-blue-500 bg-opacity-20 rounded-lg mt-2">5. 🧠 What did we learn?</div>
</v-clicks>

<v-click>
<div class="mt-4 p-4 bg-red-500 bg-opacity-20 rounded-lg text-center text-lg">
Most teams stop at question 1.<br/>
Without questions 4 and 5, there is only <span class="text-red-400 font-bold">delivery</span> — no alignment signal.
</div>
</v-click>

---
layout: default
---

# Signal 4: Alignment Survey 📝

<v-click>
<div class="p-4 bg-blue-500 bg-opacity-20 rounded-lg mb-4">
Not a satisfaction survey. A quarterly <strong>alignment diagnostic</strong>:
</div>
</v-click>

<v-clicks>
<div class="p-3 bg-gray-700 rounded-lg mt-2 text-sm"> "I understand the company's strategy."</div>
<div class="p-3 bg-gray-700 rounded-lg mt-2 text-sm"> "I know how my work contributes to our goals."</div>
<div class="p-3 bg-gray-700 rounded-lg mt-2 text-sm"> "My team's priorities are consistent with company goals."</div>
<div class="p-3 bg-gray-700 rounded-lg mt-2 text-sm"> "When priorities change, leadership explains why."</div>
<div class="p-3 bg-gray-700 rounded-lg mt-2 text-sm"> "I receive feedback about the business impact of my work."</div>
</v-clicks>

<v-click>
<div class="mt-4 p-4 bg-yellow-500 bg-opacity-20 rounded-lg text-center text-lg">
The score isn't the point. <span class="text-yellow-400 font-bold">The trend is.</span>
</div>
</v-click>

---
layout: default
---

# Signal 5: The Five Whys on Any Ticket ❓

<v-click>
<div class="text-center mt-2">
<div class="inline-flex flex-col items-center gap-1 text-sm">
<div class="p-2 bg-gray-600 rounded w-72 text-center">Upgrade PostgreSQL</div>
<div class="text-gray-400"> Why?</div>
<div class="p-2 bg-gray-600 rounded w-72 text-center">Security patches are required</div>
<div class="text-gray-400"> Why does that matter?</div>
<div class="p-2 bg-gray-600 rounded w-72 text-center">Reduces operational risk</div>
<div class="text-gray-400"> Why does that matter?</div>
<div class="p-2 bg-gray-600 rounded w-72 text-center">Meets compliance requirements</div>
<div class="text-gray-400"> Why does that matter?</div>
<div class="p-2 bg-gray-600 rounded w-72 text-center">Enables enterprise customers</div>
<div class="text-gray-400"> Why does that matter?</div>
<div class="p-2 bg-green-600 rounded w-72 text-center font-bold"> Supports company revenue growth</div>
</div>
</div>
</v-click>

<v-click>
<div class="mt-4 p-4 bg-red-500 bg-opacity-20 rounded-lg text-center">
If the chain ends after only one or two "whys," <span class="text-red-400 font-bold">alignment is weak.</span>
</div>
</v-click>

---
layout: default
---

# Signal 6: Feedback Loops 🔄

<div class="text-xl text-gray-300 mb-8">
How quickly do decisions become learning?
</div>

<v-click>

<div class="flex flex-wrap items-center justify-center gap-2 text-center text-sm">

<div class="px-3 py-2 rounded bg-blue-500/15 border border-blue-400/30">
🧭<br/><b>Decision</b>
</div>

<div class="text-2xl text-gray-400">→</div>

<div class="px-3 py-2 rounded bg-blue-500/15 border border-blue-400/30">
🛠<br/><b>Implementation</b>
</div>

<div class="text-2xl text-gray-400">→</div>

<div class="px-3 py-2 rounded bg-blue-500/15 border border-blue-400/30">
📦<br/><b>Outcome</b>
</div>

<div class="text-2xl text-gray-400">→</div>

<div class="px-3 py-2 rounded bg-yellow-500/15 border border-yellow-400/30">
💬<br/><b>Feedback</b>
</div>

<div class="text-2xl text-gray-400">→</div>

<div class="px-3 py-2 rounded bg-green-500/15 border border-green-400/30">
🧠<br/><b>Learning</b>
</div>

<div class="text-2xl text-gray-400">→</div>

<div class="px-3 py-2 rounded bg-green-600/20 border border-green-500/40 font-semibold">
🎯<br/><b>Better Decisions</b>
</div>

</div>

</v-click>

<v-click>

<div class="mt-10 text-center">

<div class="text-2xl">
How long does a deployment take to generate a
<span class="text-blue-300 font-semibold">business signal?</span>
</div>

<div class="mt-4 text-3xl text-red-400 font-bold">
Months—or never? That's your alignment gap.
</div>

</div>

</v-click>

---
layout: quote
class: text-center
---

# Alignment isn't measured by a dashboard.

<v-click>
<div class="text-xl mt-6 text-white">
It's observed through conversations, decisions, and feedback loops.
</div>
</v-click>

<v-click>
<div class="mt-8 p-6 bg-red-500 bg-opacity-20 rounded-lg text-2xl inline-block">
Without feedback, <span class="text-red-400 font-bold">alignment decays.</span>
</div>
</v-click>

---
layout: section
transition: slide-up
---

# Trust Is the Multiplier

---
layout: center
class: text-center
---

# Every Transformation Eventually Becomes a People Problem

<v-click>
<div class="text-2xl mt-6 p-6 bg-blue-500 bg-opacity-20 rounded-lg inline-block">
Technology scales only as far as <span class="text-cyan-400 font-bold">trust allows</span>.
</div>
</v-click>

---
layout: two-cols
---

# Without Trust 🚫

<v-clicks>

-  🤐 People hide information
-  🏃 Teams avoid responsibility
-  🧱 Groups protect territory
-  🎯 Everyone optimizes locally
-  🙈 Failures stay hidden
-  ✅ Code reviews become rubber stamps

</v-clicks>

::right::

# With Trust ✅

<v-clicks>

-  💬 Information flows freely
-  🔎 Mistakes surface early
-  🤝 Teams collaborate freely
-  ⚡ Conflicts become productive
-  🧠 Organizations learn faster
-  🧾 Post-mortems are honest

</v-clicks>

---
layout: default
---

# Lencioni's Dysfunctions — Engineering Edition

<div class="flex justify-center mt-2">
<div class="w-full max-w-xl flex flex-col-reverse leading-tight">

<v-click>
<div class="bg-red-500/40 py-3 px-4 text-center rounded-b-lg">
  <div class="font-bold">Absence of Trust</div>
  <div class="text-xs">
    Hidden failures • blame culture
  </div>
</div>
</v-click>

<v-click>
<div class="bg-yellow-500/30 py-2 px-4 text-center mx-8">
  <div class="font-bold">Fear of Conflict</div>
  <div class="text-xs">
    Rubber-stamp code reviews
  </div>
</div>
</v-click>

<v-click>
<div class="bg-green-500/30 py-2 px-4 text-center mx-16">
  <div class="font-bold">Lack of Commitment</div>
  <div class="text-xs">
    "We agreed, but..."
  </div>
</div>
</v-click>

<v-click>
<div class="bg-blue-500/30 py-2 px-4 text-center mx-24">
  <div class="font-bold">Avoidance of Accountability</div>
  <div class="text-xs">
    Broken builds nobody fixes
  </div>
</div>
</v-click>

<v-click>
<div class="bg-purple-500/30 py-2 px-4 text-center rounded-t-lg mx-32">
  <div class="font-bold">Inattention to Results</div>
  <div class="text-xs">
    Velocity over outcomes
  </div>
</div>
</v-click>

</div>
</div>

<v-click>

<div class="text-center mt-4 text-lg">

Many engineering problems are

<span class="text-red-400 font-bold">
organizational trust problems
</span>

in disguise.

</div>

</v-click>

---
layout: default
---

# Westrum's Culture Model

<div class="grid grid-cols-3 gap-4 mt-8">

<v-click>
<div class="p-4 bg-red-500 bg-opacity-20 rounded-lg">
  <div class="font-bold text-xl text-red-400 mb-3">Pathological</div>
  <div class="text-sm space-y-1">
    <div>🤐 Information hidden</div>
    <div>👉 Failure = blame</div>
    <div>🏹 Messengers shot</div>
    <div>🏃 Responsibility avoided</div>
  </div>
</div>
</v-click>

<v-click>
<div class="p-4 bg-yellow-500 bg-opacity-20 rounded-lg">
  <div class="font-bold text-xl text-yellow-400 mb-3">Bureaucratic</div>
  <div class="text-sm space-y-1">
    <div>📋 Rule-bound processes</div>
    <div>😐 Failure = tolerated</div>
    <div>🧱 Siloed information</div>
    <div>📦 Narrow responsibilities</div>
  </div>
</div>
</v-click>

<v-click>
<div class="p-4 bg-green-500 bg-opacity-20 rounded-lg border border-green-500">
  <div class="font-bold text-xl text-green-400 mb-3">Generative</div>
  <div class="text-sm space-y-1">
    <div>💬 Information flows freely</div>
    <div>🧠 Failure = learning</div>
    <div>🤝 Collective responsibility</div>
    <div>🔄 Continuous improvement</div>
  </div>
</div>
</v-click>

</div>

<v-click>
<div class="mt-6 p-4 bg-green-500 bg-opacity-10 rounded-lg text-center text-lg">
Generative cultures <span class="text-green-400 font-bold">consistently outperform others</span> on every DORA metric.
</div>
</v-click>

---
layout: center
---

# Charles Green's Trust Equation

<v-click>
<div class="text-center mt-8 p-8 bg-gradient-to-r from-blue-500/20 to-purple-500/20 rounded-xl">
<div class="text-4xl font-mono">
Trust = <span class="text-green-400">(C + R + I)</span> / <span class="text-red-400">S</span>
</div>
</div>
</v-click>

<v-click>
<div class="grid grid-cols-4 gap-4 mt-8 text-center">

<div class="p-4 bg-green-500 bg-opacity-20 rounded-lg">
  <div class="text-2xl mb-2">C</div>
  <div class="font-bold">Credibility</div>
  <div class="text-xs text-green-200 mt-1">"Do I believe what you say?"</div>
</div>

<div class="p-4 bg-green-500 bg-opacity-20 rounded-lg">
  <div class="text-2xl mb-2">R</div>
  <div class="font-bold">Reliability</div>
  <div class="text-xs text-green-200 mt-1">"Can I count on you?"</div>
</div>

<div class="p-4 bg-green-500 bg-opacity-20 rounded-lg">
  <div class="text-2xl mb-2">I</div>
  <div class="font-bold">Intimacy</div>
  <div class="text-xs text-green-200 mt-1">"Do I feel safe with you?"</div>
</div>

<div class="p-4 bg-red-500 bg-opacity-20 rounded-lg">
  <div class="text-2xl mb-2">S</div>
  <div class="font-bold">Self-Orientation</div>
  <div class="text-xs text-red-200 mt-1">"Whose agenda comes first?"</div>
</div>

</div>
</v-click>

---
layout: center
class: text-center
---

# The Denominator Is Dangerous!

<v-click>
<div class="text-xl mt-8 max-w-2xl mx-auto">
You can have <span class="text-green-400">high credibility</span>, <span class="text-green-400">high reliability</span>, <span class="text-green-400">high intimacy</span>...
</div>
</v-click>

<v-click>
<div class="text-2xl mt-6 p-6 bg-red-500 bg-opacity-20 rounded-lg">
But if your <span class="text-red-400 font-bold">self-orientation is high</span>, trust <span class="text-red-400">collapses</span>.
</div>
</v-click>

<v-click>
<div class="mt-4 text-lg text-cyan-400">
In the Alignment Matrix: high self-orientation keeps people stuck in the <strong>x00</strong> states.
</div>
</v-click>

<v-click>
<div class="mt-4 text-xl text-white">
A brilliant engineer who is CV-driven or empire-building<br/>
destroys team trust <span class="text-red-400 font-bold">faster</span> than a mediocre one who genuinely cares.
</div>
</v-click>

---
layout: section
transition: slide-up
---

# Closing

---
layout: center
class: text-center
---

# The Missing Metric Is NOT...

<v-clicks>

<div class="mt-4 mb-2 py-2 px-4 bg-gray-700 rounded-lg text-lg line-through text-gray-400">
Deployment Frequency
</div>

<div class="mb-2 py-2 px-4 bg-gray-700 rounded-lg text-lg line-through text-gray-400">
Lead Time for Changes
</div>

<div class="mb-2 py-2 px-4 bg-gray-700 rounded-lg text-lg line-through text-gray-400">
Mean Time To Recovery
</div>

<div class="mb-2 py-2 px-4 bg-gray-700 rounded-lg text-lg line-through text-gray-400">
Story Points or Velocity
</div>

<div class="mb-2 py-2 px-4 bg-gray-700 rounded-lg text-lg line-through text-gray-400">
Platform Engineering maturity
</div>

<div class="py-2 px-4 bg-gray-700 rounded-lg text-lg line-through text-gray-400">
Kubernetes adoption or AI utilization
</div>

</v-clicks>

<v-click>

<div class="mt-5 text-xl text-blue-200">
Those tell us <span class="text-white font-bold">how</span> we build.<br/>
They don't tell us
<span class="text-yellow-400 font-bold">whether we're building what matters.</span>
</div>

</v-click>

---
layout: center
class: text-center
---

<div class="mt-6 p-8 bg-gradient-to-r from-blue-500/20 to-purple-500/20 rounded-xl max-w-3xl mx-auto">
The missing metric is <span class="text-cyan-400 font-bold text-2xl">alignment</span>.
</div>

<v-click>
<div class="mt-8 text-xl text-white max-w-2xl mx-auto">
Alignment between engineering and business.<br/>
Between teams and strategy.<br/>
Between daily work and organizational goals.
</div>
</v-click>

---
layout: center
class: text-center
---

# The Final Equation

<v-click>
<div class="mt-8 p-8 bg-blue-500 bg-opacity-10 rounded-xl font-mono text-xl text-left inline-block">
<div class="mb-2"><span class="text-blue-400 font-bold">DevOps</span>    = 🌊 The flow mechanism</div>
<div class="mb-2"><span class="text-purple-400 font-bold">Trust</span>     = ✖️ The multiplier</div>
<div class="mb-2"><span class="text-cyan-400 font-bold">Alignment</span> = 🧭 The missing metric</div>
<div class="mb-2"><span class="text-green-400 font-bold">Value</span>     = 🎯 The destination</div>
</div>
</v-click>

<v-click>
<div class="mt-6 text-xl text-white">
DevOps is not the destination.<br/>
It is one of the ways we get there.
</div>
</v-click>

<v-click>
<div class="mt-4 text-2xl text-cyan-400 font-bold">
Trust is the multiplier. Alignment is the missing metric.
</div>
</v-click>

---
layout: default
---

# My Challenge to You

<div class="grid grid-cols-3 gap-6 mt-8">

<v-click>
<div class="p-6 bg-blue-500 bg-opacity-20 rounded-lg text-center">
  <div class="text-4xl mb-4">📅</div>
  <div class="text-xl font-bold mb-2">This Week</div>
  <div class="text-sm text-blue-200">
    Pick any task in your backlog. Ask "Why?" five times. See if you reach a business outcome.
    <br/><br/>
    <span class="text-blue-300">If you can't, that's your first alignment signal.</span>
  </div>
</div>
</v-click>

<v-click>
<div class="p-6 bg-green-500 bg-opacity-20 rounded-lg text-center">
  <div class="text-4xl mb-4">🗓️</div>
  <div class="text-xl font-bold mb-2">This Month</div>
  <div class="text-sm text-green-200">
    Run a strategy awareness session. Ask: "What are our three company priorities this quarter?"
    <br/><br/>
    <span class="text-green-300">The gaps in understanding are the gaps in alignment.</span>
  </div>
</div>
</v-click>

<v-click>
<div class="p-6 bg-purple-500 bg-opacity-20 rounded-lg text-center">
  <div class="text-4xl mb-4">📍</div>
  <div class="text-xl font-bold mb-2">This Quarter</div>
  <div class="text-sm text-purple-200">
    Map one value stream from idea to business outcome. Find where visibility breaks.
    <br/><br/>
    <span class="text-purple-300">That is where your alignment work begins.</span>
  </div>
</div>
</v-click>

</div>

---
layout: center
class: text-center
---

# Let's Connect! 🤝

<div class="grid grid-cols-2 gap-12 mt-8 items-center">

<div class="text-left">

<v-click>
<div class="p-4 bg-blue-500/20 rounded-lg mb-4 flex items-center gap-4">
  <div class="text-3xl">🌐</div>
  <div>
    <div class="text-sm text-blue-200">Website</div>
    <div class="text-xl font-bold text-cyan-400">
      zwinnapanda.pl
    </div>
  </div>
</div>
</v-click>

<v-click>
<div class="p-4 bg-blue-700/30 rounded-lg mb-4 flex items-center gap-4">
  <div class="text-3xl">💼</div>
  <div>
    <div class="text-sm text-blue-200">LinkedIn</div>
    <div class="text-xl font-bold text-blue-400">
      linkedin.com/in/kamilsenecki
    </div>
  </div>
</div>
</v-click>

<v-click>
<div class="p-4 bg-green-500/20 rounded-lg flex items-center gap-4">
  <div class="text-3xl">📊</div>
  <div>
    <div class="text-sm text-green-200">Slides</div>
    <div class="text-lg font-bold text-green-400">
      missingmetric.zwinnapanda.pl
    </div>
  </div>
</div>
</v-click>

</div>

<v-click>

<div class="p-8 bg-white rounded-xl">
  <div class="text-sm text-neutral-500 mb-3">
    Scan to get the slides
  </div>

  <div class="w-48 h-48 bg-gray-200 rounded-lg flex items-center justify-center mx-auto border-4 border-dashed border-gray-400">
    <!-- QR -->
  </div>
</div>

</v-click>

</div>

<div class="mt-8 text-blue-200 text-sm">
Kamil Senecki • ZwinnaPanda.pl
</div>