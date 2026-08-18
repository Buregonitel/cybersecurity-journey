# План обучения кибербезопасности с нуля за 6 месяцев (только бесплатные ресурсы)

- План рассчитан на 15–20 часов в неделю.
- Если будешь заниматься меньше — растяни до 8–9 месяцев.
- Главное — регулярность и практика, а не просто просмотр видео.

## Общие принципы

- Каждый день/неделю делай заметки.
- Всё, что делаешь руками — сразу документируй (это потом пойдёт в портфолио).
- Используй VirtualBox/VMware + Ubuntu + Kali (бесплатно).
- Приоритет: **TryHackMe (бесплатный тир) + PortSwigger Web Security Academy + OverTheWire**.

## Месяц 1: Основы IT и Linux

**Цель:** комфортно чувствовать себя в Linux и понимать сети.

- Неделя 1–2: Linux CLI, файловая система, права, процессы, bash-скрипты.
- Ресурсы: Linux Journey (linuxjourney.com), OverTheWire Bandit (полностью), TryHackMe — Linux Fundamentals.
- Неделя 3: Сети — OSI/TCP-IP, IP, подсети, порты, DNS, HTTP/HTTPS.
- Ресурсы: Cisco Networking Academy — Introduction to Cybersecurity + Networking Basics (skillsforall.com), Professor Messer Network+ (YouTube).
- Неделя 4: Python основы + сетевое программирование.
- Ресурсы: freeCodeCamp Python, Automate the Boring Stuff (бесплатная книга), CS50P (Harvard).
- Практика: Настрой домашнюю лабораторию (2–3 виртуалки). Напиши простые скрипты (сканер портов, парсер логов).

## Месяц 2: Основы безопасности + криптография

**Цель:** понять, как думает безопасность.

- Изучи CIA-триаду, AAA, модели угроз, NIST CSF (базово).
- Разбери основные атаки: phishing, malware, social engineering.
- Изучи криптографию: хеши, симметричное/асимметричное шифрование, TLS, цифровые подписи.
- Ознакомься с OWASP Top 10.
- Ресурсы: TryHackMe — Pre-Security path (бесплатные комнаты).
- Ресурсы: Cisco — Cybersecurity Essentials.
- Ресурсы: Harvard CS50’s Introduction to Cybersecurity (freeCodeCamp YouTube).
- Ресурсы: OWASP Top 10 официальный сайт.
- Ресурсы: Professor Messer Security+ (YouTube) — разделы по основам.
- Практика: Разбери 2–3 реальных кейса утечек (Krebs on Security). Сделай простую лабораторию с паролями/хешами.

## Месяц 3: Инструменты и веб-безопасность

**Цель:** научиться пользоваться основными инструментами.

- Изучи Nmap, Wireshark, tcpdump.
- Освой Burp Suite Community.
- Изучи веб-уязвимости: SQLi, XSS, CSRF, IDOR, SSRF и т.д.
- Главный ресурс: **PortSwigger Web Security Academy** — полностью бесплатно. Проходи все apprentice-уровень + часть practitioner.
- Дополнительно: TryHackMe — комнаты по Nmap, Wireshark, Burp Suite, OWASP Top 10.
- Дополнительно: OWASP Juice Shop (локально).

## Месяц 4: Практический пентест и CTF

**Цель:** научиться атаковать легально и методично.

- Изучи методологию пентеста (recon → enumeration → exploitation → privilege escalation → post-exploitation).
- Разбери базовый Active Directory (если успеешь).
- Изучи Linux/Windows privilege escalation.
- Ресурсы: TryHackMe — Jr Penetration Tester path (бесплатные комнаты) + комнаты Metasploit, Privilege Escalation.
- Ресурсы: Hack The Box — бесплатные машины (Starting Point).
- Ресурсы: OverTheWire — Natas (веб).
- Ресурсы: PicoCTF (ежегодный, но старые задания доступны).
- Практика: Реши минимум 15–20 машин/комнат. На каждую пиши write-up.

## Месяц 5: Сертификаты + оборонительная сторона / углубление

**Бесплатные/почти бесплатные сертификаты:**

- **ISC2 Certified in Cybersecurity (CC)** — полностью бесплатно (обучение + экзамен) по программе One Million Certified. Лучший бесплатный входной сертификат.
- Fortinet NSE 1–3 (полностью бесплатно + сертификаты).
- Cisco Introduction to Cybersecurity + Cybersecurity Essentials (цифровые бейджи).
- Google Cybersecurity Professional Certificate — контент можно аудитировать бесплатно (сертификат платный, но знания бесплатные).
- Параллельно: TryHackMe — SOC Level 1 (бесплатные комнаты) или углубление в offensive.
- Параллельно: Базовый SIEM (ELK или бесплатный Splunk).

## Месяц 6: Проекты, CTF, портфолио и специализация

- Выбери направление: Offensive (пентест / bug bounty), Defensive (SOC / Blue Team) или Web AppSec.
- Сделай 4–6 полноценных write-up’ов.
- Создай собственные мини-проекты (скрипты, автоматизация, лабораторные стенды).
- Участвуй в CTF (CTFtime.org).
- Разбери реальные отчёты HackerOne / Bugcrowd (публичные).

## Как оформить всё на GitHub

- Создай репозиторий `cybersecurity-learning-journey` или `cybersec-portfolio`.
- Рекомендуемая структура:
  - `README.md` — главная страница-портфолио
  - `learning-log/` — еженедельные заметки
  - `notes/` — конспекты по темам
  - `writeups/` — райт-апы машин/комнат
  - `projects/` — собственные проекты
  - `certifications/` — скриншоты/бейджи сертификатов
  - `resources.md` — твои избранные ссылки
- Что писать в README.md:
  - Кратко о себе и цели (Junior SOC / Junior Pentester и т.д.)
  - Навыки (таблица)
  - Пройденные пути (TryHackMe, PortSwigger и т.д.)
  - Список проектов + ссылки
  - Сертификаты
  - Статистика (сколько машин решил, сколько часов)
- Важные правила оформления:
  - Каждый write-up и проект должен иметь хороший README с описанием: цель → что сделал → инструменты → результат → чему научился.
  - Используй скриншоты (но без чувствительных данных).
  - Пиши на английском (даже если учишься на русском) — так лучше для работодателей.
  - Делай коммиты регулярно (показывает активность).
  - Закрепи 4–6 лучших репозиториев на профиле.
- Дополнительно можно сделать отдельный сайт на GitHub Pages с красивым портфолио.

## Полезные ссылки-старт

- [TryHackMe](https://tryhackme.com)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [OverTheWire](https://overthewire.org)
- [Cisco Skills for All](https://skillsforall.com)
- [ISC2 Certified in Cybersecurity](https://www.isc2.org)
- [Linux Journey](https://linuxjourney.com)
- Professor Messer (YouTube)

- Начинай с **TryHackMe Pre-Security** + **OverTheWire Bandit** прямо сейчас.
- Через 2–3 недели у тебя уже будет ощутимый прогресс.
