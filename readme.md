# DLS Finale Project (1 семестр, StyleGAN)
Перенос стиля между доменами. Обучены модели для photo2mone и selfie2anime. Ссылка на использованный датасет - https://drive.google.com/file/d/1lVB3C9KJd3zVtaQsScNOcCwpKb97RaKK/view?usp=sharing

## Использование


#### CycleGAN
1) Используйте команду: ```git clone https://github.com/iRespectOnlyYen/dls_finale_project``` что бы скопировать репозиторий к себе в проект
2) Используйте команду: ``` cd dls_finale_project ``` что бы сменить текущую директорию
3) Используйте команду: ``` pip install -r requirements.txt ``` что бы установить зависимости
4) Используйте команду: ``` cd СycleGAN ``` что бы сменить текущую директорию
5) Для того что бы указать датасет измените параметр ```PATH_TO_DATASET``` в файле train.py на путь к Вашему датасету
6) Для того что бы запустить обучение просто запустите файл train.py или используйте команду ```python train.py```
7) *Модель сохраняется каждую эпоху. Если вы хотите начать обучение используя существующую модель используйте ```python train.py --CONTINUE_LEARNING=True```*

#### Telegram бот
1) Используйте команду: ```git clone https://github.com/iRespectOnlyYen/dls_finale_project``` что бы скопировать репозиторий к себе в проект, если Вы не сделали этого ранее
2) Используйте команду: ``` cd dls_finale_project ``` что бы сменить текущую директорию
3) Используйте команду: ``` pip install -r requirements.txt ``` что бы установить зависимости, если ранее Вы этого не сделали
4) Замени параметр TOKEN в файле **telegram_bot.py** на свой токен
5) Что бы запустить бота просто запустите файл **telegram_bot.py**

### ~~P. S. Сейчас телеграм бот доступен для использования https://t.me/stileviy_bot~~

![example](https://github.com/iRespectOnlyYen/dls_finale_project/assets/90966720/d4ac743b-f393-40c6-a3bc-0ee11b66dca0)

