# 🚀 JARMIS-Local

O **JARMIS-Local** é uma aplicação local projetada para rodar diretamente no seu computador ou na sua rede local (LAN).

---

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado em seu computador:

- **[Node.js](https://nodejs.org/)** (versão 18 ou superior recomendada)
- **Git** (opcional, para clonar o repositório)

---

## 📥 Como Baixar e Instalar

### Método 1: Clonando o Repositório (Recomendado)
1. Abra o terminal ou Prompt de Comando (CMD).
2. Clone este repositório executando:
   ```bash
   git clone https://github.com/seu-usuario/JARMIS-Local.git
   ```
3. Acesse a pasta do projeto:
   ```bash
   cd JARMIS-Local
   ```

---

### Método 2: Download Manual (.zip)
1. Clique no botão verde **Code** no topo desta página do GitHub e selecione **Download ZIP**.
2. Extraia o arquivo `.zip` para uma pasta de sua preferência.
3. Abra a pasta extraída (`JARMIS-Local`).

---

## ⚙️ Instalando as Dependências

Antes de rodar a aplicação pela primeira vez, você precisa instalar as dependências do projeto:

1. Abra o terminal dentro da pasta `JARMIS-Local`.
2. Execute o comando:
   ```bash
   npm install
   ```

---

## ▶️ Como Executar a Aplicação

Você pode iniciar o projeto de duas formas:

### 1. No Windows (Via Scripts `.bat`)
Se estiver no Windows, basta clicar duas vezes nos arquivos de inicialização:
- **`start-jarmis.bat`**: Inicia o aplicativo para uso **apenas no seu computador** (`localhost`).
- **`start-jarmis-lan.bat`**: Inicia o aplicativo e libera o acesso para **outros dispositivos na mesma rede Wi-Fi/LAN**.

---

### 2. Pelo Terminal (Qualquer Sistema)
Você também pode rodar via linha de comando:

- **Uso Local:**
  ```bash
  npm start
  ```
- **Servidor com Node.js:**
  ```bash
  node server.mjs
  ```

---

## 🌐 Acessando o App

Após iniciar o servidor:
- **Localmente:** Abra o navegador e acesse `http://localhost:3000` (ou a porta informada no terminal).
- **Rede Local (LAN):** Use o endereço IP informado no terminal ao rodar o script LAN (ex: `http://192.168.x.x:3000`).

---

## 📁 Estrutura do Projeto

```text
JARMIS-Local/
├── public/              # Arquivos estáticos (index.html, imagens, etc.)
├── server.mjs           # Servidor backend principal (Node.js ES Modules)
├── package.json         # Dependências e scripts do projeto
├── start-jarmis.bat     # Atalho para rodar localmente no Windows
└── start-jarmis-lan.bat # Atalho para rodar na rede local no Windows
```

---

## 📄 Licença

Este projeto é mantido de forma privada/local. Sinta-se à vontade para modificar e adaptar conforme necessário.