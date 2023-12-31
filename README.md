# URFUML2023_SE_Team1.13

Created by:  
Kravtsov A.V.  
ilin v.  
Salov A.S.  
Chashnikov S.Y.

---

Инструкция Kravtsov_main.py:

1. Установить зависимости transformers и streamlit
2. Запустить скрипт из терминала командой streamlit run Kravtsov_main.py

Приложение предназначено для определения доминирующей эмоции в тексте. Создано на основе модели "seara/rubert-tiny2-ru-go-emotions".

Версия в облаке: https://kravtsov.streamlit.app/  
<br>

Инструкция Kravtsov_fastAPI.py:

1. Установить зависимости командой pip install Kravtsov_requirements.txt
2. Запустить скрипт из терминала командой uvicorn Kravtsov_fastAPI:app
3. Отправить запрос: curl -X POST http://127.0.0.1:8000/predict/ -H 'Content-Type: application/json' -d '{"text": "I hate machine learning engineering!"}'

---

## Описание по запуску APP приложений HW

---

##Инструкция ilin_vik_web_hw2.py <br/>

[Посмотреть файл можно тут](ilin_vik_web_hw2.py)

Это преложение предназначена для перевода тескта с русского на английский.<br/>
Даное приложение запускается с помощью Streamlit фреймворк для создания веб-приложений<br/>
Для запуска вам потребуется установить библиотеки<br/>
Вы можете установить все библиотеки с файла requirements.txt<br/>
командой:

```python3
pip install -r requirements.txt
```

###Либо по отдельности

- pip install transformers
- pip install sacremose
- pip install streamlit
- pip install torch
- pip install watchdog - отслеживает изменение в коде и автоматически перезапускает его(Не обязательно ни как не влияет на работу приложения)<br/>

---

###запуск приложение можно из терминала командой: **streamlit run ilin_vik_web_hw.py**

---

![фото](/viktor_ilin/image/image-1.png)

---

## Это приложение запускается через FastAPI

[Посмотреть файл можно тут](fastAPI_Ilin.py)

---

## Это приложение развернуто на сервере Streamlit

[StreamlitAPP](https://ep5us9zjrjsbprfibektrn.streamlit.app)

[Сам код можно посмотреть тут](/viktor_ilin/PJ-ST/work_app.py)

---

Инструкция Chashnikov.py

Приложение предназначено для перевода текста с английского на русский. Создано на основе модели 'Helsinki-NLP/opus-mt-en-ru'.
Для запуска требуется установка transformers, streamlit, tensorflow

---

Инструкция Salov.py

Модель переводить текст с русского на английский язык  
Необходимые зависимости находятся в файле Salov_requirements.txt

Запустить модель можно используя терминал командой  
streamlit run Salov_HW1.py
