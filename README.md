# Race,Gender prediction from Name
Guess the gender and race of a person using characteristics of the name using Natural Language Processing and Machine Learning.

## Dataset
Link : https://mbejda.github.io/
All of these datasets are for research and analysis.

## Steps
* Data collection
* Preprocessing and cleaning
* Feature Engineering
* Exploratory Data Analysis
* Vectorization
* Model implementation and training
* Cross validation and tunning

### Preprocessing
Clean and preprocess name data, handle missing values
#### Removes
* numbers and other non alphabets characters
* initials
* sentence start with along, with
* removes address from name
## ![](/img/pre.png)
### Feature Engineering
Features generated from name are,
* Length - character count
* ll_is_v - Last letter is vowel, 0 - False, 1 - True
* fl_is_v - First letter is vowel, 0 - False, 1 - True
* first_2 - First two letters of name
* last_2 - Last two letters of name
* first_3 - First three letters of name
* last_3 - Last three letters of name
## ![](/img/fafter.png)
