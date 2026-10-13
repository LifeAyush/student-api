# student-api

Interview exercise: an API for student records (name, age, address).

## How to run

```bash
git clone https://github.com/LifeAyush/student-api.git
cd student-api
pip install -r requirements.txt
export MONGODB_URI="your-mongodb-connection-string"
uvicorn app.main:app --reload
```

Create, list, fetch, update, and delete students at `/students/`. A student has `name`, `age`, and `address` (`city` and `country`). Listing accepts optional `country` and `age` query parameters.
