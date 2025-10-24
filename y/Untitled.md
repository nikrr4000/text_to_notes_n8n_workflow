Сертификаты генерируются локально через скрипт

## Используемые шаблоны сертификатов

- Кыргызстан русский шаблон – [kg ru.html](/hr/students/edu-projects-sup-and-dev/support-group/mezhdunarodnye-proekty/besplatnye-kursy-dlja-uchitelejj-informatiki-v-uzb/generacija-sertifikatov-lja-uchitelejj-sng/.files/kgru.html)
    
- Узбекистан русский шаблон – [uz ru.html](/hr/students/edu-projects-sup-and-dev/support-group/mezhdunarodnye-proekty/besplatnye-kursy-dlja-uchitelejj-informatiki-v-uzb/generacija-sertifikatov-lja-uchitelejj-sng/.files/uzru.html)
    
- Узбекистан английский шаблон – [uz en.html](/hr/students/edu-projects-sup-and-dev/support-group/mezhdunarodnye-proekty/besplatnye-kursy-dlja-uchitelejj-informatiki-v-uzb/generacija-sertifikatov-lja-uchitelejj-sng/.files/uzen.html)
    

## В каком виде должна быть выгрузка

Скрипт работает по схеме, которая требует для корректной работы следующие поля

- country – код страны. Допустимые значения:
    
    - uz
        
    - kg
        
- language – код языка. Допустимые значения:
    
    - en (в паре с uz)
        
    - ru (в паре с kg/uz)
        
- name – фио пользователя, которое будет указано в сертификате
    
- course – название курса (как в трекере)
    
- key – ключ тикета