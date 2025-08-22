```python
import pandas as pd
```


```python
pd.read_csv(r"FarmersHHdata.csv", header = None)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>0</th>
      <th>1</th>
      <th>2</th>
      <th>3</th>
      <th>4</th>
      <th>5</th>
      <th>6</th>
      <th>7</th>
      <th>8</th>
      <th>9</th>
      <th>10</th>
      <th>11</th>
      <th>12</th>
      <th>13</th>
      <th>14</th>
      <th>15</th>
      <th>16</th>
      <th>17</th>
      <th>18</th>
      <th>19</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>year</td>
      <td>aez</td>
      <td>hybrid</td>
      <td>sex</td>
      <td>mar_stat</td>
      <td>age</td>
      <td>fam_exp</td>
      <td>educ_yrs</td>
      <td>hh_size</td>
      <td>maize_area_ha</td>
      <td>fert_use</td>
      <td>maize_qua_kh</td>
      <td>credit_acc</td>
      <td>acc_ext</td>
      <td>acc_ext_past</td>
      <td>max_2m_air_temp_yr</td>
      <td>precipitation_yr</td>
      <td>dis_market_min</td>
      <td>ext_km</td>
      <td>Admin_1</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2010</td>
      <td>Coastal Lowland</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>54</td>
      <td>5</td>
      <td>9</td>
      <td>10</td>
      <td>0.405000001</td>
      <td>0</td>
      <td>1111.111084</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>34.83562851</td>
      <td>907.3843994</td>
      <td>0</td>
      <td>0.5</td>
      <td>Mombasa</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2013</td>
      <td>Coastal Lowland</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>56</td>
      <td>7</td>
      <td>11</td>
      <td>10</td>
      <td>0.810000002</td>
      <td>0</td>
      <td>283.9506226</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>34.86555862</td>
      <td>709.0606079</td>
      <td>0</td>
      <td>0.5</td>
      <td>Mombasa</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2010</td>
      <td>Coastal Lowland</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>58</td>
      <td>8</td>
      <td>0</td>
      <td>6</td>
      <td>2.430000067</td>
      <td>0</td>
      <td>296.2962952</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>34.83562851</td>
      <td>907.3843994</td>
      <td>10</td>
      <td>7</td>
      <td>Mombasa</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2013</td>
      <td>Coastal Lowland</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>60</td>
      <td>10</td>
      <td>0</td>
      <td>11</td>
      <td>2.936249971</td>
      <td>0</td>
      <td>588.5057373</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>34.86555862</td>
      <td>709.0606079</td>
      <td>10</td>
      <td>7</td>
      <td>Mombasa</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>2193</th>
      <td>2013</td>
      <td>Moist mid altitudes</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>28</td>
      <td>10</td>
      <td>7</td>
      <td>6</td>
      <td>2.227499962</td>
      <td>1</td>
      <td>1131.31311</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>33.79806137</td>
      <td>1989.296265</td>
      <td>20</td>
      <td>10</td>
      <td>Busia</td>
    </tr>
    <tr>
      <th>2194</th>
      <td>2010</td>
      <td>Moist mid altitudes</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>31</td>
      <td>10</td>
      <td>5</td>
      <td>6</td>
      <td>0.506250024</td>
      <td>0</td>
      <td>533.333313</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>31.62660027</td>
      <td>1975.079956</td>
      <td>20</td>
      <td>7.59</td>
      <td>Busia</td>
    </tr>
    <tr>
      <th>2195</th>
      <td>2013</td>
      <td>Moist mid altitudes</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>44</td>
      <td>20</td>
      <td>2</td>
      <td>10</td>
      <td>3.24000001</td>
      <td>0</td>
      <td>916.666687</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>33.79806137</td>
      <td>1989.296265</td>
      <td>20</td>
      <td>7.59</td>
      <td>Busia</td>
    </tr>
    <tr>
      <th>2196</th>
      <td>2010</td>
      <td>Moist mid altitudes</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>26</td>
      <td>8</td>
      <td>4</td>
      <td>6</td>
      <td>1.417500019</td>
      <td>0</td>
      <td>349.2063293</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>31.62660027</td>
      <td>1975.079956</td>
      <td>5</td>
      <td>15</td>
      <td>Busia</td>
    </tr>
    <tr>
      <th>2197</th>
      <td>2013</td>
      <td>Moist mid altitudes</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>40</td>
      <td>14</td>
      <td>8</td>
      <td>8</td>
      <td>1.012500048</td>
      <td>0</td>
      <td>790.1234131</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>33.79806137</td>
      <td>1989.296265</td>
      <td>5</td>
      <td>15</td>
      <td>Busia</td>
    </tr>
  </tbody>
</table>
<p>2198 rows × 20 columns</p>
</div>




```python

