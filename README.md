# ✨ Torn City - Monitor de Barras & Alarmes

Aplicação web leve, fofa e responsiva para monitorar as barras de **Energy**, **Nerve** e agora o **Drug Cooldown** do jogo [Torn City](https://www.torn.com/). 

O sistema utiliza a API v2 do Torn para calcular o tempo exato restante até os seus alvos personalizados, disparando **notificações no sistema operacional** acompanhadas de aviso sonoro assim que estiverem prontos!

---

## 🚀 Funcionalidades

- 🎯 **Alvos Personalizáveis:** Escolha exatamente quanta energia ou nerve você quer atingir antes de ser avisado (ou deixe vazio para calcular até o máximo).
- 💊 **Monitoramento de Drogas:** Rastreador inteligente de *Drug Cooldown* que avisa exatamente quando o tempo acabar (sem spam de notificações).
- ⏳ **Sincronização em Segundo Plano:** Continua rodando e sincronizando mesmo quando você está em outra aba, com intervalos customizáveis (30s, 1m, 2m, 5m).
- 🔔 **Notificações Visuais e Sonoras:** Alertas fofos com som personalizado e notificações de desktop compatíveis com Windows, Mac e Linux.
- 🎨 **Design Super Fofo:** Animações SVG dinâmicas no fundo que reagem perfeitamente ao tema claro e escuro.
- 🌙 **Light / Dark Mode:** Proteja seus olhos com a troca instantânea de tema!
- 🔒 **Segurança total:** A API Key é salva exclusivamente no `localStorage` do seu navegador e nunca é enviada para nenhum servidor externo.

---

## 🛠️ Como Usar

### 1. Hospedar ou Rodar Localmente
Acesse o link gerado se hospedado via **GitHub Pages**, ou rode um servidor local (ex: Live Server) para contornar bloqueios de notificação em navegadores.

### 2. Configurar sua API Key e Alvos
1. Pegue sua chave de API no jogo Torn (*Settings -> API Key*).
2. Cole na caixa **Torn API Key**.
3. Defina seus alvos de Energy e Nerve (Opcional).
4. Clique em **Save Settings**. Um *Toast* fofinho vai confirmar o salvamento!

### 3. Ativar Notificações
Clique no botão **🔔 Enable Browser Notifications**. Se a notificação de teste não aparecer, siga as instruções na caixinha de ajuda logo abaixo do botão para desbloquear os alertas no seu sistema (Windows/Mac/Linux).

---

## 🔒 Segurança e Privacidade

- Este projeto é **100% client-side** (executado totalmente no seu próprio navegador).
- O código-fonte é público.
- As suas chaves de API, preferências de tema e configurações ficam armazenadas apenas no seu computador (via localStorage) e você pode apagá-las a qualquer momento clicando em **Clear**.

---

## 💻 Tecnologias Utilizadas

- HTML5 / CSS3 Vanilla (com Variáveis CSS para Temas)
- JavaScript (ES6+)
- Fetch API (Torn API v2)
- Web Notifications API & Web Audio API