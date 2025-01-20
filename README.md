# Установка ноды GaiaNet | $GAIA 💻

GaiaNet ([Сайт проекта](https://www.gaianet.ai/gaia-domain-name?referralCode=RDzEUh)) — децентрализованная сеть, предоставляющая безопасные и монетизируемые ИИ-агенты. Проект собрал [инвестиции в $10M](https://cryptorank.io/ico/gaianet#funding-rounds) от Mirana Ventures, Mantle, ByteTrade и других.

## Как участвовать ❓
1️⃣ Перейдите на сайт [GaiaNet](https://www.gaianet.ai/gaia-domain-name?referralCode=RDzEUh).  
2️⃣ Откройте вкладку "Gaia XP".  
3️⃣ Введите инвайт-код: **RDzEUh**.  
4️⃣ Выполните все доступные задания.  
5️⃣ Установите ноду, следуя гайду ниже.  
6️⃣ Также выполните задания на [Galxe](https://app.galxe.com/quest/Gaia/GCR2xtpVMe).  

**Дедлайн:** TBA⏳

## Установка ноды Gaia на VPS

### Технические требования:
- **CPU**: 4 ядра
- **RAM**: 8GB
- **Диск**: 200GB
- **Скорость интернета**: 10 Мбит/с
- **GPU**: Nvidia T4 (опционально для повышения скорости AI).

### Установка:

1. **Обновите систему:**
   ```bash
   sudo apt update && sudo apt upgrade -y
   ```

2. **Установите зависимости:**
   ```bash
   sudo apt install -y curl
   ```

3. **Скачайте и установите ноду Gaia:**
   ```bash
   curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
   ```

4. **Добавьте путь в переменные окружения:**
   ```bash
   source ~/.bashrc
   ```

5. **Инициализируйте ноду:**
   ```bash
   gaianet init
   ```

6. **Запустите ноду:**
   ```bash
   gaianet start
   ```

7. **Получите NodeID и DeviceID:**
   ```bash
   gaianet info
   ```

8. **После запуска ноды:**
   Если нода успешно запущена, в терминале появится публичный URL, например:
   ```
   https://0xxxxxxxxx.gaianet.xyz
   ```

   Откройте URL в браузере, чтобы проверить информацию о ноде.  
   На веб-сайте:
   - Перейдите в раздел "Профиль" → "Node" → "Connect New Node".
   - Введите **NodeID** и **DeviceID**.
   - Подтвердите с помощью MetaMask.
   - Вернитесь к заданию "XP Verify Task" и завершите его.

**Готово! Ваша нода успешно установлена и активирована.**
