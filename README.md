<div id="top">

<p align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/SEU_BANNER.png">
  <source media="(prefers-color-scheme: light)" srcset="https://i.imgur.com/SEU_BANNER.png">
  <img alt="CardozoSS Logo" src="https://i.imgur.com/SEU_BANNER.png" width="75%">
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
| [ADB](https://developer.android.com/tools/adb) | Comunicação com o dispositivo |

---

### ⚙️ Execução

```sh
pkg update -y && pkg upgrade -y
pkg install curl android-tools -y

curl -L -o CardozoSS [Scan](https://github.com/CardozoServer/OlhosDoCapeta-Android/raw/refs/heads/main/cardozoss)
chmod +x CardozoSS

./CardozoSS
