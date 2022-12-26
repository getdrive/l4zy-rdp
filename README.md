# Lazy-RDP. ReUploaded

## Demo Video:
[![Lazy-RDP Demo](https://i.ytimg.com/vi/Kpl8l6YQq48/hqdefault.jpg)](https://youtu.be/Kpl8l6YQq48)
## Lazy-RDP over SSH:
[![Lazy-RDP over SSH](https://i.ytimg.com/vi/VXScp23WbZw/hqdefault.jpg)](https://youtu.be/VXScp23WbZw)

- Скрипт для автоматического сканирования списка адресов на наличие открытых RDP-портов, с последующим выбором метода и запуском перебора пары логин/пароль. <br/>

- Скрипт  настраивался для систем Kali linux 2.0, Kali linux 2016.2 и Kali linux 2017.1, 2017.2 и выше. <br/>

- Для корректной работы скрипта требуются установленные: masscan, curl и FreeRDP. <br/>

- Текущая версия 1.32. 
- Добавлено: поддержка XFCE, поддержка Parrot Security OS, автообновление, выбор сканера (Nmap) из списка, для сканирования локальных адресов из диапазона 127.0.0.1/8, возможность указания сканируемого порта. Исправлена ошибка ложноположительных срабатываний. Исправлена ошибка вылета из скрипта при выборе некоторых стран из списка. Добавлен английский язык. <s>Исправлен баг с брутфорсом.</s> Полностью поменял инструмент для брутфорса. Добавлена Hydra 9.3. Добавлена функция автоматического определения языка ОС. Оптимизирован код скрипта. Добавил автоматическую установку и настройку зависимостей (freerdp-X11, freerdp2-x11, masscan) для работы в "SANA" и "ROLLING". Добавлена возможность запуска скрипта c X11_OVER_SSH. <br/>

## Порядок установки


- Установка <br/>
               
	  git clone https://github.com/getdrive/l4zy-rdp
	  
	  cd l4zy-rdp && chmod +x hydra/configure hydra/hydra src/rdp_brute.sh start INSTALL

- Установка зависимостей <br/>
        
        ./INSTALL

- Запуск скрипта <br/>

        ./start


# Google translate

- Script for automatic scanning address list for open RDP-ports, then selecting a method and launching login/password pair scanning.  <br/>

- The script is tuned for Kali linux 2.0, Kali linux 2016.2 и Kali linux 2017.1, 2017.2 systems and higher versions . <br/>

- For the script to work correctly, you need to install: masscan, curl and FreeRDP <br/>

- The current version is 1.32.
- Added: XFCE support, Parrot Security OS support, auto-update, scanner selection (Nmap) from list, to scan local addresses in range 127.0.0.1/8, possibility to specify scanned port. Fixed false positives error. Fixed script exit error when selecting some countries from the list. Added English language to the list. Fixed bug with bruteforce. Completely changed Brutforce tool. Added Hydra 9.3. Added automatic detection of OS language. Optimized script code. Added automatic installation and setup of dependencies (freerdp-X11, freerdp2-x11, masscan) for working in "SANA" and "ROLLING". Added ability to run script with X11_OVER_SSH

## Installation

- Setting <br/>
         
	  git clone https://github.com/getdrive/l4zy-rdp
	  
	  cd l4zy-rdp && chmod +x hydra/configure hydra/hydra src/rdp_brute.sh start INSTALL


- Installing dependencies <br/>
        
        ./INSTALL

- Running the script <br/>

        ./start
        
# Disclaimer

  Этот сценарий должен использоваться только для образовательных целей и тестирования.<br/>
  Используйте его только на собственных сетях.<br/>
  Автор не несет ответственности за его использование.<br/>

  This script must be used only for educational purposes and Pentesting.<br/>
  Use it only on your own networks.<br/>
  Author is not responsible of its use.<br/>

# Supported Languages

 Russian & English.
