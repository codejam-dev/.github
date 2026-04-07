<div align="center">

# CodeJam

### Write code. Run it instantly. Soon, do it together.

A developer playground that actually works — on desktop, on mobile, on the fly.

**[Try it live](https://codejam.shubham-dev.me)** &nbsp;&middot;&nbsp; [Frontend repo](https://github.com/codejam-dev/codejam-frontend) &nbsp;&middot;&nbsp; [Backend repo](https://github.com/codejam-dev/codejam-backend)

</div>

<br/>

<p align="center">
  <img src="https://raw.githubusercontent.com/codejam-dev/.github/main/assets/hero.png" alt="CodeJam — Code. Execute. Collaborate." width="720" />
</p>

<br/>

## The playground

Pick a language. Write code. Hit Run. Output streams back from a **Docker-sandboxed container** — your code never touches the host.

<p align="center">
  <img src="https://raw.githubusercontent.com/codejam-dev/.github/main/assets/playground-editor.png" alt="CodeJam playground — editor view" width="720" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/codejam-dev/.github/main/assets/playground-output.png" alt="CodeJam playground — execution output with runtime metrics" width="720" />
</p>

**7 languages** — JavaScript, Python, Java, C, C++, Go, Rust  
**Monaco editor** — the same engine that powers VS Code  
**Execution metrics** — runtime, memory, exit code for every run  
**Run history** — track, review, and restore past executions  
**Share via URL** — encode code + language in a link, send it to anyone  
**Works on mobile** — not a compromise, a real experience

<br/>

## What's live today

| Feature | Status |
|---------|--------|
| Multi-language Docker-sandboxed execution | **Shipped** |
| Monaco editor with themes, autocomplete, settings | **Shipped** |
| Auth — email/password, OTP, Google OAuth (PKCE) | **Shipped** |
| Run history with restore | **Shipped** |
| Dashboard with stats | **Shipped** |
| Share code via URL | **Shipped** |
| Mobile-responsive playground | **Shipped** |
| Real-time collaboration (rooms, live cursors) | Coming next |
| Chat, voice, video calls | Planned |
| Competitions and leaderboards | Planned |

<br/>

## Tech stack

```
Frontend    Next.js 15  ·  React 19  ·  TypeScript  ·  Tailwind  ·  Framer Motion  ·  Monaco Editor
Backend     Java 21  ·  Spring Boot 3.4  ·  PostgreSQL  ·  Redis  ·  Docker
Auth        JWT (access + refresh)  ·  OAuth2 (Google)  ·  OTP verification
Fonts       JetBrains Mono (code)  ·  Geist Sans (UI)
```

<br/>

## The vision

CodeJam started as a simple idea: what if students could **code together** the way they study together?

Not just solve problems solo on LeetCode — but pair-program with a friend, practice algorithms together, compete head-to-head. A place where you can open your phone, write code, and run it instantly. And eventually, a platform where interviewers can host live coding sessions with built-in voice and video.

We're not there yet. The playground is live, auth works, execution is solid. Collaboration is next. The rest is the dream.

<br/>

---

<div align="center">

Built by [Shubham Mishra](https://github.com/TonyStark0801)

</div>
