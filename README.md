<div id="top">

<p align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="[https://i.imgur.com/SEU_BANNER.png](https://ptb.discord.com/channels/@me/1498868970252664914/1504583171302227998)">
  <source media="(prefers-color-scheme: light)" srcset="[https://i.imgur.com/SEU_BANNER.png](https://ptb.discord.com/channels/@me/1498868970252664914/1504583171302227998)">
  <img alt="CardozoSS Logo" src="[https://i.imgur.com/SEU_BANNER.png](https://ptb.discord.com/channels/@me/1498868970252664914/1504583171302227998)" width="75%">
</picture>

</p>

<p align="center">
  <em>Tecnologia, automação e análise avançada para dispositivos Android.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-121212?style=for-the-badge">
  <img src="https://img.shields.io/badge/Golang-6f42ff?style=for-the-badge">
  <img src="https://img.shields.io/badge/ADB-Supported-8b5cf6?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Online-a855f7?style=for-the-badge">
</p>

</div>

<img src="https://i.imgur.com/NnWf7Fm.png" width="100%" height="3px">

# 📖 Sobre

O **CardozoSS** é uma ferramenta desenvolvida para análise rápida e automatizada de dispositivos Android, reunindo informações importantes do Free Fire em poucos segundos.

O projeto foi pensado para simplificar verificações técnicas durante telagens e inspeções, automatizando processos que normalmente exigiriam diversas etapas manuais.

Com um sistema leve, rápido e eficiente, o scanner realiza verificações diretamente nos arquivos internos do jogo, identificando alterações suspeitas, arquivos incomuns e informações relevantes para análise.

---

# ⚡ Recursos

| Função | Descrição |
|--------|------------|
| 🎮 Verificação do Free Fire | Detecta instalações do jogo no dispositivo |
| 📂 Scanner de Replays | Analisa arquivos `.bin` presentes no sistema |
| 🟣 Shaders | Verificação de alterações gráficas suspeitas |
| 🔐 Root | Detecta possíveis sinais de root |
| 🕒 Data & Hora | Verifica alterações incomuns no sistema |
| ⚡ Automação | Processos rápidos e totalmente automatizados |

---

# 🚀 Utilização

### 📥 Instale o Termux

| Aplicativo | Função |
|------------|--------|
| [Termux](https://f-droid.org/repo/com.termux_1022.apk) | Ambiente utilizado para execução |

---

### ⚙️ Execução

```sh
# 1. Atualizar o Termux
pkg update -y && pkg upgrade -y

# 2. Instalar dependências
pkg install curl android-tools -y

# 3. Parear ADB (substitua xxxxx pela porta e código)
adb pair localhost:xxxxx xxxxxx

# 4. Conectar ADB (substitua xxxxx pela porta)
adb connect localhost:xxxxx

# 5. Baixar o scanner 
curl -L -o CardozoSS https://raw.githubusercontent.com/CardozoServer/OlhosDoCapeta-Android/main/cardozoss

# 6. Dar permissão de execução
chmod +x CardozoSS

# 7. Executar
./CardozoSS ´´´
