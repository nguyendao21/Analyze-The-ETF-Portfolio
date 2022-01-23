# Analyze-The-ETF-Portfolio

Using SQL, Python and the Voila librabry to analyze the performance of a hypothentical fintech ETF. This application analyze fintech ETF that consists of four stocks: GOST, GS, PYPL, and SQ. First, analyze the daily returns of the ETF stocks both individually and as a whole, then deploy the visualizations to a web application by using Voila librabry. 

---

## Technologies

This project leverages [python](https://www.python.org/) 3.7 with the pandas library. Also, using [Jupyter notebook](https://jupyter.org/) in order to organize the code frame.

---

## Usage

To use this application, simply clone the repository and open jupyter lab from git bash by running the following command:

```jupyter lab```

After launching the application, navigate ``etf_analyzer.ipynb`` notebook in the repository. 

Then in your Jupyter notebook, import the required libraries and dependencies.

```
import numpy as np
import pandas as pd
import hvplot.pandas
import sqlalchemy

```

To use Voila library to deploy notebook to a web application, type this code: 

```
voila etf_analyzer.ipynb

```


### *Example*

*An Intereactive visulization of Daily Return for PYPL * 

![Daily_Returns_PYPL](https://user-images.githubusercontent.com/94591580/150664367-eda3c488-2ff4-46ba-b422-8222e45d135b.png)



*An Intereactive visulization of Cumulative Return for PYPL*


![Cumulative_Return_PYPL](https://user-images.githubusercontent.com/94591580/150664375-792f39ec-9076-4517-9d88-97218b687c72.png)

*An Intereactive visulization of Cumulative Return for ETF*

![ETF_Cumulative_Return](https://user-images.githubusercontent.com/94591580/150664381-d706c21e-290a-410c-8695-18af2a94f406.png)
---

## Contributors

[Nguyen Dao](https://www.linkedin.com/in/nguyen-dao-a55669215/)

daosynguyen21@gmail.com


---

## License

MIT
