# DLS Finale Project (1 семестр, styleGAN)
## Использование


#### CycleGAN
1) Используйте команду: ```git clone https://github.com/iRespectOnlyYen/dls_finale_project``` что бы скопировать репозиторий к себе в проект
2) Используйте команду: ``` cd cycleCAN ``` что бы сменить текущуу директорию
3) Для того что бы указать датасет измените параметр ```PATH_TO_DATASET``` в файле train.py на путь к Вашему датасету
4) Для того что бы запустить обучение просто запустите файл train.py или используйте команду ```python train.py``` 
4.1) Модель сохраняется каждую эпоху. Если вы хотите начать обучение используя существующую модель используйте ```python train.py --CONTINUE_LEARNING=True```

#### Telegram бот
1) Используйте команду: ```git clone https://github.com/iRespectOnlyYen/dls_finale_project``` что бы скопировать репозиторий к себе в проект, если Вы не сделали этого ранее
2) Замени параметр TOKEN в файле **telegram_bot.py** на свой токен
3) Что бы запустить бота просто запустите файл **telegram_bot.py**

### P. S. Сейчас телеграм бот доступен для использования https://t.me/stileviy_bot

