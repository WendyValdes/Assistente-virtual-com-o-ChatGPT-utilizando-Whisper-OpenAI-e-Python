🎙️ Assistente de Voz com Python + Whisper + ChatGPT
📌 Descrição do Projeto

Este projeto demonstra a construção de um assistente conversacional por voz, utilizando Python no Google Colab. A solução permite:

Capturar áudio do usuário 🎤
Transcrever fala em texto 🧠
Processar a entrada com IA 💬
Retornar uma resposta em áudio 🔊
🚀 Tecnologias Utilizadas
Python
JavaScript (MediaStream API)
Whisper (OpenAI) – Speech-to-Text
OpenAI API (GPT-4) – Processamento de linguagem natural
gTTS (Google Text-to-Speech) – Text-to-Speech
Google Colab
⚙️ Como Funciona
1. 🎤 Gravação de Áudio
Utiliza JavaScript no navegador via Colab
Captura áudio do usuário por alguns segundos
Salva como arquivo .wav
2. 🧠 Transcrição com Whisper
O modelo Whisper converte o áudio em texto
Suporte para múltiplos idiomas (configurado para pt)
3. 💬 Integração com ChatGPT
Envia o texto transcrito para a API da OpenAI
O modelo gera uma resposta inteligente
4. 🔊 Síntese de Voz
A resposta do ChatGPT é convertida em áudio usando gTTS
O áudio é reproduzido automaticamente
📂 Estrutura do Fluxo
Usuário fala 🎤
   ↓
Áudio (.wav)
   ↓
Whisper (transcrição)
   ↓
Texto
   ↓
ChatGPT (resposta)
   ↓
Texto
   ↓
gTTS (voz)
   ↓
Resposta em áudio 🔊
🔑 Configuração da API

Para executar o projeto, é necessário configurar sua chave da OpenAI:

os.environ['OPENAI_API_KEY'] = 'SUA_API_KEY_AQUI'

📎 Gere sua chave em:
https://platform.openai.com/account/api-keys

▶️ Como Executar
Abra o projeto no Google Colab
Execute as células na ordem:
Instalação das bibliotecas
Gravação de áudio
Transcrição
Integração com ChatGPT
Geração de áudio
Permita acesso ao microfone quando solicitado
💡 Possíveis Melhorias
Interface web (Streamlit ou Flask)
Uso de modelos mais rápidos ou precisos
Integração com APIs externas (ex: clima, banco, suporte)
Implementação de memória conversacional
📊 Conclusão

Este projeto demonstra, de forma prática, a criação de um pipeline completo de IA conversacional por voz, integrando múltiplas tecnologias modernas. A solução é escalável e pode ser adaptada para diversos cenários, como:

Atendimento automatizado 🤖
Assistentes virtuais
Chatbots por voz
