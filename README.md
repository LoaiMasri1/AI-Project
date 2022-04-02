# AI Project HighD
This Project to handle highD data files using Python.

## Dataset
To download dataset go to this link ```https://drive.google.com/drive/folders/1PDqVqxNq3ekttpFypI86jO9oenSw-bwf```

Please move the data file to the project file so that the program can read it  ```AI-Project/data```

## Run Locally

Clone the project

```bash
  git clone https://github.com/LoaiMasri1/AI-Project.git
```

Go to the project directory

```bash
  cd AI-Project
```

## Deployment
To deploy this project run
- install code editor i recommend (VS Code)
- install python from [here](https://www.python.org/)
- in this point we will use pandas library to read csv files [docs](https://pandas.pydata.org/docs/)
- you can download anaconda [Anaconda](https://www.anaconda.com)

## Initial Code
To read all csv files from data folder and store into data array
```bash
import pandas as pd

file_name=['01','02','03','04','06','08','14','39']
data=[]

for i in range(len(file_name)):
    data.append(pd.read_csv('../data/'+file_name[i]+'_tracks.csv'))


print(data[2].head())
```

## Guideline for submitting the task:

- Calculate Volatility Measures [here](https://drive.google.com/file/d/167nINsAEw9ecqup22pC7cWdkqVkFvoRV/view?usp=sharinghttps://drive.google.com/file/d/167nINsAEw9ecqup22pC7cWdkqVkFvoRV/view?usp=sharing)

- Using Python, read all the files that are labeled as "xx_tracks.csv" as one dataframe.

- reate 13 new columns in the dataframe for the Volatility measures. For each trackID (i.e., driver), you will need to use the equation provided in the above-mentioned uploaded file to find the 13 volatility measures.


## Important Site
- HighD Tools [here](https://github.com/RobertKrajewski/highD-dataset)
- File Format [here](https://www.highd-dataset.com/format)
