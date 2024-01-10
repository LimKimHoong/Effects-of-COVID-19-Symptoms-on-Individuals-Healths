## *Effects of COVID-19 Symptoms on Individuals' Healths*

**Author:** [Lim Kim Hoong](https://github.com/LimKimHoong) ([kimhoong0324@gmail.com](mailto:kimhoong0324@gmail.com))

**Achievement:** *Assuming varied Covid-19 symptoms and utilizing a mixed-methods approach, this research demonstrates a nuanced understanding of their impact on individual health, offering valuable insights for informed healthcare strategies and public health policies.*

## How to Run

First, make sure that you have [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/install.html) installed and install the project.

```shell
mkvirtualenv Covid_19
pip install -e 'git+https://github.com/LimKimHoong/Effects-of-COVID-19-Symptoms-on-Individuals-Healths'
```

> For a private repository accessible only through an SSH authentication, substitute `git+https://github.com` with `git+ssh://git@github.com`.

## How to Contribute

First, make sure that you have [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/install.html) installed and install the project in development mode.

```shell
mkvirtualenv Stock_price
git clone https://github.com/LimKimHoong/Effects-of-COVID-19-Symptoms-on-Individuals-Healths.git
cd Covid_19
pip install -r requirements.txt
pip install -e .
pip freeze | grep -v covid_19 > requirements.txt
```

> For a private repository accessible only through an SSH authentication, substitute `https://github.com/` with `git@github.com:`.

Then, create or select a GitHub branch and have fun... 
