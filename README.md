# llm-telegram-demo

Два Telegram-бота с локальными LLM с Ollama:
* **bot_minimal.py** — переключение между 2 моделями.
* **bot_advanced.py** — история, контекст, vision, cut-thinking.

## Быстрый старт

# Установить ollama
* скачать с сайта ollama https://ollama.com/download
* загрузить модели используя cmd|terminal

```bash
ollama pull gemma3:4b
```
```bash
ollama pull qwen3:4b
```
* если у вас мощный ПК (Хотя бы vRam > 4 ГБ)

```bash
ollama pull gemma3:4b
```
```bash
ollama pull qwen3:4b
```

```bash
python -m venv venv
```
```bash
source venv/bin/activate
```
```bash
pip install -r requirements.txt
```
```bash
cp .env.example .env   # или переназовите в ".env" + впишите свой BOT_TOKEN
```
```bash
python bot_minimal.py
```
или
```bash
bot_advanced.py
```