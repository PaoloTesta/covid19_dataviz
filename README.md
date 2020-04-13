# covid19_dataviz
Data Viz of COVID 19 in Italy

## Data: 
1. to get **Protezione Civile** CoViD 19 related data, execute from project directory:  

`git clone https://github.com/pcm-dpc/COVID-19.git`  
  
If you have already cloned it and you want just to get updated data, just pull the same github repo:  

`git pull origin master` 

2. data of whole recorded deaths in Italy by **ISTAT** are avialble [here](https://www.istat.it/it/files//2020/03/comune-giorno.zip).  

you can download it by running in project directory bash command:
`curl -O https://www.istat.it/it/files//2020/03/comune-giorno.zip | unzip comune-giorno.zip`


## Notebooks:  

**dataviz_lombardia.ipynb**: descriptive plots of CoViD related statistics with a focus on Lombardia Italian Region.  

