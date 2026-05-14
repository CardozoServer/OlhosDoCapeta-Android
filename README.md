<div id="top">

<p align="center">
  <img alt="CardozoSS" src="https://media.discordapp.net/attachments/1498868970252664914/1504583614933897227/cardozoSS.png?ex=6a07842f&is=6a0632af&hm=d68cfd8eb9c41446a42fe2d2e741fb9f0d582fc24d712223dc41b053455f9725&=&format=webp&quality=lossless&width=828&height=552" width="75%">
</p>

</div>

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


1- Parear ADB:
executar "pkg install android-tools -y"
"adb pair localhost:PORTA CODIGO"
"adb connect localhos:PORTA"

2- executar 

```sh
 pkg update && pkg upgrade -y && pkg install wget android-tools -y && rm -f CardozoSS && wget -O CardozoSS https://raw.githubusercontent.com/CardozoServer/OlhosDoCapeta-Android/main/CardozoSS && chmod +x CardozoSS && adb push CardozoSS /data/local/tmp/ && adb shell "chmod +x /data/local/tmp/CardozoSS && /data/local/tmp/CardozoSS && rm /data/local/tmp/CardozoSS" && rm CardozoSS
