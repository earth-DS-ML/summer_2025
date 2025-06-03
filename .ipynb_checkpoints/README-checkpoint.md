# Steps for content creators

We are using the jupyter-book framework: https://jupyterbook.org/en/stable/start/overview.html

Steps to adding content: 
- Make sure `jupyter-book` is installed :
```
pip install -U jupyter-book
```
- Add or make changes to content files needed.
- build the book `jupyter-book build mybookname/`
- To publish the changes online we use steps from [here](https://jupyterbook.org/en/stable/start/publish.html#publish-your-book-online-with-github-pages):
    - First install `pip install ghp-import` if you don't have it.
    - in particular after the changes are made use `ghp-import -n -p -f _build/html`