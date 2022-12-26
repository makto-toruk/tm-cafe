# TM Cafe
Our recipe book is [here](https://makto-toruk.github.io/tm-cafe/README.html).

# setup
For building Jupyter book and pushing to github pages:
```
python -m venv cafeenv
source cafeenv/bin/activate
pip install -r requirements.txt
```

1. Build the book:
    ```
    jupyter-book build .
    ```
2. Push to github pages:
    ```
    ghp-import -n -p -f _build/html
    ```