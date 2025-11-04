# Statistical Rethinking with PyMC

<!-- <div style="text-align: center; margin: 30px 0;">
  <img src="https://cdn.mos.cms.futurecdn.net/3kJhpErAArtBRJ8WnG8pNG.jpg.webp" alt="Statistical Rethinking Banner" style="max-width: 800px; width: 100%;">
</div> -->

Welcome to the **Statistical Rethinking with PyMC** interactive textbook companion! This resource brings Richard McElreath's exceptional [Statistical Rethinking](http://xcelab.net/rm/statistical-rethinking/) course to Python developers.

## 📚 About This Project

[Statistical Rethinking](http://xcelab.net/rm/statistical-rethinking/) is an incredible resource for learning Bayesian Statistics, written by [Richard McElreath](https://xcelab.net/rm/), Full Professor of Anthropology at the [Max Planck Institute for Evolutionary Anthropology](https://www.eva.mpg.de/ecology/staff/richard-mcelreath/).

### What Makes This Different

The original textbook uses R and Stan for its code examples. The core PyMC development team created Python ports of these examples, and **we've taken it one step further**: 

✨ **Each notebook includes comprehensive summaries of the textbook material alongside the Python code**, eliminating the need to constantly switch between the book and notebooks.

This approach makes Statistical Rethinking accessible to anyone proficient in Python, reducing friction and making your learning journey as seamless as possible.

## 🎯 What You'll Learn

- **Bayesian Thinking**: Build intuition for probabilistic reasoning
- **PyMC Modeling**: Hands-on experience with modern Bayesian tools
- **Causal Inference**: Understand DAGs and causal relationships
- **Practical Skills**: Apply these techniques to real-world data

## 🚀 How to Use This Book

### Online Reading
Navigate through chapters using the sidebar. Each chapter includes:
- 📖 Detailed explanations of statistical concepts
- 💻 Python/PyMC code implementations
- 📊 Visualizations and examples
- 🎓 Exercises to test your understanding

### Interactive Coding
Every notebook can be opened in Google Colab! Just click the Colab button at the top of any chapter to:
- Run code interactively
- Modify examples
- Experiment with your own data

### Local Development
Clone the repository to work offline:
```bash
git clone https://github.com/vanislekahuna/Statistical-Rethinking-PyMC.git
cd Statistical-Rethinking-PyMC
```

## 📋 Prerequisites

To get the most from this material:

- **Python**: Basic understanding of Python syntax
- **NumPy/Pandas**: Familiarity with these libraries is helpful
- **Statistics**: Some exposure helpful, but Bayesian knowledge not required!
- **Curiosity**: A genuine interest in understanding data through a Bayesian lens

## 🗺️ Course Structure

The book follows Richard McElreath's textbook structure:

**Part I: Foundations**
- Chapters 1-3: Bayesian basics and sampling
- Chapter 4: Linear models

**Part II: Linear Models**  
- Chapters 5-8: Multiple regression, causality, interactions

**Part III: Generalized Linear Models**
- Chapters 9-11: MCMC, maximum entropy, count data

**Part IV: Advanced Topics**
- Chapters 12-17: Multilevel models, measurement error, missing data

## 🎬 Getting Started

Ready to begin your Bayesian journey? Head to [Chapter 1: The Golem of Prague](Chp_01) to start learning!

## 🙏 Acknowledgments

This work builds upon:
- **Richard McElreath**: For the incredible original textbook and course
- **PyMC Team**: For porting the R/Stan code to Python
- **Community Contributors**: Everyone who has helped improve these materials

## 📖 Reference

McElreath, R. (2020). *Statistical Rethinking: A Bayesian Course with Examples in R and Stan* (2nd ed.). CRC Press.

## 🔗 Additional Resources

- [Statistical Rethinking Book](https://xcelab.net/rm/statistical-rethinking/)
- [Richard McElreath's Video Lectures](https://www.youtube.com/playlist?list=PLDcUM9US4XdM9_N6XUUFrhghGJ4K25bFc)
- [PyMC Documentation](https://www.pymc.io/)
- [PyMC Resources Repository](https://github.com/pymc-devs/pymc-resources)

---

<div style="text-align: center; margin-top: 40px; padding: 20px; background-color: #f5f5f5; border-radius: 8px;">
  <p style="font-size: 1.1em; margin: 0;">
    <strong>Questions or feedback?</strong> Open an issue on our 
    <a href="https://github.com/vanislekahuna/Statistical-Rethinking-PyMC">GitHub repository</a>
  </p>
</div>



<!-- # **Statistical Rethinking with Python and PyMC**

[Statistical Rethinking](http://xcelab.net/rm/statistical-rethinking/) is an incredible resource for learning Bayesian Statistics and was written by [Richard McElreath](https://xcelab.net/rm/), a Full Professor of Anthropology at the [Max Planck Institute for Evolutionary Anthropology](https://www.eva.mpg.de/ecology/staff/richard-mcelreath/). Aside from his intuitive explanations of Bayesian concepts, Statistical Rethinking also includes code written in `R` to express the logic of the statistical theories as an alternative to the equations we're used to seeing in math textbooks. Coupled with data to manipulate, the book is very effective in testing the logic of the mathematical models and watching the theory play out through real-world examples as represented by the data. In addition to the textbook,  Prof. McElreath has also released a complimentary playlist [video lectures](https://www.youtube.com/playlist?list=PLDcUM9US4XdM9_N6XUUFrhghGJ4K25bFc) for the textbook as another resource for understanding the ideas explained in the text.

As great of a source as the textbook is, one of its key drawbacks is that it requires the reader to have a proficient understanding of the syntax of `R` to read, run, and manipulate the code presented in the textbook. Luckily, the core dev team and other selfless contributors at [PyMC](https://github.com/pymc-devs/) has offered another alternative to interacting with this resource by porting the `R` code to `Python`. By utilizing `Python` libraries such as `pymc`,`arviz`, `numpy`, and `scipy`, they were able to create `Python` equivalents to the code that Prof. McElreath wrote in the textbook for the readers that are only familiar with `Python` syntax. Their contributions can be found in this [Github repository](https://github.com/pymc-devs/pymc-resources/tree/main/Rethinking_2).

With the foundation that they've laid, we're aiming to take their project one step further by forking their original [repository](https://github.com/pymc-devs/pymc-resources/tree/main/Rethinking_2), along with all the code examples written in Jupyter Notebooks, and adding our own summaries of the textbook material alongside each of the Python-ported code examples in the notebooks. By paraphrasing the textbook material in the Jupyter Notebooks that the [PyMC](https://www.pymc.io/welcome.html) team started, we're aiming to reduce the friction of having to switch back and forth between the textbook and the code examples for a learner who's only proficient in Python. We strongly believe that [Statistical Rethinking](https://www.routledge.com/Statistical-Rethinking-A-Bayesian-Course-with-Examples-in-R-and-STAN/McElreath/p/book/9780367139919) is an intuitive resource for building a solid foundation in the world of Bayes and with this project, our goal is to make your first steps as seamless as possible. Happy Learning!

Each `.ipynb` file should have the ability to run independently by clicking the "Open in Colab" button at the top of every notebook.

<br>

**APA Reference:**

McElreath, R. (2020). *Statistical Rethinking: A Bayesian Course with examples in R and Stan.* Routledge. -->