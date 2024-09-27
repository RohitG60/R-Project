# R-studio

# 🎬 Hollywood's Most Profitable Stories Analysis 🍿

## 🌟 Project Overview
Welcome to the **Hollywood's Most Profitable Stories** analysis! In this R project, we dive into a fabulous dataset that contains juicy details about various films and their profitability. The aim is to load, clean, and manipulate the data, then create some smashing visualisations to uncover insights into the most profitable stories in Tinseltown! 🎉

## 📊 Dataset
The dataset used in this project is available at the following URL:  
[Hollywood's Most Profitable Stories Dataset](https://public.tableau.com/app/sample-data/HollywoodsMostProfitableStories.csv)

## 🚀 Getting Started
### 🛠️ Prerequisites
Before you get started, make sure you've got the following installed:
- **R** (version 4.0 or later)
- **RStudio**
- The following R packages:
  - `tidyverse`
  - `ggplot2`

You can install the required packages using these commands:

install.packages("tidyverse")
install.packages("ggplot2")

📥 Loading the Data
Ready to roll? You can load the dataset into R using this code:

df <- read.csv("https://public.tableau.com/app/sample-data/HollywoodsMostProfitableStories.csv")

This will pull in all the fabulous data we need to get started! 🚀


🔍 Data Exploration
Once the data is loaded, you can explore it using the following commands:

View(df)            # View the dataset in RStudio
print(df)          # Print the entire dataset
head(df)           # Display the first few rows
tail(df)           # Display the last few rows
summary(df)        # Get summary statistics
total_rows <- nrow(df)    # Count total number of rows
total_columns <- ncol(df)  # Count total number of columns
total_elements <- length(df) # Count total number of elements
total_non_na <- sum(!is.na(df)) # Count total non-NA values
column_names <- colnames(df)   # Get column names
str(df)             # Display the structure of the dataset
sapply(df, class)   # Get class of each column
sum(is.na(df))      # Count total NA values

🧹 Data Cleaning
In this project, you may want to handle any pesky missing values and ensure data quality. Here are some useful commands:

is.na(df)                        # Check for NA values
which(is.na(df))                 # Identify the location of NA values
complete.cases(df)              # Check for complete cases

📈 Data Visualisation
To create stunning visuals, you’ll need to load the tidyverse and ggplot2 libraries:
library(tidyverse)
library(ggplot2)

![image](https://github.com/user-attachments/assets/2edb44b7-1e54-4b7a-b316-0cae0e6c84a0)

![image](https://github.com/user-attachments/assets/a9429faf-befa-477e-b9d2-9f7ccf9be863)


Use these libraries to whip up some insightful visualisations based on your analysis. 🎨✨

💾 Saving Cleaned Data
Finally, after giving your dataset a good tidy up, you can save it as a CSV file:
write.csv(df, "clean_df.csv")  # Save the cleaned dataset

🎉 Conclusion
This project is a delightful demonstration of how to load, clean, and analyse a dataset in R. With some smashing visualisations, we can gain fantastic insights into the profitability of Hollywood stories. Cheers to that! 🥂

🙏 Acknowledgments
A big thank you to the creators of the Hollywood's Most Profitable Stories Dataset for providing such a fab resource!
📜 License
This project is licensed under the MIT License - see the LICENSE.md file for details. 📝


