# TimeSeries Analysis

### **Objective**
Forecasting foreign tourists’ arrivals in Indonesia.

### **Problem Statement**
As the largest archipelagic nation, Indonesia has a lot of cultures and national parks that can be utilized to improve the economy of Indonesia. Bali, Yogyakarta, Labuan Bajo, and Lombok are one of many regions in Indonesia that has a lot of foreign tourists, and many local people are dependent on tourism sector. The Government set a road map to reinvigorate Indonesia’s tourism sector as Indonesia’s [new source of economic growth](https://tasransel.kemenparekraf.go.id/outlook-pariwisata-dan-ekonomi-kreatif-2023-2024/show). In addition, foreign tourists also potentially can increase foreign reserve in Indonesia. 

### **Data Source**
[Statistics Indonesia (Badan Pusat Statistik)](https://www.bps.go.id/subject/16/pariwisata.html#subjekViewTab1)

### **Data Description**
<!---The data of foreign tourism (tourists) is a monthly time series from January 1979 to August 2023. Statistics Indonesia defined the tourist data as inbound tourists arriving in Indonesia by mode of transportation. They also defined tourist as any person taking a trip to a main destination outside his/her usual environment, staying at least 24 hours, but not more than 12 (twelve) months, for any main purpose (business, leisure, or other personal purpose) other than to be employed by a resident entity in the country visited. -->

<!---This series (Figure 1) has several main features:
- Trend pattern: long-term exponential increase in the data since January 1979 until before COVID-19 and right after COVID-19.
- Structural break: Tourists arrival in Indonesia dropped significantly as the whole world restricted people’s mobility.
- Seasonal pattern: rise and fall with a fixed and known period (rise during holiday season/ summer and winter period)-->

<a href="https://ibb.co/McStrsb"><img src="https://i.ibb.co/Cb8Ygzq/Data-Description.png" alt="Data-Description" border="0" /></a>

### **Exploratory Data Analysis**
#### **Seasonality**
<a href="https://ibb.co/qFWPqt0"><img src="https://i.ibb.co/4gY5v6s/seasonality.png" alt="seasonality" border="0" /></a>

#### **Normality**
<a href="https://ibb.co/N1MM0fy"><img src="https://i.ibb.co/7gqq3B1/normality.png" alt="normality" border="0" /></a>

#### **Stationarity**
<a href="https://ibb.co/yYKL0gh"><img src="https://i.ibb.co/pRNC24W/stationarity.png" alt="stationarity" border="0" /></a>
<a href="https://ibb.co/TWJm2f1"><img src="https://i.ibb.co/SfHRyjc/stationarity2.png" alt="stationarity2" border="0" /></a>

#### **Correlation**
<a href="https://ibb.co/HVrbBFC"><img src="https://i.ibb.co/px3Mb0Q/correlation.png" alt="correlation" border="0" /></a>
<a href="https://ibb.co/Pg3YNVc"><img src="https://i.ibb.co/QMzcfxP/correlation2.png" alt="correlation2" border="0" /></a>

### **Model Exploration**
#### **Exponential Smoothing (ETS)**
<a href="https://ibb.co/sRfPTcC"><img src="https://i.ibb.co/zxM53CF/ets.png" alt="ets" border="0" /></a>
<a href="https://ibb.co/ZWBLw7j"><img src="https://i.ibb.co/yW6fM79/ets2.png" alt="ets2" border="0" /></a>
<a href="https://ibb.co/b3BgqzR"><img src="https://i.ibb.co/fSpYB4G/ets3.png" alt="ets3" border="0" /></a>

#### **SARIMA**
<a href="https://ibb.co/R91Nbts"><img src="https://i.ibb.co/s2hCRcN/sarima.png" alt="sarima" border="0" /></a>
<a href="https://ibb.co/qnhbdQW"><img src="https://i.ibb.co/PYJBNH9/sarima2.png" alt="sarima2" border="0" /></a>

<!--#### **Regression with SARIMA error**
<a href="https://ibb.co/8PDYmm5"><img src="https://i.ibb.co/VMWwLLS/sarima-error.png" alt="sarima-error" border="0" /></a>
<a href="https://ibb.co/VJsHXxC"><img src="https://i.ibb.co/k5t3YJD/sarima-error2.png" alt="sarima-error2" border="0" /></a>-->

#### **Vector Auto Regression (VAR)**
<a href="https://ibb.co/pJXGz4w"><img src="https://i.ibb.co/zGfjRPx/var.png" alt="var" border="0" /></a>
<a href="https://ibb.co/N7jhR8L"><img src="https://i.ibb.co/t3sfR7b/var2.png" alt="var2" border="0" /></a>

<!--#### **TBATS**
<a href="https://ibb.co/Njq2V53"><img src="https://i.ibb.co/4TLRmzf/tbats.png" alt="tbats" border="0" /></a>
<a href="https://ibb.co/vwHQdFV"><img src="https://i.ibb.co/Bztr6pc/tbats2.png" alt="tbats2" border="0" /></a>

#### **Intervention Analysis**
<a href="https://ibb.co/XYyVbP9"><img src="https://i.ibb.co/y4hVXCD/int.png" alt="int" border="0" /></a>
<a href="https://ibb.co/f4LMs43"><img src="https://i.ibb.co/syzjZyT/int2.png" alt="int2" border="0" /></a>-->


<!--### **Conclusion**
<a href="https://ibb.co/ZGKgCyr"><img src="https://i.ibb.co/q79gwb8/conclusion.png" alt="conclusion" border="0" /></a>-->

### **Recommendation**
<a href="https://ibb.co/gWLCbpQ"><img src="https://i.ibb.co/YdFG4MJ/recommendation.png" alt="recommendation" border="0" /></a>
