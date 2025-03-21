import requests
import random
import schedule
import time

# Configurações do Telegram
TOKEN = "7474353137:AAF3rjthUfCcMoMDWSWiAzdk0LaF3N2zD2g"
CHAT_ID = "-1002292813856"
API_URL = import requests
import random
import schedule
import time


# Configurações do Telegram
TOKEN = "7474353137:AAF3rjthUfCcMoMDWSWiAzdk0LaF3N2zD2g"
CHAT_ID = "-1002292813856"
API_URL = FM83X37CADTE53NN f"https://api.telegram.org/bot{TOKEN}/sendMessage"

#   (análise de mercado real)
def gerar_sinal():
    sinal = random.choice(["CALL 🟢", "PUT 🔴"])  # Simula uma decisão de compra/venda
    par_moeda = random.choice(["EUR/USD", "GBP/USD", "USD/JPY", "AUD/CAD"])  # Simula pares de moedas
    
    mensagem = f"📊 *Novo Sinal Forex*\n\n" \
               f"📌 *Par*: {par_moeda}\n" \
               f"⏳ *Tempo*: M5\n" \
               f"📈 *Sinal*: {sinal}\n\n" \
               f"⚠️ *Gerado automaticamente*"

    enviar_mensagem(mensagem)

# Função para enviar mensagem ao Telegram
def enviar_mensagem(mensagem):
    payload = {
        "chat_id": CHAT_ID,
        "text": mensagem,
        "parse_mode": "Markdown",
    }
    requests.post(API_URL, json=payload)

# Agendar envio a cada 5 minutos
schedule.every(5).minutes.do(gerar_sinal)

# Loop principal
if __name__ == "__main__":
    print("Bot de sinais Forex iniciado...")
    while True:
        schedule.run_pending()
        time.sleep(1) f"https://api.telegram.org/bot{TOKEN}/sendMessage"

# Função para gerar sinais aleatórios (substitua isso por sua análise de mercado real)
def gerar_sinal():
    sinal = random.choice(["CALL 🟢", "PUT 🔴"])  # Simula uma decisão de compra/venda
    par_moeda = random.choice(["EUR/USD", "GBP/USD", "USD/JPY", "AUD/CAD"])  # Simula pares de moedas
    
    mensagem = f"📊 *Novo Sinal Forex*\n\n" \
               f"📌 *Par*: {par_moeda}\n" \
               f"⏳ *Tempo*: M5\n" \
               f"📈 *Sinal*: {sinal}\n\n" \
               f"⚠️ *Gerado automaticamente*"

    enviar_mensagem(mensagem)

# Função para enviar mensagem ao Telegram
def enviar_mensagem(mensagem):
    payload = {
        "chat_id": CHAT_ID,
        "text": mensagem,
        "parse_mode": "Markdown",
    }
    requests.post(API_URL, json=payload)

# Agendar envio a cada 5 minutos
schedule.every(5).minutes.do(gerar_sinal)

# Loop principal
if __name__ == "__main__":
    print("Bot de sinais Forex iniciado...")
    while True:
        schedule.run_pending()
        time.sleep(1) f"https://api.telegram.org/bot{TOKEN}/sendMessage"

# Função para gerar sinais aleatórios (substitua isso por sua análise de mercado real)
def gerar_sinal():
    sinal = random.choice(["CALL 🟢", "PUT 🔴"])  # Simula uma decisão de compra/venda
    par_moeda = random.choice(["EUR/USD", "GBP/USD", "USD/JPY", "AUD/CAD"])  # Simula pares de moedas
    
    mensagem = f"📊 *Novo Sinal Forex*\n\n" \
               f"📌 *Par*: {par_moeda}\n" \
               f"⏳ *Tempo*: M5\n" \
               f"📈 *Sinal*: {sinal}\n\n" \
               f"⚠️ *Gerado automaticamente*"

    enviar_mensagem(mensagem)

# Função para enviar mensagem ao Telegram
def enviar_mensagem(mensagem):
    payload = {
        "chat_id": CHAT_ID,
        "text": mensagem,
        "parse_mode": "Markdown",
    }
    requests.post(API_URL, json=payload)

# Agendar envio a cada 5 minutos
schedule.every(5).minutes.do(gerar_sinal)

# Loop principal
if __name__ == "__main__":
    print("Bot de sinais Forex iniciado...")
    while True:
        schedule.run_pending()
        time.sleep(1)
