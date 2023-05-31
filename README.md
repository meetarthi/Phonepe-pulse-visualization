# Phonepe-pulse-visualization app #

[Link to access the app](https://meetarthi-phonepe-pulse-visualization-phonepe-25s9rd.streamlit.app/)

[Dataset link](https://github.com/PhonePe/pulse#readme)

**Overview**
------------
Phonepe pulse visualization app is a application that provides valuable insights and analysis of data from the PhonePe digital payment platform. This app contains visualizations for better understanding of payment categories, transaction patterns, user activity, and top locations.


**Developed using:**
------------
1. **Language** - Python 

2. **Libraries** - Pandas(Dataframe) , Matplotlib(Chart), Plotly(Graph and charts), geopandas(Map)

3. **Front-end/GUI** - Streamlit


**Home Page**
------------
![Screenshot from 2023-05-31 17-24-53](https://github.com/meetarthi/Phonepe-pulse-visualization/assets/112666126/2417ebc4-292b-4ac4-8ed3-53aaad0b2014)


**Side bar**
------------
-
![Screenshot from 2023-05-31 17-36-53](https://github.com/meetarthi/Phonepe-pulse-visualization/assets/112666126/3ec15aef-b24a-4d78-96ec-a94286ffbb4d)


------------
**Payment category Analysis Page**
------------
![Screenshot from 2023-05-31 17-40-53](https://github.com/meetarthi/Phonepe-pulse-visualization/assets/112666126/9e8baba8-fd26-4495-ac66-25c8ce44af9a)
![Screenshot from 2023-05-31 18-45-16](https://github.com/meetarthi/Phonepe-pulse-visualization/assets/112666126/300d5f41-3cec-474d-b680-b4303aad3fb8)


1. The user is supposed to choose either India or any of the states from the dropdown, select the year and type of transaction category.
2. Based on user input, Bar graph is generated.

------------
**Map Transaction Analysis Page**
------------
![Screenshot from 2023-05-31 18-48-41](https://github.com/meetarthi/Phonepe-pulse-visualization/assets/112666126/126043c5-4ce6-497a-bbb6-d721290b1344)
![Screenshot from 2023-05-31 18-52-20](https://github.com/meetarthi/Phonepe-pulse-visualization/assets/112666126/46e23d79-44fb-43d6-9bdd-9c20b6d07c1a)


1. The user is supposed to choose either India or any of the states from the dropdown, select the year.
2. Based on user input, Map is generated with spots on specific locations(if the input is **India** the spots are on the states, if the input is **states** the spots are on the districts), which gives information on total transaction and total transaction value.


------------
**User Activity Page**
------------
![Screenshot from 2023-05-31 19-10-06](https://github.com/meetarthi/Phonepe-pulse-visualization/assets/112666126/88c04a0c-f616-44d2-9683-2ee05a977142)
![Screenshot from 2023-05-31 19-26-30](https://github.com/meetarthi/Phonepe-pulse-visualization/assets/112666126/2664afc0-3272-4892-bd5e-137266d8eec2)



1. The user is supposed to choose either India or any of the states from the dropdown, select the year.
2. Based on user input,Time series graph is generated. On hovering over the peaks corresponding to the locations, the registered users count and app open counts are shown.

------------
**Top Locations based on Transaction data Page**
------------
