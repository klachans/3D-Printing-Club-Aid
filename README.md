# 3D-Printing-Club-Aid

## Description
Python (Flask) based app, which helps to manage and monitor 3D Printing Club resources.   
Data is stored in SQL database.   

User can add new printers and filaments to database and start new printing, which will display on page containing following info:
* Printer
* % completion
* Used filament (and amount)
* Author
* Temperature and humidity (**only with required hardware!**)

**Important:**   
App works as it is, but originally was run on a Raspberry Pi 4B, with DTH11 sensor and MAX7219 7-segment display connected.   

95% complete (for more information - check TODO section).

## Interface
### Home
![image](https://github.com/klachans/3D-Printing-Club-Aid/assets/138781589/dace00a7-737c-464a-a72c-cd4e0df04957)

### Adding a new printer/filament
![image](https://github.com/klachans/3D-Printing-Club-Aid/assets/138781589/d7a05d2d-f954-4fab-b854-c2a75797cdd9)
![image](https://github.com/klachans/3D-Printing-Club-Aid/assets/138781589/e6cfdb01-913a-43a1-a2d6-3fbb6e9c8021)

### Starting a new print
![image](https://github.com/klachans/3D-Printing-Club-Aid/assets/138781589/bb31d4f0-f7c4-4bd0-a294-c644c0991725)

### Monitoring
![image](https://github.com/klachans/3D-Printing-Club-Aid/assets/138781589/1b27199d-6aee-458a-a225-66c02a28e3bb)

## Instructions
* Run main.py to start the webpage
* If running for the first time, run sql.py, then main.py
* Website adress will appear in terminal

## Requirements
* Libraries (Flask, sqlite3, datetime)

## TODO
* added printers and filaments should appear in droplist while starting a new print (currenly works on pre-filled data)
