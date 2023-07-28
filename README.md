# **Statistical Rethinking with Python and PyMC**

[Statistical Rethinking](http://xcelab.net/rm/statistical-rethinking/) is an incredible resource for learning Bayesian Statistics and was written by [Richard McElreath](https://xcelab.net/rm/), a Full Professor of Anthropology at the [Max Planck Institute for Evolutionary Anthropology](https://www.eva.mpg.de/ecology/staff/richard-mcelreath/). Aside from his intuitive explanations of Bayesian concepts, Statistical Rethinking also includes code written in `R` to express the logic of the statistical theories as an alternative to the equations we're used to seeing in math textbooks. Coupled with data to manipulate, the book is very effective in testing the logic of the mathematical models and watching the theory play out through real-world examples as represented by the data. In addition to the textbook,  Prof. McElreath has also released a complimentary playlist [video lectures](https://www.youtube.com/playlist?list=PLDcUM9US4XdM9_N6XUUFrhghGJ4K25bFc) for the textbook as another resource for understanding the ideas explained in the text.

As great of a source as the textbook is, one of its key drawbacks is that it requires the reader to have a proficient understanding of the syntax of `R` to read, run, and manipulate the code presented in the textbook. Luckily, the core dev team and other selfless contributors at [PyMC](https://github.com/pymc-devs/) has offered another alternative to interacting with this resource by porting the `R` code to `Python`. By utilizing `Python` libraries such as `pymc`,`arviz`, `numpy`, and `scipy`, they were able to create `Python` equivalents to the code that Prof. McElreath wrote in the textbook for the readers that are only familiar with `Python` syntax. Their contributions can be found in this [Github repository](https://github.com/pymc-devs/pymc-resources/tree/main/Rethinking_2).

With the foundation that they've laid, we're aiming to take their project one step further by forking their original [repository](https://github.com/pymc-devs/pymc-resources/tree/main/Rethinking_2), along with all the code examples written in Jupyter Notebooks, and adding our own summaries of the textbook material alongside each of the Python-ported code examples in the notebooks. By paraphrasing the textbook material in the Jupyter Notebooks that the [PyMC](https://www.pymc.io/welcome.html) team started, we're aiming to reduce the friction of having to switch back and forth between the textbook and the code examples for a learner who's only proficient in Python. We strongly believe that [Statistical Rethinking](https://www.routledge.com/Statistical-Rethinking-A-Bayesian-Course-with-Examples-in-R-and-STAN/McElreath/p/book/9780367139919) is an intuitive resource for building a solid foundation in the world of Bayes and with this project, our goal is to make your first steps as seamless as possible. Happy Learning!

<br>

**APA Reference:**

McElreath, R. (2020). *Statistical Rethinking: A Bayesian Course with examples in R and Stan.* Routledge.

<br>
<br>

## Installing the dependencies

To install the dependencies to run these notebooks, you can use [Anaconda](https://www.anaconda.com/products/individual#Downloads). Once you have installed Anaconda, run:

    conda env create -f environment.yml

to install all the dependencies into an isolated environment.

Activate the environment by running:

    source activate stat-rethink2-pymc

To use the notebooks you first have to register your new environment as a valid notebook kernel:

    python -m ipykernel install --user --name stat-rethink2-pymc3 --display-name "Python 3.10 (stat-rethink2-pymc3)"

You can start a notebook by running:
    
    jupyter notebook

or use the more modern jupyter lab:
    
    jupyter lab
    
from the root directory.