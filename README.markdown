# Pivotal Tracker Time Estimation

I present a way to get probabilities of getting stories done which takes into
account the variability between 1-pointer and 2-pointer stories. 2-pointers usually
take more time than 1-pointers. Thus, 20 1-pointers might take a lot faster to get
done than 10 2-pointers, even though the two sets have the same total amount
of points.

For more information, see my following [article](http://edderic.github.io/2015/07/12/probability-of-hitting-deadlines-based-on-pivotal-tracker-points.html)

## Requirements

- a pivotal tracker token
- a project id associated with the pivotal tracker token
- [IPython Notebook](http://ipython.org/notebook.html), [matplotlib](http://matplotlib.org/downloads.html), [pandas](http://pandas.pydata.org/pandas-docs/stable/install.html), [numpy](http://docs.scipy.org/doc/numpy/user/install.html) installation.


### Usage

- Clone/download this repo.
- `cd` into the directory.
- Fire up iPython Notebook: `ipython notebook`.
- Add your credentials (pivotal tracker token and project id)
- Click the `cell` menu and click `Run all`.
- Wait for the data to load.
- play around with the `prob_get_done` function (there's examples at the very bottom
of the iPython notebook).

   <img src="http://edderic.github.io/images/1-point-conv-wself-4-prob-under-hrs-8.png" alt="Probability of getting Five 1-Pointers done in Eight Working Hours">

   <img src="http://edderic.github.io/images/2-point-conv-wself-1-prob-under-hrs-8.png" alt="Probability of getting Two 2-Pointers done in Eight Working Hours">


