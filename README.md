# titanic-passenger-survival-ML

C# ML.NET project that predicts Titanic passenger survival using supervised learning.  
Built with Visual Studio 2022 as part of independent practice in applied machine learning.

---

## 📊 Project Overview
- **Type:** Binary Classification (Supervised Learning)  
- **Framework:** C# (.NET 8), ML.NET Model Builder  
- **Goal:** Predict survival outcome (0 = did not survive, 1 = survived) for Titanic passengers  

---

## 🧠 Concepts Applied
- **Supervised Learning** → trained model on labeled data (`Survived` column).  
- **Binary Classification** → survival outcome is yes/no.  
- **Data Preprocessing** → selected features (`Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`) and ignored irrelevant ones.  
- **Feature Selection** → used passenger characteristics most correlated with survival.  
- **Model Training & Evaluation** → model trained automatically with ML.NET, evaluated using accuracy.  
- **Prediction** → tested with new passenger data, produced probability scores for each class.  

---

## ⚙️ How to Run
1. Open the solution in **Visual Studio 2022**.  
2. Ensure generated files exist: `ModelInput.cs`, `ModelOutput.cs`, `ConsumeModel.cs`, `MLModel.zip`.  
3. Set the console app as **Startup Project**.  
4. Press **F5** to run → console prints survival prediction with probabilities.  

---


