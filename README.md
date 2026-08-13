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

## 🏆 Premiação e Certificação Acadêmica

> 🥇 **1º LUGAR – MELHOR TRABALHO APRESENTADO (Apresentação Oral)**
> Este artigo e projeto foram avaliados por banca examinadora e **premiados como o melhor trabalho apresentado** na II Jornada de Pesquisa, Extensão e Internacionalização.

### 📋 Detalhes da Certificação
* **Trabalho Premiado:** VERITAS: Sistema Integrado de Controle de Acesso Biométrico com Inteligência Artificial
* **Categoria:** Apresentação Oral (Melhor Trabalho)
* **Evento:** II Jornada de Pesquisa, Extensão e Internacionalização
* **Instituição:** Centro Universitário Estácio de Belém
* **Período:** 17/06/2026 a 19/06/2026
* **Emissão:** Pró-reitoria de Pesquisa, Extensão e Internacionalização (Profª Natalle do Socorro da C. Freitas)
* 
📄 **[Clique aqui para visualizar o Certificado em PDF](./certificado.pdf)**

---

### 🔍 Validação e Autenticidade do Certificado
A autenticidade deste certificado pode ser verificada publicamente na plataforma Even3[cite: 2]:
* **Código de Autenticidade:** `20818247.07826094.8406373.8.08182470782609484063738`[cite: 2]
* **Link para Validação:** [Validar em Even3 Documentos](https://www.even3.com.br/documentos)[cite: 2]
---

## 👥 Autores
* Geovanni Silva Honorato
* Elrick Vinícius Pinheiro de Almeida Leite
* Joeni Abreu Franco
* Wallace Luiz Santos dos Santos
* Yasmin Vitória dos Santos da Silva
