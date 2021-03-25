# Ahoy! Are You Ready for Climate Model Data Analysis?
### Let's sail the high seas together through the analysis of a global oceanographic climate model.

In this mini-workshop, we will be working with data from one of the world's best climate models as we build toward an understanding of its structure and meaning.

# Setup

All of our code will be written in Python (specifically, Python >= 3.4). To get set up correctly, please ensure you have Python3 installed on your machine. If it is not, you can install it from the official page [here](https://www.python.org/downloads/). Below, we will create a virtual environment and install the necessary Python packages for this mini-workshop. We can then use either the terminal (Mac) or command prompt (Windows) to run the following commands in the local git repository.

If you have trouble creating the virtual environment via the commands below, please feel free to contact me at patrickold96@gmail.com or use the following video tutorial to potentially address your challenges: [Mac](https://www.youtube.com/watch?v=Kg1Yvry_Ydk&ab_channel=CoreySchafer), [Windows](https://www.youtube.com/watch?v=APOPm01BVrk&ab_channel=CoreySchafer).

1. Clone the repository.

`git clone https://github.com/Patrick-Old/twilio-global-ocean.git`

2. Create the virtual environment.

`python3 -m venv climate`

3. Activate the virtual environment.

On Mac: `source climate/bin/activate`

On Windows: `climate\Scripts\activate.bat`

4. Make sure `pip` is up to date with the following command.

`pip install --upgrade pip`

5. Install all packages using `pip` to the virtual environment.

`pip install -r requirements.txt`

6. Launch Jupyter Notebook via the command below, then navigate to the "notebooks" folder to begin your voyage.

`jupyter notebook .`
