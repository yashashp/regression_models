# Simple linear regression
The model is built on the dataset which contains the salary data based on experience.

Dataset: salary_data.csv
Salary: Salary based on experience

Description: The dataset contains the details of a employees experience in years and respective salary:
| Feature         | Description                                           | Used in Model |
|----------------|-------------------------------------------------------|---------------|
| YearsExperience| Unique ID of customer (not needed)                    | ✅             |
| Salary        | Last name (not relevant for prediction)                | ✅             |

## 🧠 Model Used

- Architecture: ANN with input layer → hidden layers → output layer (Sigmoid)
- Activation Functions: ReLU, Sigmoid
- Optimiser: Adam
- Loss Function: Binary Crossentropy

## 📈 Performance

- Accuracy: 86.8%
- Confusion Matrix:
- [[1530 65]
[ 199 206]]
