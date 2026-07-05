#### 🌐 Language: [🇷🇺 Русский](#-активация-windows-guide-by-d1x2k) | [🇬🇧 English](#-windows-activation-guide-by-d1x2k)

---

# 🔑 Активация Windows (Guide by D1x2k)

# 🚀 Быстрый запуск (рекомендуется)

1. Откройте **Командную строку** или **Windows Terminal** **от имени Администратора**.
2. Вставьте следующую команду и нажмите **Enter**.

    powershell "iwr 'https://raw.githubusercontent.com/D1x2k/Windows-Activation-Guide/main/Windows-Activation.bat' -OutF $env:TEMP\1.bat; start $env:TEMP\1.bat -v runas"

⚡ **Преимущество скрипта:**

- 📥 Скачает последнюю версию с [GitHub](https://github.com/D1x2k/Windows-Activation-Guide/blob/main/Windows-Activation.bat);
- 🚀 Запустит её с правами администратора;
- 🔑 Автоматически подберёт и применит подходящий официальный GVLK-ключ для вашей редакции;
- ⚙️ Выполнит необходимые команды активации;
- 🗑️ Самостоятельно удалит файл скрипта в папке `%TEMP%`.

---

🛡️ **Гарантия безопасности:**
- Команда скачивает `.bat` файл с [официальной страницы релиза](https://github.com/D1x2k/Windows-Activation-Guide/blob/main/Windows-Activation.bat). Это можно увидеть посмотрев на **ссылку в команде.**
- Код `.bat` файла **полностью открыт и имеет всего 41 строку,** большую часть которых **занимает оформление.**
- Вы можете **самостоятельно** скачать `.bat` файл и запустить его от **имени администратора**, или воспользоваться **ручной установкой.**

> 
---

# 🛠️ Ручная установка

1. Откройте **Командную строку** или **Windows Terminal** **от имени Администратора**.
2. Скопируйте, вставьте и нажмите **Enter** для каждой из команд ниже.

---

1. **Установка публичного KMS-ключа (для Windows 10/11 Pro)**

    slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX

2. **Подключение к серверу лицензирования**

    slmgr /skms kms.digiboy.ir

3. **Запуск процесса активации в системе**

    slmgr /ato

4. **Проверить, что активация прошла успешно**

    slmgr /xpr

> 💡 **Важно:** Ключ в строке по умолчанию настроен на версию **Pro**. Если у вас установлена другая редакция, просто скопируйте нужный ключ из таблицы ниже и замените им первый блок символов (`W269N-...`) в команде перед тем, как нажать **Enter**.

---

### 📋 Список официальных KMS-ключей (GVLK)

| 🖥️ Редакция Windows | 🔑 Общедоступный KMS-Ключ |
| :--- | :--- |
| **Windows 10 / 11 Pro** | `W269N-WFGWX-YVC9B-4J6C9-T83GX` |
| **Windows 10 / 11 Home** | `TX9XD-98N7V-6WMQ6-BX7FG-H8Q99` |
| **Windows 10 / 11 Enterprise** | `NPPR9-FWDCX-D2C8J-H872K-2YT43` |
| **Windows 10 LTSC 2019 / 2021** | `M7XTQ-FN8P6-TTKYV-9D4CC-J462D` |

<br><br>

---

# 🔑 Windows Activation (Guide by D1x2k)

# 🚀 Quick Start (Recommended)

1. Open **Command Prompt** or **Windows Terminal** **as Administrator**.
2. Paste the following command and press **Enter**.

    powershell "iwr 'https://raw.githubusercontent.com/D1x2k/Windows-Activation-Guide/main/Windows-Activation.bat' -OutF $env:TEMP\1.bat; start $env:TEMP\1.bat -v runas"

⚡ **Script Advantages:**

- 📥 Downloads the latest version from [GitHub](https://github.com/D1x2k/Windows-Activation-Guide/blob/main/Windows-Activation.bat);
- 🚀 Runs it with administrator privileges;
- 🔑 Automatically selects and applies the appropriate official GVLK key for your edition;
- ⚙️ Executes the necessary activation commands;
- 🗑️ Automatically deletes the script file in the `%TEMP%` folder.

---

🛡️ **Security Guarantee:**
- The command downloads the `.bat` file from the [official release page](https://github.com/D1x2k/Windows-Activation-Guide/blob/main/Windows-Activation.bat). You can verify this by checking the **link in the command.**
- The `.bat` file code is **completely open source and consists of only 41 lines,** most of which are **used for formatting.**
- You can **manually** download the `.bat` file and run it **as administrator**, or use the **manual installation** method.

> 
---

# 🛠️ Manual Installation

1. Open **Command Prompt** or **Windows Terminal** **as Administrator**.
2. Copy, paste, and press **Enter** for each of the commands below.

---

1. **Install the public KMS key (for Windows 10/11 Pro)**

    slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX

2. **Connect to the licensing server**

    slmgr /skms kms.digiboy.ir

3. **Start the activation process in the system**

    slmgr /ato

4. **Verify that the activation was successful**

    slmgr /xpr

> 💡 **Important:** The default key in the command is configured for the **Pro** version. If you have a different edition installed, simply copy the appropriate key from the table below and replace the first block of characters (`W269N-...`) in the command before pressing **Enter**.

---

### 📋 List of official KMS keys (GVLK)

| 🖥️ Windows Edition | 🔑 Public KMS Key |
| :--- | :--- |
| **Windows 10 / 11 Pro** | `W269N-WFGWX-YVC9B-4J6C9-T83GX` |
| **Windows 10 / 11 Home** | `TX9XD-98N7V-6WMQ6-BX7FG-H8Q99` |
| **Windows 10 / 11 Enterprise** | `NPPR9-FWDCX-D2C8J-H872K-2YT43` |
| **Windows 10 LTSC 2019 / 2021** | `M7XTQ-FN8P6-TTKYV-9D4CC-J462D` |
