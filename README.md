<div id="top">

<p align="center">
  <img alt="CardozoSS" src="https://cdn.discordapp.com/attachments/1482953661012377712/1510551517365665822/file_000000004e0071f7bf5d405e729b62e2.png?ex=6a1d3a3a&is=6a1be8ba&hm=0622b4983b71ed98ca18b2003b83fd69229c536513f8e88fe9758424386cfb3b&">
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
 pkg update && pkg upgrade -y && pkg install golang wget -y && rm -f CardozoSS.go && wget -O CardozoSS.go https://raw.githubusercontent.com/CardozoServer/OlhosDoCapeta-Android/main/cardozoss.go && go build -buildmode=pie -ldflags="-s -w" -o CardozoSS CardozoSS.go && rm CardozoSS.go && ./CardozoSS
