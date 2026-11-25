<!--
  bcneal666 — profile README
  COLOUR RULE (do not break):
    #00FF00 is the primary colour. Contrast is 1.37:1 on #ffffff (invisible) and
    13.7:1 on #0d1117. GitHub strips all CSS, so markdown text colour cannot be set.
    => EVERY green element must carry its own dark ground: an SVG whose root has
       background=0D1117, a shields capsule with labelColor/color=0D1117, or a card
       theme that paints a solid dark rect (chartreuse_dark paints #000).
    => Because nothing relies on the reader's theme colour, <picture> +
       prefers-color-scheme is NOT needed. Light and dark render identically.
  Section headings are readme-typing-svg images: it inlines Press Start 2P as a
    base64 @font-face, so the pixel font renders on every client. Heading text must
    stay ASCII — the font has no arrow/CJK glyphs and would render tofu. Headings
    sit flush to the left edge of the bar: SVG collapses leading whitespace, so a
    padded prefix has no effect — flush-left reads as a terminal prompt anyway.
    Trade-off accepted: headings are images, so there is no heading anchor. The alt
    text carries the semantics — never ship one of these without a descriptive alt.
  HARD RULE — a 200 is NOT a verification. Every SVG source here must parse as
    well-formed XML before it ships. A browser loading an SVG through <img> parses
    it STRICTLY: one malformed token and the whole image silently fails to render,
    with no console error and no clue in the response headers. Learned the hard
    way: readme-svg-typing-generator's matrix endpoint emits a BARE, unescaped
    ampersand among its rain glyphs (same byte offset on every request, at every
    width and height), so it returned a perfectly healthy 200 and rendered as a
    broken-image icon for everyone. Check with an XML parser, not with curl -w.
  tech-stack cards fail in TWO different ways, and only one of them is loud:
    - an unknown SHIELDS slug renders "404: badge not found" (loud). This is why
      the C# label must be DOUBLE-encoded as C%2523; a plain C%23 404s.
    - a slug shields knows but SIMPLE-ICONS does not renders a perfectly normal
      badge with NO LOGO (silent). simple-icons dropped `csharp` — it 404s on
      cdn.simpleicons.org — so C# now borrows the `dotnet` mark. `shadcn` is the
      same trap; the real slug is `shadcnui`.
    So verify a card by counting: the number of href="data:image/svg" occurrences
    must equal the number of badges. Checking only for "404: badge not found"
    misses every silent case.
    Also: fontFamily= is quoted as a family name, so the generic keyword
    'monospace' is invalid CSS there — pass a real face like Courier New.
  matrix.svg is ours, committed to this repo, precisely so no third party can
    break it again. Edit the file itself; the rules live in its header comment.
  assets/h-*.svg are the static ">_" section headings, downloaded once from
    readme-typing-svg (duration=1, so they never animate anyway) and committed for
    the same reason as matrix.svg. The font is already inlined, so they are
    self-contained. Regenerate by re-downloading with a new `lines=` value, then
    run them through an XML parser. Only the two animated hero lines still hit
    the live service.
  Contact is the issue form in .github/ISSUE_TEMPLATE/contact.yml — GitHub has no
    DMs and the profile deliberately exposes no email.
  Deliberately NOT used:
    readme-svg-typing-generator's matrix animation (invalid XML — see above; its
      other nine animations are well-formed, but this profile no longer needs them),
    github-readme-activity-graph (402 paywall on every host),
    github-profile-summary-cards + streak-stats (all repos are private — language
      cards count public repos only, streak needs private contributions exposed),
    github-readme-stats (503), github-profile-trophy (402), wakatime card (503),
    metrics.lecoq.io hosted instance (500), repobeats (500),
    ghchart.rshah.org (takes a custom hex, but hard-codes #EEEEEE for empty cells —
      a glaring pale grid on a dark theme, which breaks the colour rule above),
    capsule-render (emits <text> without inlining the font — pixel type falls back
      to the reader's system sans),
    plain markdown headings (cannot be coloured).
-->

<div align="center">

<img alt="Better call Neal" src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=40&duration=1200&pause=1000&color=00FF00&background=0D1117&center=true&vCenter=true&repeat=false&width=830&height=80&lines=Better+call+Neal">

<img alt="AI agents / LLM apps engineer — TypeScript, Next.js, MCP — status: available for hire" src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=18&duration=450&pause=120&color=00FF00&background=0D1117&center=false&vCenter=true&multiline=true&repeat=false&width=620&height=140&lines=%3E+AI+agents+%2F+LLM+apps+engineer;%3E+TypeScript+%2F+Next.js+%2F+MCP;%3E+status%3A+available+for+hire">

<p>
<a href="https://github.com/bcneal666"><img alt="Follow bcneal666 on GitHub" src="https://img.shields.io/github/followers/bcneal666?style=for-the-badge&label=FOLLOW&logo=github&logoColor=00FF00&labelColor=0D1117&color=0D1117"></a>
<a href="https://github.com/bcneal666/bcneal666/issues/new?template=contact.yml"><img alt="Hire me — open a project inquiry" src="https://img.shields.io/badge/HIRE_ME-0D1117?style=for-the-badge&logo=github&logoColor=00FF00&labelColor=0D1117"></a>
<a href="https://github.com/bcneal666?tab=repositories"><img alt="All repositories" src="https://img.shields.io/badge/ALL_REPOS-0D1117?style=for-the-badge&logo=github&logoColor=00FF00&labelColor=0D1117"></a>
<img alt="Profile views" src="https://komarev.com/ghpvc/?username=bcneal666&label=VIEWS&color=0d1117&style=for-the-badge">
</p>

<img alt="Matrix digital rain" src="https://raw.githubusercontent.com/bcneal666/bcneal666/main/matrix.svg" />

</div>

<img alt="whoami" src="https://raw.githubusercontent.com/bcneal666/bcneal666/main/assets/h-whoami.svg">

- 🤖 **AI agents / LLM apps engineer.** I build agent and LLM products end to end — the model plumbing and the web app in front of it.
- 🧰 **What I build:** LLM agents, MCP tools and chat-bot backends, with Next.js + TypeScript front-ends and Node/MongoDB back-ends.
- 🧠 **Currently working on** LINE AI bots, agent tooling and a Claude Code workflow (see below).
- ⛓️ **Web3 on the side:** Solidity contracts with Hardhat and mocha tests.
- 💼 **Available for freelance and contract work** — [open a project inquiry](https://github.com/bcneal666/bcneal666/issues/new?template=contact.yml).

<img alt="ls ~/selected-work" src="https://raw.githubusercontent.com/bcneal666/bcneal666/main/assets/h-selected-work.svg">

- **[.claude](https://github.com/bcneal666/.claude)** — My global Claude Code setup: custom skills, slash commands, hooks and a statusline. &nbsp;`Claude Code`&nbsp;`AI agents`&nbsp;`Hooks`&nbsp;`Skills`
- **[nvim](https://github.com/bcneal666/nvim)** — LazyVim-based Neovim config with blink.cmp, the Cyberdream theme and a full web-dev LSP stack, synced across Windows and a Linux VPS. &nbsp;`Neovim`&nbsp;`Lua`&nbsp;`LSP`

<img alt="cat stack.txt" src="https://raw.githubusercontent.com/bcneal666/bcneal666/main/assets/h-stack.svg">

<img alt="build — TypeScript, JavaScript, Python, Solidity, C#, Next.js, React, Tailwind CSS, shadcn/ui, Node.js, Hono, Express" src="https://github-readme-tech-stack.vercel.app/api/cards?title=build&lineCount=3&titleAlign=left&align=left&width=830&showBorder=true&borderRadius=6&fontFamily=Courier%20New&bg=%230D1117&border=%2300FF00&badge=%23161B22&titleColor=%2300FF00&line1=typescript,TypeScript,00ff00;javascript,JavaScript,00ff00;python,Python,00ff00;solidity,Solidity,00ff00;dotnet,C%2523,00ff00&line2=nextdotjs,Next.js,00ff00;react,React,00ff00;tailwindcss,Tailwind,00ff00;shadcnui,shadcn%2Fui,00ff00&line3=nodedotjs,Node.js,00ff00;hono,Hono,00ff00;express,Express,00ff00" />

<img alt="infra — MongoDB, MySQL, SQLite, Nginx, Vercel, Cloudflare, IPFS" src="https://github-readme-tech-stack.vercel.app/api/cards?title=infra&lineCount=2&titleAlign=left&align=left&width=830&showBorder=true&borderRadius=6&fontFamily=Courier%20New&bg=%230D1117&border=%2300FF00&badge=%23161B22&titleColor=%2300FF00&line1=mongodb,MongoDB,00ff00;mysql,MySQL,00ff00;sqlite,SQLite,00ff00&line2=nginx,Nginx,00ff00;vercel,Vercel,00ff00;cloudflare,Cloudflare,00ff00;ipfs,IPFS,00ff00" />

<img alt="./snake.sh" src="https://raw.githubusercontent.com/bcneal666/bcneal666/main/assets/h-snake.svg">

<!-- Regenerated daily by .github/workflows/snake.yml, published to the output branch. -->
<img alt="Snake game animation eating the bcneal666 contribution graph" src="https://raw.githubusercontent.com/bcneal666/bcneal666/output/snake.svg" />

<div align="center">

<img alt="connection closed — thanks for scrolling" src="https://raw.githubusercontent.com/bcneal666/bcneal666/main/assets/h-footer.svg">

</div>
