### 🔑 Key Components

- **Dataset:** Utilizes the California Housing dataset with `MedHouseVal` (median house value) as the target variable.
- **Feature Engineering:** Adds domain-specific structural ratios (`BedroomsPerRoom` and `RoomsPerHousehold`) to enhance predictive signal.
- **Polynomial Features:** Generates 2nd-degree squared and pairwise interaction terms to capture complex, non-linear market relationships.
- **Regularization (Ridge Regression):** Applies regularization with an optimal penalty (alpha = 500.0$) to stabilize exploding polynomial weights and prevent overfitting.
- **Leakage-Free Pipeline:** Implements a strict 60/20/20 Train/Validation/Test split—ensuring feature scaling (Normalisation) and polynomial mappings are fitted exclusively on training data and reapplied using `.transform()`.
- **Evaluation** using R2 Score and Mean Squared Error (MSE).
