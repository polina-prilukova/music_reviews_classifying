## music_reviews_classifying
Классификация текстов отзывов с сайта магазина муз. инструментов

### Задача:
Анализ тональности - по тексту отзыва необходимо определить, является ли он нейтральным, позитивным или негативным 

#### Структура

Ноутбуки [Collecting_data.ipynb](https://github.com/polina-prilukova/music_reviews_classifying/blob/main/Collecting_data.ipynb) и [Collecting_links.ipynb](https://github.com/polina-prilukova/music_reviews_classifying/blob/main/Collecting_links.ipynb) содержат скрипты для сбора данных с сайта

В [Data_augmentation.ipynb](https://github.com/polina-prilukova/music_reviews_classifying/blob/main/Data_augmentation.ipynb) формируется полный датасет, скомпанованный из данных от нескольких источников.

[EDA_Modeling.ipynb](https://github.com/polina-prilukova/music_reviews_classifying/blob/main/EDA_Modeling.ipynb) - основной ноутбук проекта

[Data](https://github.com/polina-prilukova/music_reviews_classifying/tree/main/Data) содержит данные для анализа. 
- reviews.csv - исходные данные с сайта [pop-music.ru](https://pop-music.ru), 
- reviews_musicstore.csv - исходные данные с [musicstore.com](https://musicstore.com) 
- after_aug_preprocessed.csv - полный датасет

[Models](https://github.com/polina-prilukova/music_reviews_classifying/tree/main/Models) содержит веса моделей

[Reports](https://github.com/polina-prilukova/music_reviews_classifying/tree/main/Reports) - папка для отчетов
