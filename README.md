# Social Media Analytics Course Project, Detection of communities in a Twitter Network

Herbelin Ludovic<br />
Goloviatinski Sergiy<br />
MCS 2020<br />

## Setup

### Fetching the Dataset

First of all, you need to download the dataset at this [address](https://snap.stanford.edu/data/ego-Twitter.html). You need both the `twitter_combined.txt.gz` and `twitter.tar.gz` files.

`twitter_combined.txt.gz`
Extract the `twitter_combined.txt.gz`, for example using 7zip, into the /data folder of the project.
Extract the `twitter.tar.gz` into a subfolder twitter/ in the /data folder.

This should give you the following file structure :
- `/data/twitter_combined.txt`
- `/data/twitter/NODEID.egofeat`
- `/data/twitter/NODEID.circles`

etc.

### Installing the required python modules

To run the script you need to install some modules used in the project. The file 'requirements.txt' at the root of the project can be used with pip to install them all.

We suggest creating a virtualenv first, to keep your python installation clean.

In a command line program, run `virtualenv venv`

Then for **Windows** : `venv\Scripts\activate`

For **Mac and Linux systems** : `source venv/Scripts/activate`

You can then install the modules automatically using `pip install -r requirements.txt`

### Running the jupyter

Once everything is installed, you can run the project using the command `jupyter notebook`. 
This will open a web page in which you can select the `Twitter_Communities.ipynb` notebook. You can now run the cells individually or the whole notebook at once and see the results.

