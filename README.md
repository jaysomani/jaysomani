![1666024203535](https://github.com/jaysomani/jaysomani/assets/69755312/fb417b4f-f421-423b-889a-c5ee6fbc8422)

<h1 align="center">Hi 👋, I'm Jayesh Somani</h1>
<h3 align="center">Software Engineer & Open Source Contributor from India</h3>
<img align="right" alt="Coding" width="400" src="https://www.lambdatest.com/resources/images/news24.gif">

<p align="left">
  <a href="https://twitter.com/jayesh_s_s" target="blank">
    <img src="https://img.shields.io/twitter/follow/jayesh_s_s?logo=twitter&style=for-the-badge" alt="jayesh_s_s" />
  </a>
</p>

- 🔭 Currently contributing to open source infrastructure — auth systems, VCS adapters, SSR runtimes, and developer tooling
- 🌱 Deep-diving into **distributed systems, security research, and devtools infrastructure**
- 🔐 Found and fixed a production MFA security bypass in a major open source BaaS platform
- 💬 Ask me about **TypeScript, Node.js, PHP, Go, Docker, Git internals, REST API design**
- 📫 Reach me at **jaysomani2016@gmail.com**

---

### 🛠️ Open Source Contributions

#### VCS Infrastructure
| Work | What I did |
|------|-----------|
| **GitLab, Gitea, Forgejo, Bitbucket adapters** | Built full VCS adapter layer — OAuth2, webhooks (HMAC-SHA256), repository ops, pull requests, normalised output across all providers |
| **Unified test architecture** | Migrated per-adapter test duplication into a single base class running across all providers — O(n) → O(1) test maintenance |
| **Adapter normalisation** | Fixed cross-provider inconsistencies so all adapters return uniform `{items, total}` structure |

#### Runtime & SSR
| Work | What I did |
|------|-----------|
| **Jaspr SSR runtime** | Implemented full SSR runtime for Jaspr (Dart/Flutter web framework) in open-runtimes — reverse-engineered undocumented contract from reference implementations, built health/auth/timings endpoints, verified end-to-end in Docker |

#### Auth & Security
| Work | What I did |
|------|-----------|
| **JWT session null bug** | Found production MFA security bypass — JWT-authenticated requests silently skipped factor-count enforcement. Traced through 4 files, proved with failing E2E tests, fix merged |
| **deleteSessions current param** | Added `current` bool param to bulk session deletion — JWT-aware session identification, fixed X-Fallback-Cookies regression |
| **Session duration param** | Added per-login `duration` param to email/password sessions with validation against project max |
| **listX total param** | Added `total` param to 24 list endpoints for consistent API surface |

#### Developer Tooling (Go)
| Work | What I did |
|------|-----------|
| **Windows PE metadata fix** | Fixed `entire.exe` reporting `0.0.0.0` in Explorer/Get-Command — added goversioninfo build step with CI regression test |
| **HTTP redirect security** | Fixed POST redirects being silently followed (diverging from vanilla git behavior) — `via[0].Method` fix covering all 301/302/303/307/308 status codes |
| **Warning text accuracy** | Fixed misleading warning that blamed a flag users never passed |

---

<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://twitter.com/jayesh_s_s" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="jayesh_s_s" height="30" width="40" /></a>
  <a href="https://linkedin.com/in/jayesh-somani" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="jayesh somani" height="30" width="40" /></a>
  <a href="https://instagram.com/somani.jayesh" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="somani.jayesh" height="30" width="40" /></a>
</p>

---

<h3 align="left">Languages and Tools:</h3>
<p align="left">
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/></a>
  <a href="https://nodejs.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/></a>
  <a href="https://golang.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/></a>
  <a href="https://www.php.net" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/></a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a>
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/></a>
  <a href="https://nextjs.org/" target="_blank" rel="noreferrer"><img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/></a>
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/></a>
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/></a>
  <a href="https://cloud.google.com" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/></a>
</p>

---

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=jaysomani&show_icons=true&locale=en&layout=compact" alt="jaysomani" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=jaysomani&show_icons=true&locale=en" alt="jaysomani" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=jaysomani&" alt="jaysomani" /></p>
