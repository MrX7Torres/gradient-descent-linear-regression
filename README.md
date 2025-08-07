# Gradient Descent for Linear Regression 📉

This project demonstrates a custom implementation of the **gradient descent algorithm** for solving a **linear regression** problem, applied to the **Iris dataset**.  
Developed as part of the **MeIA 2025** final project.

## 🎯 Objective

To implement linear regression from scratch using NumPy and optimize the model using gradient descent — without relying on libraries like scikit-learn.

## 📊 Dataset

- Dataset: [Iris Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
- Independent variables: `sepal_width`, `petal_width`, `sepal_length`
- Dependent variable: `petal_length`

## 🔁 Methodology

- Manual implementation of gradient descent
- Cost function: Mean Squared Error (MSE)
- Comparison with scikit-learn's `LinearRegression`
- Visualization of training progress and predictions

## 📈 Results

- Cost reduced from `3.14` to `~0.05` after 1000 iterations
- Manual model yielded parameters close to those from scikit-learn
- Clear match between predicted and real values in plots

## 📎 Key Libraries

- NumPy
- pandas
- matplotlib
- scikit-learn (for validation only)

## 🧠 Author

- Jesús Antonio Torres Contreras

## 📄 License

MIT License – see [`LICENSE`](./LICENSE)

