# NAI_project

! Project has been created in Google Colab so probaby it's best to launch it there 

# CONTRIBUTOR :
This project was created by Amelia Boszke (s27089)

# DESCRIPTION :
The program was created as a final project on NAI at the Polish-Japanese Academy of Information Technology. It is used to compare the performance of 3 language models (clip, top_15_anime_characters_image_detection, AnimeCharacterClassifierMark1) on a set of 50 randomly selected images of characters from famous anime, i.e. Eren Jeager, Naruto, Vegeta, Lelouch Lamperouge, Killua. The characters were selected based on the characters on which the top_15_anime_characters_image_detection model was previously trained - it had the smallest set of test data.

# USED MODELS :

1. CLIP
2. https://huggingface.co/dima806/top_15_anime_characters_image_detection by dima806
3. https://huggingface.co/Abhiram4/AnimeCharacterClassifierMark1 by Abhiram4

# SETUP 
Before starting work, download all the necessary libraries (if launched via collab, the libraries are already implemented in code) 

```!pip install transformers datasets huggingface_hub pillow torchvision numpy scikit-learn icrawler python-Levenshtein```

