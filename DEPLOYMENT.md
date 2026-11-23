
# 🚀 RAG Fishing Assistant - Deployment Guide

Этот документ описывает пошаговый процесс развертывания RAG-ассистента на чистом Ubuntu 24.04 VPS из репозитория GitHub.

## 📋 Предварительные требования
- VPS с Ubuntu 24.04 (минимум 2 CPU, 4GB RAM, 20GB SSD).
- Доменное имя, делегированное на Cloudflare (бесплатный тариф).
- Установленные `git`, `docker`, `docker-compose`.

## 🛠 Шаг 1: Клонирование и настройка окружения
```bash
git clone https://github.com/ВАШ_НИК/rag-fishing-assistant.git
cd rag-fishing-assistant
cp .env.example .env
nano .env  # Заполните реальные значения (пароли, домен)#
