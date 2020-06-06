# Virtual-Screening-for-Abl-Kinase

This repo is a demonstration of using deep learning for Virtual Screening. My target will be Abl kinase (1FPU) and my dataset comes from http://dude.docking.org/ which provides active and decoy molecules for virtual screening. For prediction, I obtained my dataset through https://zinc.docking.org/, which is a database for commerically available compounds for virtual screening.

I have added my comments and thoughts in the pdf file, alternatively you can view it as a blogpost through medium (still in draft). Hopefully this will at least inspire my fellow group members (or future group members) to use machine learning for their research. 

In this repo, I will use Abl kinase (PDB id: 1FPU), a type of tyrosine kinase. Tyrosine kinase is a fascinating class of protein with a longstanding history of being involved in cancer and recently it was uncovered that it might play a role in neurodegeneration. I have obtained the dataset via DUD-E (http://dude.docking.org/). 

## Prerequisites
To do this project properly:
- Tensorflow 1.x version
- Pandas
- Matplotlib
- Seaborn
- Deepchem
Optional:
- Google colab (I used google colab to connect to GPU)

## Files
In this repo, there are three files
- Deep Learning for the Virtual Screening.pdf: Here is my report for my project. 
- Exploratory Data Analysis for Abl Kinase Compounds.ipynb: The first step is EDA. I will have some comments in my .ipynb
- Training and Screening Compounds.ipynb: This is the second step where I train and screen compounds.

## Licensing, Authors and Acknowledgements
Please refer to this book for more guidance and if you are interested in applying your research:
@book{Ramsundar-et-al-2019,
    title={Deep Learning for the Life Sciences},
    author={Bharath Ramsundar and Peter Eastman and Patrick Walters and Vijay Pande and Karl Leswing and Zhenqin Wu},
    publisher={O'Reilly Media},
    note={\url{https://www.amazon.com/Deep-Learning-Life-Sciences-Microscopy/dp/1492039837}},
    year={2019}
}

They are useful for chemists and biologists who wants to learn more about deep learning and how it can be relevant to their research. 

Also, I would like acknowledge both http://dude.docking.org/ and https://zinc.docking.org/ for the dataset.

