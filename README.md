# 🛡️ VERITAS: Sistema Integrado de Controle de Acesso Biométrico com IA

> **Artigo Científico:** Publicado na *II Jornada de Pesquisa, Extensão e Internacionalização (2026)*.

O **VERITAS** é uma solução completa de controle de frequência biométrico com assistente inteligente embarcado, projetado para automatizar o registro de estagiários no Núcleo de Prática Jurídica (NPJ/CESUPA). O sistema foca em **baixo custo de hardware** e **privacidade total (Privacy by Design)**.

---

## 💡 Destaques do Projeto

* 💰 **Baixo Custo:** Hardware completo montado por menos de R$ 200,00.
* 🤖 **IA 100% Offline (RAG):** Execução local do modelo **Llama 3.2 1B** via `node-llama-cpp` e `transformers.js`, dispensando conexões externas e garantindo privacidade.
* 🔒 **Segurança & LGPD:** Armazenamento restrito a *templates* numéricos de minúcias e banco de dados SQLite com criptografia AES-256 (SQLCipher).
* 📊 **Validado em Produção:** Testado com 3.394 registros de 265 alunos entre março e maio de 2026.

---

## 🛠️ Arquitetura e Tecnologias

### Hardware Embarcado
* **Microcontrolador:** ESP8266 (NodeMCU v2)
* **Sensor Biométrico:** Óptico R307
* **Periféricos:** Relógio RTC DS3231 e Display LCD 20x4

### Backend e IA
* **Servidor:** Node.js + Express
* **Comunicação em Tempo Real:** Socket.IO
* **Banco de Dados:** SQLite3 (Criptografado com SQLCipher / AES-256)
* **Pipeline de IA:** Local RAG (Retrieval-Augmented Generation)

---

## 📄 Artigo Científico

O artigo completo descrevendo a metodologia, diagramas de circuito e análises de desempenho está disponível neste repositório:
👉 [Acessar artigo.pdf](./artigo.pdf)

---

## 👥 Autores
* Geovanni Silva Honorato
* Elrick Vinícius Pinheiro de Almeida Leite
* Joeni Abreu Franco
* Wallace Luiz Santos dos Santos
* Yasmin Vitória dos Santos da Silva
