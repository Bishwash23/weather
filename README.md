# Weather (Django)

Simple Django app that fetches current weather from OpenWeatherMap and stores recent searches.


## Setup

1. Install dependencies

```bash
pip install django requests python-decouple
```

2. Set your OpenWeather API key in the `.env` file at the project root:

```
API_KEY=your_real_api_key_here
```

The project uses `python-decouple` to read `API_KEY` from the environment or `.env`.

3. Run migrations and start the dev server:

```bash
python manage.py migrate
python manage.py runserver
```

4. Open http://127.0.0.1:8000/ in your browser and try a city search.

