<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,100:243B55&height=180&section=header&text=Pratik&fontSize=46&fontAlignY=44&fontColor=e8e8e8&desc=full-stack%20%C2%B7%20Pune%20%C2%B7%20building%20%40burnix%2Fcli&descSize=18&descAlignY=65" alt="Pratik — full-stack, Pune, building @burnix/cli" width="100%" />

<a href="https://readme-typing-svg.demolab.com/">
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=20&duration=3500&pause=1500&color=8B949E&center=true&vCenter=true&width=740&height=45&lines=Full-stack+engineer+in+Pune;I+ship+things%2C+break+them+under+load%2C+then+write+down+why;Currently%3A+hard+spend+caps+for+LLM+API+calls" alt="Typing SVG" />
</a>

<p>
  <a href="https://www.npmjs.com/package/@burnix/cli">npm</a> &nbsp;·&nbsp;
  <a href="mailto:pratik2k08@gmail.com">email</a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141E30,100:243B55&height=2&section=header" width="100%" alt="" />

</div>

<br />

<div align="center">

18, first-year CS student in Pune. Full-stack — mostly Node, Postgres, and React.

</div>

<br />

<div align="center">
<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=26&duration=1&pause=999999&color=E8E8E8&center=true&vCenter=true&width=300&height=40&lines=burnix" alt="burnix" />
</div>

<div align="center">

A fuse for LLM API spend. Wraps any command, tracks real cost per call,<br />
and refuses the next request once a cap is hit.

</div>

<p align="center">
  <img src="https://raw.githubusercontent.com/pr3tik/burnix/main/demo/demo.gif" alt="burnix demo: live spend climbing toward a cap, then tripping mid-run" width="680" />
</p>

<div align="center">

```bash
npm install -g @burnix/cli
burnix --cap 5.00 -- npm run agent
```

</div>

Provider-side spend limits run off billing pipelines that lag by minutes to hours — fine for a forgotten VM, useless for an agent in a retry loop.

My first version was wrong by **4.2x** under parallel load: twenty concurrent requests all read the same stale `spent` value before any completed. The fix reserves worst-case cost *before* each call, so the cap holds under concurrency.

<div align="center">

→ &nbsp;[**`pr3tik/burnix`**](https://github.com/pr3tik/burnix) &nbsp;·&nbsp; [**npm**](https://www.npmjs.com/package/@burnix/cli)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141E30,100:243B55&height=2&section=header" width="100%" alt="" />

</div>

<br />

<div align="center">
<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=26&duration=1&pause=999999&color=E8E8E8&center=true&vCenter=true&width=300&height=40&lines=stack" alt="stack" />
</div>

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,nodejs,react,vite,tailwind&theme=dark" alt="TypeScript, JavaScript, Node.js, React, Vite, Tailwind" />

<img src="https://skillicons.dev/icons?i=postgres,supabase,vercel,git,python&theme=dark" alt="PostgreSQL, Supabase, Vercel, Git, Python" />

</div>

<br />

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141E30,100:243B55&height=2&section=header" width="100%" alt="" />

</div>

<br />

<div align="center">
<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=26&duration=1&pause=999999&color=E8E8E8&center=true&vCenter=true&width=340&height=40&lines=currently" alt="currently" />
</div>

At **FschoolAI**, where I own four production surfaces — landing page, in-app navigation, Study Assistant, and Study Rooms — from Postgres schema through serverless endpoints to UI.

Most of what I've learned there came from things breaking: recovering a platform-wide outage from a Row-Level Security misconfiguration across 21 tables, and tracking down a schema/type mismatch that was silently dropping writes.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141E30,100:243B55&height=2&section=header" width="100%" alt="" />

</div>

<br />

<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=17&duration=4000&pause=1200&color=8B949E&center=true&vCenter=true&width=760&height=40&lines=The+gap+between+%22the+demo+works%22+and+%22it+holds+under+load%22;is+most+of+what's+actually+hard+about+shipping" alt="Interested in" />

<br /><br />

<a href="mailto:pratik2k08@gmail.com"><b>pratik2k08@gmail.com</b></a> &nbsp;·&nbsp; open to freelance work

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:243B55,100:141E30&height=100&section=footer" width="100%" alt="" />

</div>
