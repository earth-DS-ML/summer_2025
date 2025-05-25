# Intro to JupyterLab

## JupyterLab

[JupyterLab](https://jupyterlab.readthedocs.io) will be our primary method for
interacting with the computer. JupyterLab contains a complete environment for
interactive scientific computing which runs in your web browser. Jupyter is an
open source python project that was started by scientists like yourselves who
wanted a more effective way to interact with their computers.

JupyterLab has excellent documentation. Rather than repeat that documentation
here, we point you to their docs. The following pages are particularly relevant:

- [The JupyterLab Interface](https://jupyterlab.readthedocs.io/en/stable/user/interface.html)
- [Working with Files](https://jupyterlab.readthedocs.io/en/stable/user/files.html)
- [The Text Editor](https://jupyterlab.readthedocs.io/en/stable/user/file_editor.html)
- [Notebooks](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html)
- [Terminals](https://jupyterlab.readthedocs.io/en/stable/user/terminal.html)
- [Managing Kernels and Terminals](https://jupyterlab.readthedocs.io/en/stable/user/running.html)

You will gain experience and familiarity with JupyterLab over the course of the
semester as we use it in our weekly lectures and assignments.

## Other development environments

There are other ways to interact with the computer using python as well. A summary of these can be found [here](https://github.com/yutianwuldeo/GR6901/blob/main/week2_how_to_run_python.md).

## Markdown

Throughout the course, we will write rich text documents using Markdown.
Here are some useful references on Markdown syntax.

- [Official Markdown Documentation](https://daringfireball.net/projects/markdown/)
- [Markdown Guide / Basic Syntax](https://www.markdownguide.org/basic-syntax) -
  A more user-friendly syntax guide.

## Our Course JupyterHub

[JupyterHub](https://jupyter.org/hub) is multi-user Jupyter environment designed for companies, classrooms and research labs.
This course will use a cloud-based JupyterHub environment supported by the [NSF LEAP STC](https://leap.columbia.edu/) and
managed by [2i2c](https://2i2c.org/infrastructure/):

[![Launch JupyterHub](https://img.shields.io/badge/jupyterhub-leap.2i2c.cloud-orange?style=for-the-badge&logo=jupyter)](https://leap.2i2c.cloud/)

A lot of documentation about this hub can be found at https://leap-stc.github.io/intro.html

## Using Git / GitHub from remote JupyterHub

The recommended way to move code in and out of a remote hub is via git / GitHub.
You should clone your project repo from the terminal and use git pull / git push to update and push changes.
In order to push data to GitHub from the hub, you will need to set up GitHub authentication.
[gh-scoped-creds](https://github.com/yuvipanda/gh-scoped-creds/) should be already setup
on your 2i2c managed JupyterHub, and we shall use that to authenticate to GitHub for
push / pull access.

Open a terminal in JupyterHub, run `gh-scoped-creds` and follow the prompts.

Alternatively, in a notebook, run the following code and follow the prompts:

```
import gh_scoped_creds
%ghscopedcreds
```

You should now be able to push to GitHub from the hub! These credentials will expire after
8 hours (or whenever your JupyterHub server stops), and you'll have to repeat these steps
to fetch a fresh set of credentials. Once you authenticate, you'll be provided with a link
to a [GitHub App](https://docs.github.com/en/developers/apps/getting-started-with-apps/about-apps)
that you have to [install](https://docs.github.com/en/developers/apps/managing-github-apps/installing-github-apps)
on the repositories you want to be able to push to from this particular JupyterHub. You only
need to do this once per JupyterHub, and can revoke access any time. You can always provide
access to your own personal repositories, but might need approval from admins of GitHub
organizations if you want to push to repos in that organization.

## Python Environments

On the LEAP hub everyone uses a common environment, which is inherited from these [docker images](https://github.com/pangeo-data/pangeo-docker-images/).

A thorough description of how to manage your own environment when needed can be found in: https://earth-env-data-science.github.io/lectures/environment/python_environments.html 
