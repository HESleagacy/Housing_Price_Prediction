# HESlegacy – California Housing Price Prediction API

A **production-ready FastAPI service** for predicting California housing prices using a tuned machine learning model.  
Built to run cleanly, predict reliably, and start without drama.

---

## ✅ Project Highlights
- **Model fully trained and finalized**
- **CombinedAttributesAdder included in pipeline**
- **FastAPI-ready for production**
- **Zero pickle / serialization issues**
- **Deployable in under 2 minutes**

No hacks. No “works on my machine” nonsense.

---

## 🏆 Model Performance
- **Algorithm**: RandomForestRegressor (GridSearchCV tuned)
- **Best Parameters**:
  - `n_estimators = 30`
  - `max_features = 8`
- **Test RMSE**: ≈ **$48,000**
- **95% Confidence Interval**: ± **$3,800**
- **Engineered Features**:
  - `rooms_per_household`
  - `population_per_household`
  - `bedrooms_per_room`

---

## 📚 Inspiration
This project follows the principles and pipeline design from:

**_Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow_**  
by **Aurélien Géron**

Applied faithfully, not copy-pasted blindly.

---

## 📥 Clone the Repository
```bash
git clone https://github.com/HESleagacy/HESlegacy-California-Housing-API.git
cd HESlegacy-California-Housing-API
