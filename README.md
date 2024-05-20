

# Maritime Crew Size Prediction

Welcome to the Maritime Crew Size Prediction project! This repository contains the code and resources for predicting the optimal crew size for ships using Apache Spark and machine learning.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Learnings](#learnings)
- [Contributing](#contributing)
- [License](#license)
- [Full Report](#full-report)

## Introduction

In the maritime industry, managing the number of crew members on a ship is crucial for ensuring smooth operations and safety. With modern technology, we can now use big data and machine learning to make these management tasks more efficient. Using Apache Spark, a powerful tool for handling large amounts of data, we have developed a machine learning model to predict the needed crew size for different ships based on factors like the ship's age, size, and the number of passengers it can hold.

This project aims to help ship operators optimize their crew, reduce costs, and improve safety. By accurately estimating crew needs, operators can make better decisions about staffing and operations. Through this initiative, we're not just solving a technical problem but also enhancing maritime operations, making them safer and more efficient.

## Features

- **Crew Size Estimation**: Predicts the optimal number of crew members needed for a ship based on various factors.
- **Data Processing with Apache Spark**: Leverages Spark's robust data processing capabilities to handle large and complex datasets.
- **Machine Learning Models**: Utilizes Spark MLlib to develop and fine-tune machine learning models for accurate predictions.
 ![image](https://github.com/Pravesh0101/ApacheSpark-Maritime-Crew-Size-Prediction/assets/97783672/ea2262cb-c92c-45cd-b1aa-8dcc43147780)

- **Data Visualization**: Visualizes model outcomes through graphs and charts for clear, actionable insights.
 ![image](https://github.com/Pravesh0101/ApacheSpark-Maritime-Crew-Size-Prediction/assets/97783672/1b0dee46-805d-4e33-ada6-512e2f12ba2f)


## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/Maritime-Crew-Size-Prediction.git
   cd Maritime-Crew-Size-Prediction
   ```

2. **Set Up Apache Spark:**
   - Download and install [Apache Spark](https://spark.apache.org/downloads.html).
   - Follow the setup instructions to configure Spark on your system.

3. **Install Required Libraries:**
   Ensure you have the necessary Python libraries installed. You can install them using pip:
   ```sh
   pip install pyspark pandas matplotlib
   ```

## Usage

1. **Prepare Data:**
   - Ensure your dataset is in the appropriate format and accessible by the script.
   
2. **Run the Model:**
   - Use the provided scripts to preprocess the data, train the model, and make predictions.
   ```sh
   spark-submit crew_size_prediction.py
   ```

3. **Visualize Results:**
   - Visualize the model's predictions using the provided visualization scripts.

## Learnings

Through this project, we gained valuable insights into both technical and practical aspects of data analysis and machine learning in the maritime industry:

1. **Application of Apache Spark in Data Analysis:** Gained hands-on experience with Spark for data processing and analysis, enhancing our skills in handling large datasets.
2. **Understanding Maritime Operational Needs:** Learned about the specific needs of maritime logistics and how crew size impacts ship operations and safety.
3. **Implementation of Machine Learning Models:** Developed and fine-tuned machine learning models using Spark MLlib to predict optimal crew sizes.
4. **Data Visualization:** Created visualizations to interpret and present data clearly to stakeholders.
5. **Communication and Collaboration Skills:** Improved our ability to work as a team and effectively communicate complex technical concepts.

## Contributing

We welcome contributions to enhance the functionality and scope of this project. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Full Report

For a detailed overview of the project, including methodology and results, please refer to the full report: [ApacheSparkCrew.pdf](https://github.com/Pravesh0101/ApacheSpark-Maritime-Crew-Size-Prediction/files/15378156/ApacheSparkCrew.pdf)