```


```python

```


```python
#import pandas in Jupiter Notebook environment:
import pandas
```


```python
dataset = pandas.read_excel("weather.xlsx")
```


```python
#Check the Head:
dataset.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>MinTemp</th>
      <th>MaxTemp</th>
      <th>Rainfall</th>
      <th>Evaporation</th>
      <th>Sunshine</th>
      <th>WindGustDir</th>
      <th>WindGustSpeed</th>
      <th>WindDir9am</th>
      <th>WindDir3pm</th>
      <th>WindSpeed9am</th>
      <th>...</th>
      <th>Humidity3pm</th>
      <th>Pressure9am</th>
      <th>Pressure3pm</th>
      <th>Cloud9am</th>
      <th>Cloud3pm</th>
      <th>Temp9am</th>
      <th>Temp3pm</th>
      <th>RainToday</th>
      <th>RISK_MM</th>
      <th>RainTomorrow</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>8.0</td>
      <td>24.3</td>
      <td>0.0</td>
      <td>3.4</td>
      <td>6.3</td>
      <td>NW</td>
      <td>30.0</td>
      <td>SW</td>
      <td>NW</td>
      <td>6.0</td>
      <td>...</td>
      <td>29</td>
      <td>1019.7</td>
      <td>1015.0</td>
      <td>7</td>
      <td>7</td>
      <td>14.4</td>
      <td>23.6</td>
      <td>No</td>
      <td>3.6</td>
      <td>Yes</td>
    </tr>
    <tr>
      <th>1</th>
      <td>14.0</td>
      <td>26.9</td>
      <td>3.6</td>
      <td>4.4</td>
      <td>9.7</td>
      <td>ENE</td>
      <td>39.0</td>
      <td>E</td>
      <td>W</td>
      <td>4.0</td>
      <td>...</td>
      <td>36</td>
      <td>1012.4</td>
      <td>1008.4</td>
      <td>5</td>
      <td>3</td>
      <td>17.5</td>
      <td>25.7</td>
      <td>Yes</td>
      <td>3.6</td>
      <td>Yes</td>
    </tr>
    <tr>
      <th>2</th>
      <td>13.7</td>
      <td>23.4</td>
      <td>3.6</td>
      <td>5.8</td>
      <td>3.3</td>
      <td>NW</td>
      <td>85.0</td>
      <td>N</td>
      <td>NNE</td>
      <td>6.0</td>
      <td>...</td>
      <td>69</td>
      <td>1009.5</td>
      <td>1007.2</td>
      <td>8</td>
      <td>7</td>
      <td>15.4</td>
      <td>20.2</td>
      <td>Yes</td>
      <td>39.8</td>
      <td>Yes</td>
    </tr>
    <tr>
      <th>3</th>
      <td>13.3</td>
      <td>15.5</td>
      <td>39.8</td>
      <td>7.2</td>
      <td>9.1</td>
      <td>NW</td>
      <td>54.0</td>
      <td>WNW</td>
      <td>W</td>
      <td>30.0</td>
      <td>...</td>
      <td>56</td>
      <td>1005.5</td>
      <td>1007.0</td>
      <td>2</td>
      <td>7</td>
      <td>13.5</td>
      <td>14.1</td>
      <td>Yes</td>
      <td>2.8</td>
      <td>Yes</td>
    </tr>
    <tr>
      <th>4</th>
      <td>7.6</td>
      <td>16.1</td>
      <td>2.8</td>
      <td>5.6</td>
      <td>10.6</td>
      <td>SSE</td>
      <td>50.0</td>
      <td>SSE</td>
      <td>ESE</td>
      <td>20.0</td>
      <td>...</td>
      <td>49</td>
      <td>1018.3</td>
      <td>1018.5</td>
      <td>7</td>
      <td>7</td>
      <td>11.1</td>
      <td>15.4</td>
      <td>Yes</td>
      <td>0.0</td>
      <td>No</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 22 columns</p>
</div>



#Check the tail:
dataset.tail(5)


```python

```
