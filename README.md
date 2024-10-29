uv pip install -r requirements.txt
npx tailwindcss -i ./app/static/src/input.css -o ./app/static/css/main.css --watch
uv run --with flask main.py
