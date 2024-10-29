# **Statistics Calculator**
A web application designed to perform various statistical calculations, including Mean, Mode, Median, Range, Variance, and Standard Deviation. This project utilizes HTML for structure, CSS for styling, and JavaScript for the core logic, making statistical analysis accessible and easy to use.

### **Table of Contents**
- Overview
- Features
- Technologies
- Installation
- Usage
- Code Structure
- Contributing
- License



### **Overview**
The Statistics Calculator allows users to input a set of numbers and obtain statistical results instantly. It’s a useful tool for students, educators, and professionals who need quick and reliable statistical insights.


### **Features**
1. **Calculate Mean**: Find the average of a set of numbers.
2. **Calculate Mode**: Identify the number that appears most frequently.
3. **Calculate Median**: Determine the middle value of a sorted list.
4. **Calculate Range**: Compute the difference between the highest and lowest values.
5. **Calculate Variance**: Measure how far a set of numbers are spread out from their average.
6. **Calculate Standard Deviation**: Determine the amount of variation or dispersion in a set of values.
7. **User-Friendly Interface**: Simple and intuitive design for easy interaction.




### **Technologies**
- **HTML5**: For structuring the web application.
- **CSS3**: For styling and visual appeal.
- **JavaScript**: For implementing the statistical calculations and logic.




### **Installation**
1. Clone the repository:

```
git clone https://github.com/stephenombuya/statistics-calculator/tree/main
```

2. Navigate to the project directory:

```
cd statistics-calculator
```

3. Open the index.html file in a web browser to interact with the application.





### **Usage**
1. **Input Data**: Enter your data points in the provided input field. Separate multiple numbers with commas.
2. **Select Calculation**: Choose the statistical calculation you want to perform (Mean, Mode, Median, Range, Variance, or Standard Deviation).
3. **Calculate**: Click the "Calculate" button to compute the selected statistic.
4. **View Results**: The results will be displayed below the input field, showing the calculation along with the input data.





### **Code Structure**
- **index.html**: The main HTML file containing the structure and elements of the application.
- **styles.css**: The stylesheet for styling the user interface and enhancing the visual appeal.
- **script.js**: The JavaScript file that contains the logic for performing statistical calculations.




### **Sample Code**
Here's an example of the JavaScript function used to calculate the Mean:

```
const calculateMean = (numbers) => {
  const total = numbers.reduce((acc, num) => acc + num, 0);
  return total / numbers.length;
}
```


### **Other Statistical Functions**
1. **Mode**: Implemented using a frequency map to count occurrences.
2. **Median**: Uses sorting to find the middle value.
3. **Range**: Calculates by subtracting the minimum value from the maximum.
4. **Variance and Standard Deviation**: Uses the mean to determine how much the values deviate.





### **Contributing**
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature (git checkout -b feature-name).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-name).
5. Open a pull request.



### **License**
This project is licensed under the MIT License. See the [LICENSE](https://github.com/stephenombuya/statistics-calculator/blob/main/LICENSE) file for more details.
