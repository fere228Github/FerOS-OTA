# FerOS OTA

Обновления FerOS - неофициальная сборка LineageOS 18.1 (стек Mi-Thorium, ядро 4.19)
для Xiaomi Redmi Note 5A "ugglite" (таргет Mi8937_4_19).

Файл ota.json в формате Lineage Updater: в системе он прописан через свойство
lineage.updater.uri (raw-ссылка на этот файл). Сами сборки лежат release-ассетами
с тегами v<версия>. Установка - встроенным Updater'ом по воздуху либо из
рекавери (adb sideload).