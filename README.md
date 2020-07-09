## Data description

* ### peak wave height
  - This is the maximum significance crest prediction problem using the observations of the Ocean Data Buoy report.<br>
    The Ocean Data Buoy observes marine weather phenomena with various weather equipment at sea level.
    Depending on the shape, there are two types, ship type and disk type, and Pagoe and Paegui measure and analyze the moving acceleration of the buoyant body at sea level.
    For the Train data, it consists of daily data from 2014 to 2018, so you can study it to predict test data.
    The marine weatherman used the data from Ulleungdo Island.
   
  - <b>Data summary</b><br>
    point, date, average wind speed (m/s), average air pressure (hPa), average relative humidity (%), average temperature (°C), average water temperature (°C), average maximum       wave height(m), average significant wave height (m), maximum wave height (m), average wave period (sec), max wave period (sec), max significant wave height(m)
    
    
  - significant wave height: The average of the crests observed during the arbitrary observation time, corresponding to one-third of the total, in the order in which the wave       heights are high.
    Maximum wave height: The largest wave height observed during the arbitrary observation time.<br>
    Mean wave height: Mean crest of the observed wave height during the arbitrary observation time.<br>
    
  - [data source](https://data.kma.go.kr/data/sea/selectBuoyRltmList.do?pgmNo=52&tabNo=1)
  
  - [source code](https://github.com/Yeonwoo-Kim/Pytorch/blob/master/script/peak_wave_height.ipynb)

* ### sea ice extent
  <img src="https://user-images.githubusercontent.com/50096655/87002337-562a1180-c1f4-11ea-98b5-545b38489298.gif" width="300" height ="300">

  - Every summer, let's look at the magnitude of sea ice due to the ongoing emissions of carbon dioxide and the unusual factors of carbon dioxide, the gases that contribute to       the greenhouse effect. There are many factors in carbon dioxide emissions. We've talked about one of the interesting cases that. It is given from 1978 to 1919, when 2016 was     omitted, and every year there is data from January to December.
  
  - <b>Data summary</b><br>
    year : (int64)<br>
    month : (int64)<br>
    car_reg : number of car registrations (float64)<br>
    cow : the number of cow in the world (float64)<br>
    gdp_ : average amount of GDP (float64)<br>
    Carbon : Carbon emissions (remove number of linearity,seasonality) (float64)<br>
    seaice_extent : sea ice size (float64)

  - data source
    - [car_reg](http://www.index.go.kr/potal/main/EachDtlPageDetail.do?idx_cd=1257)
    - [cow](http://www.fao.org/faostat/en/#data/QL)
    - [gdp](https://data.oecd.org/gdp/gross-domestic-product-gdp.htm)
    - [Carbon](https://www.kaggle.com/ucsandiego/carbon-dioxide?select=archive.csv)
    - [seaice_extent](https://www.kaggle.com/nsidcorg/daily-sea-ice-extent-data)
    
  - [source code](https://github.com/Yeonwoo-Kim/Pytorch/blob/master/script/ice_extent.ipynb)



* ### breast cancer diagnosis

  - <b>Data summary</b><br>
    *The results of the test
    diagnosis(Benign tomor = 0 / Malignant tumor = 1)<br>

    *test results for diagnosing breast cancer<br>
   radius_mean,texture_mean,perimeter_mean,area_mean,smoothness_mean,compactness_mean,concavity_mean,concave,points_mean,symmetry_mean,fractal_dimension_mean,radius_se,texture_se,perimeter_se,area_se,smoothness_se,compactness_se,concavity_se,concave points_se,symmetry_se,fractal_dimension_se,radius_worst,texture_worst,perimeter_worst,area_worst,smoothness_worst,compactness_worst,concavity_worst,concave points_worst,symmetry_worst,fractal_dimension_worst
  
  - [source code](https://github.com/Yeonwoo-Kim/Pytorch/blob/master/script/breast_cancer.ipynb)
   

* ### Boston Housing Price

  - <b>Data summary</b><br>

  - [source code]()

* ### cabbage_price
  
  - <b>Data summary</b><br>
  
  - [source code]()

* ### diabetes diagnosis
  - <b>Data summary</b><br>
  
  - [source code]()

* ### Animal Classification

  - [source code]()

* ### Danyang Water quality of sewage
  - Estimate the number of E. coli in water quality using discharge water data at Danyang Sewage Treatment Plant.<br>
  
  - <b>Data summary</b><br>
    outflow (방류량), temp 수온(℃), 방류수질(pH(-)), 방류수질(BOD(㎎/L)), 방류수질(COD(㎎/L)), 방류수질(SS(㎎/L)), 방류수질(T-N(㎎/L)), 방류수질(T-P(㎎/L)), Escherichia coli(개/㎖)
  
  - [data source](https://www.data.go.kr/data/15053866/fileData.do)
  
  - [source code](https://github.com/Yeonwoo-Kim/Pytorch/blob/master/script/water_quality.ipynb)



