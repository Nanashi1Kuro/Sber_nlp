### Описание проекта
Задание было дано в рамках тестового для NLP отдела в Сбербанке.

Данный проект посвящен анализу отзывов о банках с использованием данных с сайта banki.ru. В процессе анализа мы исследуем отзывы, проводим статистический анализ, визуализируем результаты и строим модели для оценки простой тональности отзывов(плохой/хороший).

### Структура репозитория

Репозиторий состоит из следующих элементов:

1. **Папка `data`**: Здесь хранятся данные, предоставленные для анализа. Эта папка может содержать файлы с отзывами о банках в формате CSV или других форматах.

2. **Test_Task (`.ipynb`)**: Файл Test Task содержит код для анализа данных, визуализации результатов и построения моделей машинного обучения. В ноутбуке демонстрируются шаги анализа данных, включая предварительную обработку, статистический анализ, визуализацию и построение моделей.

### Запуск ноутбука

Чтобы запустить ноутбук с анализом отзывов о банках, выполните следующие шаги:

1. **Установите Jupyter Notebook или Откройте через Google Colab**: Если у вас еще не установлен Jupyter Notebook, выполните установку, используя инструкции на [официальном сайте Jupyter](https://jupyter.org/install). Также ноутбук можно открыть непосредственно через платформу Google Colab, что позволяет запускать код в облаке без необходимости установки на локальной машине. Для этого перейдите по [ссылке](https://colab.research.google.com/) и загрузите ноутбук, нажав на кнопку "Upload" или открыв его напрямую из GitHub. 

Если вы выбрали локальный вариант запуска
  Клонируйте репозиторий: Склонируйте репозиторий на свой компьютер с помощью Git:

   ```bash
   git clone https://github.com/Nanashi1Kuro/Sber_nlp.git
  ```

2. **Откройте ноутбук**: Перейдите в каталог с клонированным репозиторием и запустите Jupyter Notebook:

    ```bash
    cd Sber_nlp
    jupyter notebook
