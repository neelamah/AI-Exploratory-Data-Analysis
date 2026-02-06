# AI-Exploratory-Data-Analysis
EDA (Exploratory Data Analysis) for AI/ML datasets using  python , Pandas, NumPy, Matplotlib, and Seaborn.

EDA(Exploratory Data Analysis):- 
    Exploratory Data Analysis (EDA) is the process of analyzing and visualizing a dataset to understand its structure, detect patterns, anomalies, and inconsistencies, and prepare it for further modeling.

steps:- 

1. Data cleaning:-
    Type of Cleaning - 	Example in Dataset
    Duplicates:-    	ID 1 repeated with slightly different formats
    Missing values:- 	Missing Email, Phone, Age, Review, Rating
    Invalid numeric	:-  Qty blank, Price = "abc"
    Inconsistent text:-	Category = widgets, Widgets, wIdGeTs; Country = US, USA, United States, CAN
    Incorrect email formats:- 	bob AT mail.com, gigi@mail
    Incorrect phone formats:- 	123456789, 123-456, +44 123 456 789
    Boolean inconsistency:- 	Returned = No, no, False, false, Y, NA
    Date inconsistencies:- 	JoinDate and LastLogin have multiple formats (MM/DD/YYYY, DD-MM-YYYY, “July 3, 2025”)
    Text inconsistencies:-	Review text: “Love it!”, “love it!”, “ok fine”, blank
    Missing totals:- 	Total missing or needs recalculation
    VIP column:- 	Mix of Yes, No, True, False, blank (boolean conversion needed)

2.  Visualize Data:-
    Create plots to understand patterns & relationships:
    Histograms, bar charts (distribution)
    Scatter plots (numeric relationships)
    Correlation heatmaps (numeric correlation)

Libraries Used:- 
    List all Python libraries you used.
    Example:
    - pandas
    - numpy
    - matplotlib
    - seaborn
