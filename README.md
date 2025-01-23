# NAI_project
Program powstał jako projekt zaliczeniowy z NAI na Polsko-Japońskiej Akademii Technik Komputerowych (filia w Gdańsku). Służy on do porównania działania 3 modeli języka ( clip, top_15_anime_characters_image_detection, AnimeCharacterClassifierMark1 ) na zbiorze 50 randomowo wylosowanych ,ze zbioru pobranych, obrazów postaci ze znanych anime tj. Eren Jeager, Naruto, Vegeta, Lelouch Lamperouge, Killua. Postacie zostały dobranie na podstawie postaci na których był uprzednio trenowany model top_15_anime_characters_image_detection - posiadał najmniejszy zestaw danych testowych.

# UŻYTE MODELE :

1. CLIP
2. https://huggingface.co/dima806/top_15_anime_characters_image_detection autorstwa dima806
3. https://huggingface.co/Abhiram4/AnimeCharacterClassifierMark1 autorstwa Abhiram4

# INSTALACJA BIBLIOTEK
Przed przystąpieniem do pracy należy pobrać wszystkie potrzebne biblioteki

```!pip install transformers datasets huggingface_hub pillow torchvision numpy scikit-learn icrawler python-Levenshtein```

