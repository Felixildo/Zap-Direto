# 🚀 Zap Direto

![Screenshot do App](zap%20direto.png)

O **Zap Direto** é um Web App leve e eficiente desenvolvido para facilitar o início de conversas no WhatsApp sem a necessidade de salvar o número de telefone na agenda do celular ou do computador. Ideal para vendedores, suporte e uso pessoal.

---

## ✨ Funcionalidades

* **3 Modos de Abertura:** Escolha entre abrir no App do Celular, App do Computador (Desktop) ou diretamente no WhatsApp Web.
* **Máscara Inteligente:** Formatação automática para números do Brasil `(00) 00000-0000`.
* **Suporte Internacional:** Seletor de códigos de país (DDI) organizado por ordem alfabética.
* **Mensagem Personalizada:** Campo para predefinir o texto da conversa.
* **Histórico Local:** Armazena os últimos 10 contatos utilizados (salvo apenas no seu navegador).
* **PWA Ready:** Pode ser instalado como um aplicativo nativo no Android, iOS, Windows e Mac.

## 🛠️ Como usar

1.  Acesse o app: [https://felixildo.github.io/Zap-Direto/](https://felixildo.github.io/Zap-Direto/)
2.  Insira o número do telefone com o DDD.
3.  (Opcional) Digite uma mensagem.
4.  Escolha o destino (Celular, Desktop ou Web).
5.  Clique em **Iniciar Conversa**.

## 🚀 Como Hospedar

Este projeto é uma **Single Page Application (SPA)**, o que significa que você só precisa do arquivo `index.html`.

1.  Faça o upload do arquivo `index.html` para o seu provedor (GitHub Pages, Netlify ou Vercel).
2.  Acesse o link gerado.
3.  No celular, use a opção **"Adicionar à Tela de Início"** para usar como um App.

## 🔒 Privacidade

Sua privacidade é prioridade. Este Web App:
* Não possui banco de dados.
* Não envia seus dados para nenhum servidor.
* O histórico é salvo localmente no seu navegador através do `localStorage`.

## ⚖️ Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

## ⚠️ Avisos Importantes

### 1. Limitações
* **Dependência de Terceiros:** O funcionamento final depende exclusivamente das APIs oficiais do WhatsApp (Meta).
* **Armazenamento:** O histórico é local. Limpar os dados do navegador fará com que as informações recentes sejam perdidas.
* **Bloqueios:** O uso excessivo de mensagens para números desconhecidos pode ser interpretado como SPAM pelo WhatsApp.

### 2. Responsabilidade
* O usuário é o único responsável pelo conteúdo enviado e pelas consequências de suas interações via WhatsApp.

### 3. Garantia
* Software fornecido "no estado em que se encontra", sem garantias de funcionamento ininterrupto.

---
Desenvolvido por [Felixildo](https://github.com/Felixildo) para agilizar o seu dia a dia. ⚡
