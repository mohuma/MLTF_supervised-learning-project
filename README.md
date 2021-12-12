### Date created
Finding Donors for CharityML project in Python/Jupyter was created on 24-Nov-2021.

### Project Title
**Finding Donors for CharityML**

### Description
CharityML is a fictitious charity organization located in the heart of Silicon
Valley that was established to provide financial support for people eager to learn
machine learning. After nearly 32,000 letters were sent to people in the community,
CharityML determined that every donation they received came from someone that was
making more than $50,000 annually. To expand their potential donor base, CharityML
has decided to send letters to residents of California, but to only those most
likely to donate to the charity.

In this project, I employed several supervised algorithms to accurately model
individuals' income using data collected from the 1994 U.S. Census. I then chose
the best candidate algorithm from preliminary results and further optimized this
algorithm to best model the data. My goal with this implementation is to construct
a model that accurately predicts whether an individual makes more than $50,000.

### Files used
census.csv - The modified census dataset consists of approximately 32,000 data
points, with each data point having 13 features.

**Features**
- `age`: Age
- `workclass`: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov,
    Local-gov, State-gov, Without-pay, Never-worked)
- `education_level`: Level of Education (Bachelors, Some-college, 11th, HS-grad,
    Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th,
    Doctorate, 5th-6th, Preschool)
- `education-num`: Number of educational years completed
- `marital-status`: Marital status (Married-civ-spouse, Divorced, Never-married,
    Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- `occupation`: Work Occupation (Tech-support, Craft-repair, Other-service, Sales,
    Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical,
    Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
- `relationship`: Relationship Status (Wife, Own-child, Husband, Not-in-family,
    Other-relative, Unmarried)
- `race`: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- `sex`: Sex (Female, Male)
- `capital-gain`: Monetary Capital Gains
- `capital-loss`: Monetary Capital Losses
- `hours-per-week`: Average Hours Per Week Worked
- `native-country`: Native Country (United-States, Cambodia, England, Puerto-Rico,
    Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China,
    Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico,
    Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti,
    Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia,
    El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

**Target Variable**
- `income`: Income Class (<=50K, >50K)

visuals.py - A Python file containing visualization code that is run behind-the-scenes.

### Credits
The dataset for this project originates from [UCI Machine Leaning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income) free of charge.
