<div align="center">

# DoctorM&Ai IT/AI Laboratory

**Набор скриптов, оберток для LLM и инфраструктурных утилит.**

[![Website](https://img.shields.io/badge/🌐_Сайт-shtab--ai.ru-00D4AA?style=flat-square)](https://shtab-ai.ru)
[![Dashboard](https://img.shields.io/badge/📊_Дашборд-myrmexcontrol.shtab--ai.ru-00D4AA?style=flat-square)](https://myrmexcontrol.shtab-ai.ru)

[🇬🇧 English](README.md) · [🇷🇺 Русский](#)

</div>

---

## 🏛️ Проверка реальности

Это никакая не "колония" и вы не выращиваете "живой организм". Это просто набор из 8 автоматизированных LLM-агентов (промпты + скрипты) и пара десятков репозиториев для рутинных задач. Никакой магии, только API-вызовы и bash-скрипты.

## 🤖 Скрипты (бывшие "Агенты")

Хватит ролевых игр с именами животных. Вот что они делают на самом деле:
- **Мониторинг и операции**: Проверка статусов, управление VPN, маршрутизация данных.
- **Автоматизация**: Боты, выполнение скриптов, интеграция задач.
- **Инфраструктура**: Настройка железа и CI/CD пайплайны.
- **Разработка**: Генерация кода и скрипты деплоя.
- **QA**: Аудит кода и промпты для архитектурного ревью.
- **Разведка**: Сбор данных из сети, парсинг.

Все они общаются через общий JSON-файл (`myrmex.json`) и панель управления (`myrmex-control`). На этом "эволюция" заканчивается.

## 🚀 Базовая инфраструктура

- [myrmex-control](https://github.com/thedoctormes-hue/myrmex-control) — Реальная панель управления. Node.js + React.
- [lab-vault](https://github.com/thedoctormes-hue/lab-vault) — Менеджер секретов (Go).
- [api-hub](https://github.com/thedoctormes-hue/api-hub) — API-прокси и маршрутизация (Python).
- [lab-monitoring](https://github.com/thedoctormes-hue/lab-monitoring) — Мониторинг статусов (Python).
- [lab-memory](https://github.com/thedoctormes-hue/lab-memory) — RAG и семантический поиск по артефактам (ONNX + FAISS).
- [mcp-tools](https://github.com/thedoctormes-hue/mcp-tools) — MCP серверы для связности агентов.

## 📊 Проекты

Свалка из активных утилит, поставленных на паузу идей и мертвых репозиториев. Из живого:
- **Активные**: [snablab](https://github.com/thedoctormes-hue/snablab), [autoexpert](https://github.com/thedoctormes-hue/autoexpert), [zprr-tracker](https://github.com/thedoctormes-hue/zprr-tracker), [stenographer](https://github.com/thedoctormes-hue/stenographer), [consilium](https://github.com/thedoctormes-hue/consilium), [polyscop](https://github.com/thedoctormes-hue/polyscop).
- **Кладбище**: Ищите во вкладке repositories, если хотите копаться в заброшенном коде MVP и замороженных ботах.

## 📡 Ссылки
- Сайт: [shtab-ai.ru](https://shtab-ai.ru)
- GitHub: [thedoctormes-hue](https://github.com/thedoctormes-hue)
- Telegram: [@DoctorMES](https://t.me/DoctorMES)
