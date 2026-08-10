# ⚡ Torn City - Monitor de Barras & Alarmes

Aplicação web leve e responsiva para monitorar as barras de **Energy** e **Nerve** do jogo [Torn City](https://www.torn.com/). 

O sistema utiliza a API v2 do Torn para calcular o tempo exato restante até a recarga total e dispara notificações no navegador acompanhadas de aviso sonoro assim que as barras atingem 100%.

---

## 🚀 Funcionalidades

- ⏳ **Contagem regressiva em tempo real** para Energy e Nerve sem necessidade de requisições constantes (*polling*).
- 🔔 **Notificações do Navegador** quando a recarga é concluída (funciona com a aba em segundo plano).
- 🔊 **Alarme sonoro** integrado para alerta imediato.
- 🔒 **Segurança total**: A API Key é salva exclusivamente no `localStorage` do seu navegador e nunca é enviada para nenhum servidor externo.

---

## 🛠️ Como Usar

### 1. Acessar a aplicação
Acesse o link gerado pelo **GitHub Pages** da aplicação.

### 2. Configurar sua API Key
1. Obra sua chave de API no jogo Torn (*Settings -> API Key*).
2. Insira a chave no campo **Sua API Key do Torn**.
3. Clique em **Salvar Chave**. Ela ficará armazenada no seu próprio navegador para acessos futuros.

### 3. Ativar Notificações
Clique no botão **🔔 Ativar Notificações do Navegador** e permita que a página envie alertas no seu dispositivo.

---

## 🔒 Segurança e Privacidade

- Este projeto é **100% client-side** (executado totalmente no seu próprio navegador).
- O código-fonte é público e não possui chaves fixas embutidas.
- A chave de API permanece local e você pode removê-la a qualquer momento clicando em **Remover**.

---

## 💻 Tecnologias Utilizadas

- HTML5 / CSS3
- JavaScript (ES6+)
- Fetch API (Torn API v2)
- Web Notifications API & Web Audio API