# 🚀 Zap Direto - Multi-Acesso

O **Zap Direto** é um Web App leve e eficiente desenvolvido para facilitar o início de conversas no WhatsApp sem a necessidade de salvar o número de telefone na agenda do celular ou do computador. Ideal para vendedores, suporte e uso pessoal.

## ✨ Funcionalidades

- **3 Modos de Abertura:** Escolha entre abrir no App do Celular, App do Computador (Desktop) ou diretamente no WhatsApp Web.
- **Máscara Inteligente:** Formatação automática para números do Brasil `(00) 00000-0000`.
- **Suporte Internacional:** Seletor de códigos de país (DDI).
- **Mensagem Personalizada:** Campo para predefinir o texto da conversa.
- **Histórico Local:** Armazena os últimos 10 contatos utilizados (salvo apenas no seu navegador).
- **Auto-Reset:** Limpa os campos automaticamente após o envio, pronto para a próxima mensagem.
- **PWA Ready:** Pode ser instalado como um aplicativo nativo no Android, iOS, Windows e Mac.

## 🛠️ Como usar

1. Insira o número do telefone com o DDD.
2. (Opcional) Digite uma mensagem.
3. Escolha o destino (Celular, Desktop ou Web).
4. Clique em **Iniciar Conversa**.

## 🚀 Como Hospedar

Este projeto é uma **Single Page Application (SPA)**, o que significa que você só precisa do arquivo `index.html`.

1. Faça o upload do arquivo `index.html` para o seu provedor (GitHub Pages, Netlify ou Vercel).
2. Acesse o link gerado.
3. No celular, use a opção **"Adicionar à Tela de Início"** para usar como um App.

## 🔒 Privacidade

Sua privacidade é prioridade. Este Web App:
- Não possui banco de dados.
- Não envia seus dados para nenhum servidor.
- O histórico é salvo localmente no seu navegador através do `localStorage`.

## ⚖️ Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

## ⚠️ Avisos Importantes

### 1. Limitações
* **Dependência de Terceiros:** Este app funciona como um facilitador de links. O funcionamento final depende exclusivamente da disponibilidade e das APIs oficiais do WhatsApp (Meta).
* **Armazenamento:** O histórico é local. Limpar os dados do navegador ou trocar de dispositivo fará com que as informações recentes sejam perdidas, pois não utilizamos banco de dados em nuvem.
* **Bloqueios:** O uso excessivo de mensagens para números desconhecidos pode ser interpretado pelo WhatsApp como SPAM. Utilize a ferramenta com responsabilidade.

### 2. Responsabilidade
* **Uso de Dados:** O desenvolvedor não tem acesso aos números ou mensagens digitados. Todos os dados permanecem no dispositivo do usuário.
* **Ações do Usuário:** O usuário é o único responsável pelo conteúdo enviado e pelas consequências de suas interações via WhatsApp.

### 3. Garantia
* **"Como está":** Este software é fornecido "no estado em que se encontra", sem garantias de qualquer tipo, expressas ou implícitas, incluindo garantias de funcionamento ininterrupto.
* **Suporte:** Por ser uma ferramenta gratuita e de código aberto, não há garantia de suporte técnico imediato ou atualizações vitalícias.

---
Desenvolvido para agilizar o seu dia a dia. ⚡
