<div align="center">
  <a href="https://zenyweb.com">
    <img src="https://raw.githubusercontent.com/zenyweb/.github/main/profile/hero.jpg" alt="zeny: Личный ИИ-компьютер в браузере и Telegram" width="100%" />
  </a>
  <br />
  <p>
    <a href="https://zenyweb.com"><b>zenyweb.com</b></a> ·
    <a href="https://t.me/zenyweb"><b>Telegram @zenyweb</b></a> ·
    <a href="https://t.me/zeny_ai_bot"><b>@zeny_ai_bot</b></a> ·
    <a href="#english"><b>English below</b></a>
  </p>
</div>

---

## zeny: личный ИИ-компьютер в браузере и Telegram

**zeny** ([zenyweb.com](https://zenyweb.com)) предоставляет каждому пользователю выделенный облачный компьютер с автономными ИИ-агентами, единой долговременной памятью и управлением через браузер и Telegram Mini App.

### Модули платформы

| Модуль | Назначение |
| :--- | :--- |
| **`czeef`** | **Личный компьютер в браузере.** Полноценная изолированная машина Linux с рабочей средой, терминалом, браузером и командой ИИ-агентов. Запускается в один клик с телефона, планшета или ноутбука, продолжает работу в облаке при закрытой вкладке и принимает задачи прямо из ветки в Telegram. |
| **`focus`** | **Задачи, дела и бережные сводки дня.** Принимает поручения голосом и текстом в Telegram и Mini App, ведёт расписание и напоминания без давления и чувства вины, а сложные рабочие задачи передаёт агентам в `czeef`. |
| **`cntrl`** | **Защищённый помощник по личной переписке в Telegram.** Делает сводку непрочитанного по людям, группам и каналам, ищет детали в диалогах по смыслу и готовит черновики ответов прямо в поле ввода чата. Сообщения отправляет только сам человек. |
| **`dreamy`** | **Студия генерации иллюстраций, сцен и видео.** Создаёт визуальные материалы из короткой фразы и образца с сохранением единого стиля проекта. |

### Инженерные принципы и безопасность

* **Аппаратная и сетевая изоляция.** Каждому пользователю выделяется отдельная виртуальная машина в изолированном сетевом контуре WireGuard.
* **Белый список протокола и подтверждение действий.** Брокер `cntrl` физически ограничен на уровне протокола только чтением и сохранением черновика (`SaveDraftRequest`). Любые необратимые операции с памятью, задачами или сессиями требуют явного подтверждения человека.
* **Защита ключей и подписок.** Ключи API (`BYOK`) и токены личной подписки Claude Pro/Max хранятся в зашифрованном контуре шлюза и недоступны коду внутри пользовательского контейнера.
* **Прозрачная модель работы.** Тарифы считаются в часах, неделях и месяцах реальной работы без скрытых автосписаний и без привязки банковской карты на старте (доступен бесплатный тест-драйв).

### Официальные ресурсы и реквизиты

* **Сайт и личный кабинет:** [https://zenyweb.com](https://zenyweb.com)
* **Официальный канал в Telegram:** [@zenyweb](https://t.me/zenyweb)
* **Бот и Telegram Mini App:** [@zeny_ai_bot](https://t.me/zeny_ai_bot)
* **Правовые документы:** [Пользовательское соглашение (оферта)](https://zenyweb.com/offer) · [Политика конфиденциальности](https://zenyweb.com/privacy)
* **Юридическое лицо:** Товарищество с ограниченной ответственностью «Zeny» (**ТОО «Zeny»**), БИН `261040015657`, Республика Казахстан, г. Алматы, почтовый индекс `A10A5T2`.

---

<a id="english"></a>

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
