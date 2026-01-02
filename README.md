MADE BY CHATGPT, ANY INFORMATION COULD BE FALSE

CHATGPT BILAN YOZILGAN, MA'LUMOT NOTO'G'RI BO'LISHI MUMKIN

СДЕЛАНО CHATGPT, ИНФОРМАЦИЯ МОЖЕТ БЫТЬ НЕВЕРНА

# DIYHome Smart Home Modules

## 🇺🇿 O‘zbekcha

## 📦 Umumiy ma’lumot

**DIYHome** — bu **DIY (o‘zing yig‘)** formatidagi aqlli uy modullari to‘plami bo‘lib, **faqat ta’limiy va tajriba maqsadlari** uchun mo‘ljallangan. Ushbu to‘plamlar o‘quvchilar, havaskorlar va muhandislikka qiziquvchilar uchun IoT, sensorlar, ESP platformasi va MQTT orqali aloqa tamoyillarini amaliy o‘rganishga yordam beradi.

⚠️ **Muhim ogohlantirish:**
Bu modullar **kundalik foydalanish**, **real xavfsizlik tizimlari** yoki **hayotiy muhim holatlar** uchun mo‘ljallanmagan. Ular sertifikatlanmagan va xavfsizlik kafolatlariga ega emas. Yong‘in, gaz, suv oqishi yoki xavfsizlikni ta’minlash uchun ularga ishonmang.

---

## 🧩 To‘plam tarkibi

Bitta **DIYHome to‘plami** quyidagi **11 ta moduldan** iborat:

1. 💧 Suv sizib chiqishini aniqlash moduli
2. 🌡 Harorat va namlik moduli
3. 🚶 Harakatni aniqlash moduli
4. 🔥 Yong‘in / olov sensori moduli
5. 💡 LED boshqaruv moduli
6. 🧪 Gaz sensori moduli
7. 🌧 Yomg‘ir sensori moduli
8. 🔊 Ovoz sensori moduli
9. 🚪 Eshik ochilish-yopilish moduli
10. 📳 Vibratsiya moduli
11. 🧠 Aqlli hub (markaziy boshqaruv moduli)

---

## 🧲 Jismoniy dizayn

* Barcha modullarning orqa tomonida **magnitlar** mavjud
* Bu ularni metall yuzalarga yoki magnit doskalarga oson o‘rnatish imkonini beradi

---

## ⚙️ Apparat platformasi

### Ishlatilgan mikrokontrollerlar

* **ESP-01 (ESP8266)**
  → Harorat moduli va hubdan tashqari barcha modullarda ishlatiladi

* **Wemos D1 Mini (ESP8266)**
  → Harorat va namlik modulida ishlatiladi

* **NodeMCU ESP8266**
  → Aqlli hub modulida ishlatiladi

### Hub qo‘shimcha qismlari

Hub quyidagilar bilan jihozlangan:

* 🔊 **DFPlayer Mini** audio modul
* 🔈 **4Ω 5W Aiyima** dinamik
* 🟩 **13×6 LED matritsa** (holat, ogohlantirish va animatsiyalar uchun)

---

## 🎵 Audio imkoniyatlar

Aqlli hub quyidagilarga dasturlanishi mumkin:

* **SD-karta** ichidagi sevimli musiqalarni ijro etish
* Ogohlantirishlar va bildirishnomalar uchun ovozdan foydalanish

Bu funksiyalar **o‘rganish va tajriba** uchun mo‘ljallangan.

---

## 🌐 Aloqa va dasturiy ta’minot

* Har bir modul uchun kodlar **open-source** hisoblanadi
* Modullar **MQTT** orqali aloqa qiladi
* Ular **shaxsiy (private) MQTT server** ga ulanish uchun mo‘ljallangan

---

## 📚 Ta’limiy maqsadlar haqida eslatma

Bu loyiha quyidagilar uchun yaratilgan:

* Elektronika va sensorlarni o‘rganish
* ESP8266 dasturlashni mashq qilish
* IoT tizimlar arxitekturasini tushunish

❗ **Xavfsizlik uchun mo‘ljallanmagan!**
Yong‘in signalizatsiyasi, gaz signalizatsiyasi yoki real xavfsizlik tizimi sifatida ishlatmang.

---

## 🇷🇺 Русский

## 📦 Общее описание

**DIYHome** — это набор **DIY-модулей умного дома**, предназначенных **исключительно для образовательных и экспериментальных целей**. Проект создан для учеников, энтузиастов и начинающих инженеров, чтобы изучать IoT, датчики, микроконтроллеры ESP и взаимодействие по MQTT.

⚠️ **Важное предупреждение:**
Модули **НЕ предназначены для повседневного использования** и **НЕ являются системами безопасности**. Они не сертифицированы и не обеспечивают надёжную защиту. Не используйте их в качестве пожарных, газовых или охранных систем.

---

## 🧩 Состав набора

Один набор **DIYHome** включает **11 модулей**:

