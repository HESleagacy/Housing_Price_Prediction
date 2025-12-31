# HESlegacy – California Housing Price Prediction API

**Model_finished**  
**CombinedAttributesAdder INCLUDED**  
**Production-Ready FastAPI**  
**Zero Pickle Errors**  
**Deployed in 2 minutes**

---

### Winner Model Stats
- **Algorithm**: RandomForestRegressor (GridSearchCV tuned)
- **Best Params**: `n_estimators=30`, `max_features=8`
- **Test RMSE**: ~48,000 USD
- **95% Confidence**: ± $3,800
- **Custom Features**: `rooms_per_household`, `population_per_household`, `bedrooms_per_room`

---

This work draws inspiration and guidance from the book  
**_Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow_**  
by **Aurélien Géron**.
---

📥 Clone the Repository
git clone https://github.com/HESleagacy/HESlegacy-California-Housing-API.git
cd HESlegacy-California-Housing-API

🧪 Create Virtual Environment (Recommended)
python -m venv venv
source venv/bin/activate   # Linux / macOS
# venv\Scripts\activate    # Windows

📦 Install Dependencies
pip install -r requirements.txt


No pickle errors. No mysterious crashes. If this fails, the problem is not the repo.

🚀 Run the FastAPI Server
uvicorn main:app --reload


Server starts in seconds. Production-ready means it actually starts.

🌐 Access the API

Swagger UI:
👉 http://127.0.0.1:8000/docs

API Endpoint:
POST /predict

### API Endpoint
```bash
POST /predict

