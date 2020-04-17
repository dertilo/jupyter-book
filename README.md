# Book made with Jupyter-Book
### based on https://github.com/jupyter/jupyter-book/tree/master/jupyter_book/book_template

```bash
docker run --rm --security-opt label:disable  \
   -v /home/tilo/code/WEB/jupyter-book/book:/srv/jekyll \
   -p 4000:4000 \
   -it -u 1000:1000 \
   emdupre/jupyter-book
```

docker run not yet properly working; still needs manual `jupyter-book build book`

### Thebelabs
use jupyter-notebook kernel 
run notebook where jupyterbook run `jupyter notebook --NotebookApp.allow_origin='*' --NotebookApp.token=letmein`