1. 💧 Датчик протечки воды
2. 🌡 Датчик температуры и влажности
3. 🚶 Датчик движения
4. 🔥 Датчик огня / пламени
5. 💡 Модуль управления LED
6. 🧪 Датчик газа
7. 🌧 Датчик дождя
8. 🔊 Датчик звука
9. 🚪 Датчик открытия двери
10. 📳 Датчик вибрации
11. 🧠 Центральный hub-модуль

---

## 🧲 Физическая конструкция

* Все модули оснащены **магнитами на задней стороне**
* Это упрощает монтаж и перестановку модулей

---

## ⚙️ Аппаратная часть

### Используемые микроконтроллеры

* **ESP-01 (ESP8266)**
  → Используется во всех модулях, кроме температурного и hub-модуля

* **Wemos D1 Mini (ESP8266)**
  → Используется в модуле температуры и влажности

* **NodeMCU ESP8266**
  → Используется в центральном hub-модуле

### Дополнительно в hub-модуле

* 🔊 **DFPlayer Mini**
* 🔈 **Динамик Aiyima 4Ω 5W**
* 🟩 **LED-матрица 13×6** для индикации и анимаций

---

## 🎵 Аудио возможности

Hub можно запрограммировать так, чтобы он:

* Проигрывал любимые треки с **SD-карты**
* Использовал звук для уведомлений и демонстраций

---

## 🌐 Связь и программное обеспечение

* Код каждого модуля является **open-source**
* Модули взаимодействуют через **MQTT**
* Подключение осуществляется к **частному MQTT серверу**

---

## 📚 Образовательное назначение

Проект предназначен для:

* Изучения электроники и датчиков
* Практики программирования ESP8266
* Понимания архитектуры IoT-систем

❗ **Не использовать в системах безопасности!**

---

## 📜 Лицензия

Исходный код открыт. Подробности см. в файле `LICENSE`.


# 🇺🇸DIYHome Smart Home Modules
## 📦 Overview

**DIYHome** is a collection of **DIY smart home module kits** designed primarily for **educational and experimental purposes**. These kits are meant to help students, hobbyists, and makers learn about IoT, sensors, ESP-based microcontrollers, and MQTT-based communication in a hands-on way.

⚠️ **Important notice**:
These modules are **NOT intended for real-world, everyday, or safety‑critical smart home use**. They are **educational prototypes**, not certified safety devices. Do **not** rely on them for fire detection, gas detection, security, or any situation where failure could cause harm or damage.

---

## 🧩 Kit Contents

One **DIYHome kit** consists of **11 individual smart modules**, each focusing on a specific sensor or function:

1. 💧 **Water leak module**
2. 🌡 **Temperature & humidity module**
3. 🚶 **Motion detection module**
4. 🔥 **Fire / flame detection module**
5. 💡 **LED control module**
6. 🧪 **Gas detection module**
7. 🌧 **Rain detection module**
8. 🔊 **Sound detection module**
9. 🚪 **Door / open‑close module**
10. 📳 **Vibration module**
11. 🧠 **Smart hub module** (central controller)

---

## 🧲 Physical Design

* All modules are equipped with **magnets on the back**, allowing easy mounting on metal surfaces or magnetic boards.
* The modular design makes it easy to rearrange, test, and experiment with different layouts.

---

## ⚙️ Hardware Platform

### Microcontrollers used

* **ESP‑01 (ESP8266)**
  → Used in **all modules except** the temperature module and the smart hub.

* **Wemos D1 Mini (ESP8266)**
  → Used for the **temperature & humidity module**.

* **NodeMCU ESP8266**
  → Used for the **smart hub module**.

### Smart Hub Extras

The smart hub also includes:

* 🔊 **DFPlayer Mini** audio module
* 🔈 **4Ω 5W Aiyima speaker**
* 🟩 **13×6 LED matrix** for visual status, alerts, and animations

---

## 🎵 Audio Features

The smart hub can be programmed to:

* Play **custom or favorite songs** stored on an **SD card**
* Use audio for **alerts, notifications, or demonstrations**

This feature is intended for **learning and experimentation**, such as understanding audio modules, serial communication, and event‑based triggers.

---

## 🌐 Communication & Software

* All module firmware is **open‑source** and available in this repository.
* Modules communicate using **MQTT**.
* They are designed to connect to a **private MQTT server**.

This allows users to:

* Learn MQTT fundamentals
* Experiment with IoT messaging
* Build dashboards, automations, and logic externally

---

## 📚 Educational Purpose Disclaimer

This project is intended for:

* Learning electronics and sensors
* Practicing ESP8266 programming
* Understanding IoT architectures
* Experimenting with MQTT and modular systems

❗ **Not certified. Not hardened. Not fail‑safe.**
Do **NOT** use these modules as:

* Fire alarms
* Gas leak alarms
* Security systems
* Safety‑critical monitoring devices

---

## 📜 License

All code in this repository is **open‑sourced**.
Please check the `LICENSE` file for detailed terms.

---

## 🚀 Future Possibilities

DIYHome is modular by design, making it easy to:

* Add new sensor modules
* Extend hub functionality
* Improve visualizations on the matrix
* Integrate with custom dashboards or apps

If you’re curious, experimental, and want to **learn how smart homes work from the inside** — this project is for you.

Happy building 🛠️
