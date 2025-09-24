-----------------------------

3. UTILITY FUNCTIONS

-----------------------------

def mean_squared_error(y_true, y_pred):
"""Calculates the Mean Squared Error (MSE)."""
return np.mean((y_true - y_pred) ** 2)

def r2_score(y_true, y_pred):
"""Calculates the R^2 score."""
ss_res = np.sum((y_true - y_pred) ** 2)
ss_tot = np.sum((y_true - np.mean(y_true)) ** 2)
return 1 - (ss_res / ss_tot)

----------------------------- 👋 Hi, I’m @nusrat-samanta

<!---
nusrat-samanta/nusrat-samanta is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
