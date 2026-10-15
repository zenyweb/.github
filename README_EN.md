<div align="right"><b>English</b> | <a href="README.md">Русский</a></div>

<div align="center">
  <a href="https://zenyweb.com">
    <img src="https://raw.githubusercontent.com/zenyweb/.github/main/profile/hero.jpg" alt="zeny: Personal AI computer in your browser and Telegram" width="100%" />
  </a>
  <br />
  <p>
    <a href="https://zenyweb.com"><b>zenyweb.com</b></a> ·
    <a href="https://t.me/zenyweb"><b>Telegram @zenyweb</b></a> ·
    <a href="https://t.me/zeny_ai_bot"><b>@zeny_ai_bot</b></a>
  </p>
</div>

---

## zeny: Personal AI Computer in Your Browser and Telegram

**zeny** ([zenyweb.com](https://zenyweb.com)) gives every user a dedicated cloud computer powered by autonomous AI agents, shared long-term memory, and seamless control from any browser or Telegram Mini App.

### Platform Modules

| Module | Purpose |
| :--- | :--- |
| **`czeef`** | **Personal computer in your browser.** A dedicated, isolated Linux machine with a full workspace, terminal, browser, and a team of AI agents. Launches in one click from phone, tablet, or laptop, keeps running in the cloud when you close the tab, and accepts tasks directly from your Telegram thread. |
| **`focus`** | **Tasks, routines, and calm daily digests.** Captures voice and text tasks in Telegram and the Mini App, manages reminders without pressure or guilt, and hands off complex engineering or research tasks to agents in `czeef`. |
| **`cntrl`** | **Protected assistant for personal Telegram messages.** Summarizes unread messages across people, groups, and channels, searches conversations by meaning, and places reply drafts directly into the Telegram input field. Only the human sends messages. |
| **`dreamy`** | **Visual studio for illustrations, scenes, and video.** Generates consistent visual assets from a short prompt and reference image while keeping your project style intact. |

### Engineering Principles & Security

* **Hardware & network isolation.** Every user workspace runs on its own virtual machine inside an isolated WireGuard network contour.
* **Protocol allowlist & human-in-the-loop.** The `cntrl` broker is strictly limited at the protocol layer to read operations and `SaveDraftRequest`. Every irreversible action on memory, tasks, or sessions requires explicit human confirmation.
* **Credential isolation.** User API keys (`BYOK`) and personal Claude Pro/Max subscription tokens are encrypted at the gateway layer and are never exposed inside the user container.
* **Transparent billing.** Plans are measured in clear hours, weeks, or months of work with no hidden auto-renewals and no card required to start a free test drive.

### Official Links & Legal Entity

* **Website & Cabinet:** [https://zenyweb.com](https://zenyweb.com)
* **Official Telegram Channel:** [@zenyweb](https://t.me/zenyweb)
* **Telegram Bot & Mini App:** [@zeny_ai_bot](https://t.me/zeny_ai_bot)
* **Legal Documents:** [Terms of Service](https://zenyweb.com/offer) · [Privacy Policy](https://zenyweb.com/privacy)
* **Legal Entity:** **Zeny LLP** (`ТОО «Zeny»`), BIN `261040015657`, Almaty, Republic of Kazakhstan (`A10A5T2`).
