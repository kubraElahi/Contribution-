# 🧠 Bangla Religious Aggressive Comments Dataset (BRAC)


This dataset contains Bangla-language comments labeled for aggression and targeted religious hate Comments. It is designed to support research in Natural Language Processing (NLP), including aggression detection, hate speech moderation, and classification tasks focused on religious tolerance in online spaces.


# 📂 Dataset Overview
Language: Bangla (বাংলা)
Domain: Social Media, Online Comments
Total Samples: [add total rows, e.g. ~2,000]
Purpose: Aggression classification and religious hate speech analysis


# 🧾 Data Format
Each row in the dataset includes:


Column	Description
Comments	The Bangla-language comment text
Aggression Label	One of: Aggressive, Non-Aggressive
Target Religion	The religion targeted in the comment (e.g., Hindu, Muslim)


# 🔍 Sample Data
Comments,Aggression Label,Target Religion

তোরা কাফের, বাংলাদেশে থাকতে পারবি না।,Aggressive,Hindu

এটা সবার ধর্মের প্রতি সম্মান জানানোর দিন।,Non-Aggressive,

ধর্ম নিয়ে কথা বলবি তোকে কুত্তার মতো মারব।,Aggressive,Islam



# 🎯 Use Cases
This dataset is useful for:

Hate speech and aggression detection in Bangla

Religious bias classification

Social media moderation tools

Multilingual or cross-lingual NLP training

Transfer learning for low-resource languages

languages



# 🧑‍💻 How to Use
You can load and analyze the dataset using pandas:

import pandas as pd

df = pd.read_csv("Bangla_religious_aggressive_comments.csv")
print(df.head())


# 📚 Annotation Guidelines
[-] Aggressive: Includes threats, hate, or abuse.

Non-Aggressive: Respectful, neutral, or irrelevant comments.
Target Religion: Left blank if no religion is targeted. Each comment was manually reviewed and annotated by native Bangla speakers.


# 📈 Statistics
(Fill these out based on your data)

Aggressive: 10,000

Non-Aggressive: 10,000

Targeted Religions:

Hindu: 2500

Islam: 2500

Christian: 2500

Buddhist: 2500


# 🪪 License
This dataset is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. You may use, distribute, and modify the dataset with attribution.


# Find Bangla Religious Aggressive Comments Dataset 
https://github.com/Riad071/BRAC-Bengali-Religious-Aggressive-Comments

