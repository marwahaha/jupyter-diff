# Parse GeoJSON data of SF

From Jupyter Lab Open Studio! (at Bloomberg HQ)

Kunal Marwaha and Saul
Shanabrook // June 22 2019

This is an experiment in using version control for Jupyter notebooks, using the
tool [notedown](https://github.com/aaren/notedown) to automatically store
notebooks in Markdown.

## Why

Jupyter is a great tool for creating *notebooks* (`.ipynb` files). With
notebooks, one can explore new computational ideas and share narratives with
code. 


Ideas can change, and many turn to a form of version control to track
changes.

![PhD Comics by Jorge Cham](https://swcarpentry.github.io/git-
novice/fig/phd101212s.png)


However, the underlying format of notebooks is
JSON. It is relatively difficult to see changes to JSON objects in classic tools
like [diff](http://man7.org/linux/man-pages/man1/diff.1.html).

There is still not consensus on how to put Jupyter notebooks in version control
(see [here](https://stackoverflow.com/questions/18734739/using-ipython-
notebooks-under-version-control), [here](https://nextjournal.com/schmudde/how-
to-version-control-jupyter), [here](https://towardsdatascience.com/version-
control-with-jupyter-notebooks-f096f4d7035a), with varied solutions like
[nbdime](https://nbdime.readthedocs.io/en/latest/),
[nbstripout](https://github.com/kynan/nbstripout), or
[jupytext](https://github.com/mwouts/jupytext). 

Here, I will use
[notedown](https://github.com/aaren/notedown) to work with `.md` files in
Jupyter Lab, and use [git](https://git-scm.com/book/en/v2/Getting-Started-What-
is-Git%3F) for version control.

```{.python .input}

```

## Thanks!

Check out the latest [Jupyter Lab
interface](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html)
for working with notebooks in a friendly, responsive way.

```{.python .input}

```
