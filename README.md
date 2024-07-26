## Surveillance Station

## [Surveillance Station 9.1.2-10854](https://archive.synology.com/download/Package/SurveillanceStation)
---
### Диспетчер задач
- Панель управления -> Планировщик задач.
- Создать -> Запланированное задание -> Пользовательский сценарий.
- Общие: Пользователь = root, снимите флажок Включить.
- Настройки задачи: Пользовательский сценарий = ...
- Нажмите и запустите задачу.
- Удалите эту задачу, когда увидите.......

---
### A. x86_64 (9.2.0-11289)
- Link download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.2.0-11289/SurveillanceStation-x86_64-9.2.0-11289.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/ohyeah521/Surveillance-Station/main/9.2.0_11289/SurveillanceStation-x86_64/install_license)
```

---  

---
### A. x86_64 (9.1.2-10854)
- Link download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.1.2-10854/SurveillanceStation-x86_64-9.1.2-10854.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/ZwiReKsyno/Surveillance-Station/main/lib/SurveillanceStation-x86_64/install_license)
```

### B. x86_64_openvino (9.1.1-10728)
- Link download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.1.1-10728/SurveillanceStation-x86_64-9.1.1-10728_openvino.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/ZwiReKsyno/Surveillance-Station/main/lib/SurveillanceStation-x86_64_openvino/install_license)
```

### C. armada38x (9.0.2-10061)
- Link download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.0.2-10061/SurveillanceStation-armada38x-9.0.2-10061.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/ZwiReKsyno/Surveillance-Station/main/lib/SurveillanceStation-armada38x/install_license)
```

---
### Remove license
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/ZwiReKsyno/Surveillance-Station/main/lib/license/remove_license)
```
https://archive.synology.com/download/Package/SurveillanceStation
