# ARCHITECTURE

## Главная цель

crypto_bot — облачная мульти-кошельковая платформа для полуавтоматической и автоматической торговли.

---

# Слои системы

## UI Layer

Flutter + Riverpod

Экран:

- Dashboard
- Wallets
- Trading
- Statistics
- Backtesting
- Settings

---

## Domain Layer

Модели:

- WalletProfileModel
- OrderModel
- PositionModel

Движки:

- BuyEngine
- SellEngine
- StopLossEngine
- TakeProfitEngine
- PartialCloseEngine
- PositionManager
- PaperOrderEngine

---

## Data Layer

Repository:

- OrderRepository
- WalletRepository
- PositionRepository

API:

- Binance REST API
- WebSocket API

---

## AI Layer

ChatGPT
Архитектор.

Gemini Flash
Диспетчер.

DeepSeek
Разработка.

Qwen
Тестирование.

---

## Cloud Layer

GitHub

Firebase Studio

Android Studio Cloud

Google Drive

---

## Основной принцип

Марис
↓

ChatGPT

↓

Gemini Flash

↓

AI Team

↓

GitHub

↓

Cloud Workspace
