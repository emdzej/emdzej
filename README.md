# Hey, I'm Michał 👋

I've been building software for over 20 years. At this point, I'm not sure if I chose this career or it chose me while I was distracted debugging something.

I like making things that actually work. Code, furniture, electronics, welded contraptions — if it solves a problem and doesn't catch fire, I'm happy. *Usually* it doesn't catch fire.

Based in Łódź, Poland 🇵🇱 — yes, that's pronounced "Woodge." No, I can't explain why.

## What I'm Currently Breaking

### Complete Solutions

#### Bimmerz Suite

| Project | What it does | Why it exists |
|---------|--------------|---------------|
| [**bimmerz-box**](https://github.com/emdzej/bimmerz-box) | Bimmerz Suite ina Box | Plug it in connect via phone or tablet and enjoy |
| [**ediabasx**](https://github.com/emdzej/ediabasx) | BMW diagnostic interface — TypeScript port 🚧 | The VM runs. Everything else is "coming soon." |
| [**ediabasx-embedded**](https://github.com/emdzej/ediabasx-embedded) | BMW diagnostic interface — TypeScript port 🚧 | The VM runs. Everything else is "coming soon." |
| [**inpax**](https://github.com/emdzej/inpax) | INPA scripting — cross-platform 🚧 | Not everyone likes Windows. Even in the garage. |
| [**ncsx**](https://github.com/emdzej/ncsx) | BMW NCS Expert in the browser | Factory coding tool ported to TypeScript — no installer, no Wine needed |
| [**nfsx**](https://github.com/emdzej/nfsx) | NFS / WinKFP + JMG Flasher + MS4x Flasher in one tool | Flash what you need on any platform you want |
| [**wdsx**](https://github.com/emdzej/wdsx) | BMW Wiring Diagram System — web port | The original Java applet stopped working. My car didn't stop needing repairs. |
| [**etkx**](https://github.com/emdzej/etkx) | BMW Electronic Parts Catalogue — reverse engineered | Because PDF parts lists are for quitters |
| [**tunex**](https://github.com/emdzej/tunex) | ECU firmware editor with TunerPro's XDF support in your browser | For a comlete flashing experience |
| [**xbusx**](https://github.com/emdzej/xbusx) | BMW I-Bus / K-Bus protocol + tools | Reference implementation for in-vehicle comms (E31–E87) |
| [**dashx**](https://github.com/emdzej/dashx) | BMW CAN Dashboard | What you really need is just your phone (and BimmerzBox) |
| [**tisx**](https://github.com/emdzej/tisx) | BMW TIS reimplementation | Workshop manuals without dusting off Windows XP |

#### Other Marques

| Project | What it does | Why it exists |
|---------|--------------|---------------|
| [**ddtx**](https://github.com/emdzej/ddtx) | Renault / Dacia / Nissan ECU diagnostics in the browser — [ddtx.emdzej.pl](https://ddtx.emdzej.pl) | A DDT4All port that reads a real vehicle over K-line. Turns out browser latency is noise next to an ECU. |
| [**dialogysx**](https://github.com/emdzej/dialogysx) | Renault / Dacia parts catalogue **and** repair documentation — [dialogysx.emdzej.pl](https://dialogysx.emdzej.pl) | Dialogys 7.5.6, reverse engineered. 576,034 index keys, 0 failures, no backend. |
| [**eperx**](https://github.com/emdzej/eperx) | Fiat, Lancia, Alfa Romeo, Abarth, Chrysler parts catalogue — [eperx.emdzej.pl](https://eperx.emdzej.pl) | ePER 8.3 without the Java installer. VIN in, exact factory build out. |
| [**masax**](https://github.com/emdzej/masax) | Mitsubishi After Sales parts catalogue — [masax.emdzej.pl](https://masax.emdzej.pl) | 9,495,097 records decoded exactly and all 17,977 drawings de-obfuscated. The discs still work; the application doesn't. |
| [**mitsudocs**](https://github.com/emdzej/mitsudocs) | Mitsubishi service manual viewer + AI-powered indexing | Local vision models doing OCR on scanned wiring diagrams |

### Tools

| Project | What it does | Why it exists |
|---------|--------------|---------------|
| [**swsrs**](https://github.com/emdzej/swsrs) | Self-hostable WebSocket relay for peers behind NAT/firewalls + OIDC-protected admin plane | Because "just open a port" stops being funny behind CGNAT |
| [**npvm**](https://github.com/emdzej/npvm) | Monorepo versioning CLI | Semantic versioning across 47 packages shouldn't require a PhD |
| [**stm**](https://github.com/emdzej/stm) | Serial Terminal & Monitor on the web | My way, anywhere |
| [**bass**](https://github.com/emdzej/bass) | Self hosted service + library for synchronising backendless web apps | Not every app needs backend, and I like switching devices |
| [**avrdudeui**](https://github.com/emdzej/avrdudeui) | UI for avrdude CLI | Because AVRDUDESS was not updated in a while |
| [**airlock**](https://github.com/emdzej/airlock) | Raspberry Pi network card-reader appliance — SMB, web UI, and a macOS menubar companion | Someone else's thumb drive plugs into a $50 Pi mounted `noexec`, not into the machine you actually work on |
| [**spinup**](https://github.com/emdzej/spinup) | Cloud-functions platform for Spin WebAssembly components on Kubernetes — [spinup.emdzej.pl](https://spinup.emdzej.pl) | Write Go / Rust / TS in the browser, hit Build & Deploy, get an HTTP endpoint. Lambda without the vendor. |

### AI & LM

| Project | What it does | Why it exists |
|---------|--------------|---------------|
| [**microagent**](https://github.com/emdzej/microagent) | Minimal AI agent with tools + MCP in ~1500 LOC | Reference implementation for "how do agents actually work?" |
| [**ragclaw**](https://github.com/emdzej/ragclaw) | Local-first RAG engine with SQLite vector search | Because sometimes you want AI to know things without sending your secrets to the cloud |

### Libraries, Extensions & Plugins

| Project | What it does | Why it exists |
|---------|--------------|---------------|
| [**keycloak-api-keys**](https://github.com/emdzej/keycloak-api-keys) | API key management for Keycloak | OAuth2 is great until your IoT toaster needs to authenticate |
| [**config**](https://github.com/emdzej/config) | Runtime config service for SPAs (build once, run everywhere) | Env/secret‑driven config without rebuilds |
| [**itw-decoder**](https://github.com/emdzej/itw-decoder) | BMW ITW image format decoder | Because things should be accessible and live forever |
| [**j2534**](https://github.com/emdzej/j2534) | TypeScript SAE J2534 PassThru API (Node + WebUSB) 🚧 | Cross-platform replacement for Windows-only DLLs |
| [**csfs**](https://github.com/emdzej/csfs) | One read API over anything a browser can reach: static HTTP, a picked folder, OPFS — or a zip inside any of them — [csfs.emdzej.pl](https://csfs.emdzej.pl) | Reading *part* of a remote file is what makes 15 GB of catalogue data usable at all |
| [**elmo**](https://github.com/emdzej/elmo) | Schematics as code — a text DSL that renders circuits as SVG — [elmo.emdzej.pl](https://elmo.emdzej.pl) | Mermaid and PlantUML for electronics. ~45 symbols, markdown-it / remark / CLI / browser. |

## Fun Facts

- 🔧 I fix things. Cars, appliances, furniture, pride after failed deployments.
- 🛠️ I build things in the physical world too. Wood, metal, electronics — whatever gets the job done.

## Right to Repair

The [Right to Repair](https://repair.eu) movement advocates for consumers' ability to fix the products they own — from electronics to vehicles — without being locked out by manufacturers through proprietary tools, paywalled documentation, or artificial restrictions.

**I build these tools because I believe repair is a fundamental right, not a privilege.**

Too often, service manuals, diagnostic software, and technical documentation are kept behind closed doors — unavailable to individuals even when they're willing to pay. This wasn't always the case. Products once shipped with schematics and repair guides as standard. The increasing complexity of modern technology doesn't change the fact that capable people exist who can — and should be allowed to — use that information.

These projects exist to preserve access to technical knowledge and ensure that owners aren't left at the mercy of vendors who may discontinue support, charge prohibitive fees, or simply refuse service.

## Get In Touch

- 🌐 [emdzej.pl](https://emdzej.pl)
- 📧 michal@jaskolski.pro

## Support

If you find my work useful, consider [buying me a coffee](https://buymeacoffee.com/emdzej) ☕ or [sponsoring on GitHub](https://github.com/sponsors/emdzej) or if it's your thing: via PayPal

[![Donate with PayPal](https://www.paypalobjects.com/en_US/PL/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?business=TDBR3A97PLQRQ&no_recurring=0&item_name=%28emdzej%29&currency_code=PLN)


---

*"It works on my machine"* — certified since 2003
