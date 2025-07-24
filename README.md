# Здравствуй, дорогой друг!  
Многие просят меня посоветовать хороший 🛡️ VPN / поделиться конфигом (учёткой). ❓  
  
🌐 И я решил создать этот репозиторий, где буду публиковать проверенные на работоспособность из РФ конфиги VPN по протоколам совместимым с v2ray/sing_box/Xray (т.е. VLESS, VMESS, trojan, shadowsocks, shadowsocksr и прочие, и их расширения) 💯 бесплатно ❗  
  
👉 Хочу обратить внимание, что какие-то сервера (конфиги) будут нормально работать у одного провайдера, но могут не работать у другого. Так же все сервера (конфиги) имеют непрогнозируемый срок жизни.💤 

## Программы-клиенты которые необходимо установить  
Для работы вам необходимо будет установить приложение клиент под вашу платформу.  
Установить надо одну программу, это перечисление аналогов.  
  
- 🤖 Android  
  - v2rayNG - https://github.com/2dust/v2rayNG/releases  
  - NekoBox - https://github.com/MatsuriDayo/NekoBoxForAndroid/releases  

- 💻 Windows and 🐧 Linux  
  - v2rayN - https://github.com/2dust/v2rayN/releases  
  - nekoray - https://github.com/MatsuriDayo/nekoray/releases (не обновляется с декабря 2024)  

- 🍎 Mac and 📱 iOS  
  - v2RayTun - https://apps.apple.com/ru/app/v2raytun/id6476628951  
  - streisand - https://apps.apple.com/ru/app/streisand/id6450534064  
  - foxray - https://apps.apple.com/ru/app/foxray/id6448898396  
  - shadowrocket - https://apps.apple.com/ru/app/shadowrocket/id932747118  
  - v2box - https://apps.apple.com/ru/app/v2box-v2ray-client/id6446814690  


## Ссылки которые необходимо добавить в программу клиент
В приложение надо добавить лист подписки с конфигами. Чуть ниже разберу на примере одного приложения.  
  
Я планирую вести два листа:
- ✔ (рекомендуемый) по протоколу VLESS с шифрованием tls как наиболее недетектируемый
  (на момент первой публикации содержит чуть более 200 конфигов)
  (ссылка для добавления в программу клиент) 🔻🔻🔻  
```
https://raw.githubusercontent.com/jov2000/v2ray/refs/heads/main/vless-tls.txt
```
- ❌ (резервный) все остальные протоколы, с tls и без, работающие на момент публикации из московского региона (содержит и первый список в т.ч.)(на случай если я заброшу этот репозиторий, а в списке выше не осталось рабочих серверов, либо требуется какой-то конкретный сервер)  
```
пока в тестировании
```


Источники  
https://github.com/barry-far/V2ray-Config  
https://github.com/Epodonios/v2ray-configs  
