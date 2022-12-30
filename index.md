---
layout: default
---

What is this channel?

Hello. My name is Lyosha. I live in Tbilisi and love to run. But I am concerned about the poor air quality in this city. Therefore, I decided to write a bot that will check the level of pollution every hour and report on dangers. After all, when the level is dangerous - it is better not to run.

If you have any ideas - write in the comments to this post)


A bit of theory 

There is a general air condition index (AQI), which is calculated using a special formula. I don’t count anything, but I take data from free sources, namely from the service https://www.iqair.com/georgia/t-bilisi/tbilisi

Please note that there are very few of these sensors in Tbilisi, so the accuracy of the determination suffers and much depends on the specific area.  

From the general index, you can characterize the air, namely:

0 to 50 is good air
From 51 to 100 is valid,
101 to 150 bad
From 151 to 200 is very bad.


I propose the following version of the channel 

Every morning a message will be sent here with the current value of the air indicators.
If during the day the indicators fall sharply, or rise, my script will signal this.

That is, if the air was clean in the morning (for example, 13), and by the evening it crossed the boundaries of good air (became above 50), a notification will be sent to the channel. Then, let's say the growth continued to 101 - again we get a message. And in the evening I went down to 13 - again a message will come.


Why do You need it? 

By controlling air pollution, you can perform certain actions. For example, if the air is very dirty, you need to go out less and close all the windows of the house without opening them unnecessarily. If the air is clean, you can go for a walk or run.


О чём этот канал

Привет. Я Леша. Я живу в Тбилиси и люблю бегать. Но меня беспокоит плохое качество воздуха в этом городе. Именно поэтому я решил написать бота, который будет каждый час проверять уровень загрязнения и сообщать об опасностях. Потому что если уровень воздуха опасен - лучше не бегать и сидеть дома с закрытыми окнами.

Если есть идеи - пишите в комментариях к этому посту)
  

Немного теории 

Имеется общий индекс (AQI) состояни воздуха, который высчитвается по специальной формуле. Я ничего не считаю, а беру данные из свободных источников, а именно - с сервиса https://www.iqair.com/georgia/t-bilisi/tbilisi

Прошу заметить, что в Тбилиси этих датчиков очень мало, поэтому точность определения страдает и многое зависит от конкретного района.

Из общего индекса  можно дать характеристику воздуху, а именно:  

От 0 до 50 это хороший воздух,
От 51 до 100 допустимый,
От 101 до 150 плохой,
От 151 до 200 очень плохой. 


Предлагаю следующий вариант работы канала

Каждое утро сюда будет слаться сообщение с текущим значением показателей по воздуху.
Если в течении дня показатели резко упадут, или подымуться - мой скрипт об этом просигнализирует.
То есть, если с утра воздух был чистый (например, 13), а к вечеру перешел границы хорошего воздуха (стал выше 50) - в канал отправится уведомление. Потом, допустим продолжился рост до 101 - опять получаем сообщение. А к вечеру спустился до 13 - опять прийдет сообщение. 

 
Зачем вам это надо?  

Контроллируя загрязненность воздуха можно совершать те или иные действия. Например, если воздух очень грязный - нужно поменьше выходить на улицу и закрыть все окна дома, не открывая их без надобности.  Если воздух чистый - можно сходить прогуляться, или побегать.
