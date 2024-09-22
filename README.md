Zahide Erva Bilen

[1erva.bilen@gmail.com]

# Drug Side Effects Data Analysis
This project involves the analysis of a dataset related to drug side effects. The main goal is to perform **Exploratory Data Analysis (EDA)**, clean and preprocess the data, and prepare it for potential machine learning models. The data includes information about users, their medications, side effects, and various medical conditions.

## Dataset Description

The dataset contains the following columns:
- **Kullanıcı_id**: Unique ID for each user (patients can have multiple entries for different drugs).
- **Cinsiyet**: Gender of the user.
- **Doğum_Tarihi**: Birthdate of the user.
- **Uyruk**: Nationality of the user.
- **İl**: The city where the user resides.
- **İlaç_Adi**: Name of the medication.
- **İlaç_Baslangic_Tarihi**: Start date of medication use.
- **İlaç_Bitiş_Tarihi**: End date of medication use.
- **Yan_Etki**: Reported side effect(s).
- **Yan_Etki_Bildirim_Tarihi**: Date when the side effect was reported.
- **Alerjilerim**: List of allergies of the user.
- **Kronik_Hastalıklarım**: List of chronic illnesses of the user.
- **Baba_Kronik_Hastalıkları**, **Anne_Kronik_Hastalıkları**, **Kız_Kardeş_Kronik_Hastalıkları**, **Erkek_Kardeş_Kronik_Hastalıkları**: Family medical history of chronic illnesses.
- **Kan_Grubu**: User's blood type.
- **Kilo**: Weight of the user (kg).
- **Boy**: Height of the user (cm).

## Key Steps and Findings

1. **Exploratory Data Analysis (EDA)**:
   - Used **Pandas**, **Matplotlib**, and **Seaborn** for data exploration and visualization.
   - Detected and visualized missing data, relationships between variables.
   - Created visualizations like line graphs, bar graphs, pie charts and histograms to represent data distribution and relationships.

2. **Data Preprocessing**:
   - Handled **missing values** using techniques such as **KNN Imputer** for both numerical and categorical variables.
   - **Encoded categorical variables** using **LabelEncoder**.
