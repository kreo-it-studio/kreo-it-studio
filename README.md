# KREO Studio

Продуктовая IT-студия. Делаем собственные продукты и проекты под заказ: мобильные приложения, веб-платформы, платёжные и VPN-сервисы, AI-инструменты.

## Продукты

| Продукт | Что это | Стек | Статус |
|---|---|---|---|
| **Wrab** | VPN-сервис: control-plane, сайт, админка, биллинг | Go, Next.js, PostgreSQL | active |
| **Wrabbit Proxy** | VPN/прокси-клиент для iOS и Mac на xray-core | Swift, SwiftUI | active |
| **Paycryp** | Платёжный терминал для заведений: СБП и криптовалюта | NestJS, React, PWA | active |
| **Foodly** | iOS-дневник питания с распознаванием еды по фото | SwiftUI, Express, PostgreSQL | active |
| **Velorra** | AI-агенты для телефонии: обзвон, перезвоны, CRM | Go, Next.js, Python, LiveKit | active |
| **Clipfarm** | Конвейер коротких видео: нарезка, субтитры, постинг | Python, FastAPI, ffmpeg | active |
| **Selfler** | Рабочее пространство команды: задачи, доски, CRM, ИИ | React, Node.js, MySQL | mvp |
| **Stiker** | AI-inbox для iOS/macOS: контент в модульные заметки | SwiftUI, Supabase | mvp |
| **Cubion** | Игровая платформа: 3D-ферма и мини-игры для Web, Telegram, iOS | Next.js, Three.js, Go | active |
| **Platforma** | Закрытое верифицированное сообщество предпринимателей | Next.js, Fastify, Prisma | paused |
| **Win-Win** | B2B-маркетплейс стройматериалов с кешбеком | React, Express, MySQL | paused |

## Инфраструктура

- **kreo-site** — сайт студии на Next.js с WebGL-сценой.
- **kreo-monitoring** — воркер проверок доступности, TLS и бэкапов с алертами в Telegram.
- **kreo-starter-kit** — шаблон нового проекта студии.

## Соглашения

- Репозитории именуются в `kebab-case`: `<продукт>` или `<продукт>-<часть>` (`wrab-vpn`, `wrabbit-ios`, `velorra-landing`).
- Устаревшие версии получают суффикс `-legacy` и архивируются.
- Topics: продукт, стек, платформа и статус (`status-active`, `status-mvp`, `status-paused`, `status-legacy`).
- Ветка `main` защищена от force-push и удаления.
