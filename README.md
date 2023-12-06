Link where the file on nationwide insecurity was obtained: https://www.gob.mx/sesnsp/acciones-y-programas/datos-abiertos-de-incidencia-delictiva?state=published, from where the following link was retrieved: https://drive.google.com/file/d/1PslWCPehm2_Z8au2HLeJzc3JCsqrSC7Q/view# Data Analysis - Jalisco's Voter Registry and Perceived Crime Index


![Bandera-Catedra-Jalisco](https://github.com/GRP-777/Data_Analysis-Jalisco-Lista_nominal-Indice_percepcion_delictiva/assets/132501854/8fffe571-d54a-4427-9221-b67f3c2ac462)



### Objective:

Assessing synthesis, clarity, and organization of ideas, as well as understanding of the Mexican political and security system and the formulation of evidence-based conclusions.



### Contents:

- Data Files: Includes the Jalisco voter registry data and perceived crime index.
- Scripts: Contains the Python code used for data extraction, analysis, and map visualization.
- Visualizations: Displays the generated maps showcasing the percentage of young voters and the top 5 municipalities.
- Feel free to explore, contribute, or utilize the provided resources for your own analysis purposes.

The code and data files included in this repository enable replication of the analysis and serve as a resource for further exploration or refinement of the presented visualizations.



## Voters Registry

The voter registry analysis includes the extraction of the nominal voter list by municipality in Jalisco, followed by the creation of a map displaying the percentage of young voters aged between 18 and 30 years old in relation to the total voter registry for each municipality. Additionally, the top 5 municipalities with the highest percentage of young voters are highlighted on the map for easy identification.

The aim of this project is to provide a visual representation of the distribution of young voters across different municipalities in Jalisco, shedding light on the demographic composition of the voter registry.

**Data provider**
Access to the databases (data by age ranges, cutoff on November 9, 2023):
https://www.ine.mx/transparencia/datos-abiertos/#/archivo/datos-por-rangos-de-edad-entidad-de-origen-y-sexo-del-padron-electoral-y-lista-nominal-2023

Screenshot of the Power BI dashboard:

![image](https://github.com/GRP-777/Data_Analysis-Jalisco-Lista_nominal-Indice_percepcion_delictiva/assets/132501854/9bfc2d70-6347-4e46-a2d6-5fd55e6f4ed8)

Also, as a support, a table with the numeric and string data:

![image](https://github.com/GRP-777/Data_Analysis-Jalisco-Lista_nominal-Indice_percepcion_delictiva/assets/132501854/ff013d00-fa7f-48cb-a50b-1c8e8f9759ed)

**Conclusions:**

The map displays municipalities with the highest percentage of young individuals registered in the voter registry. They are indicated in blue, with larger bubbles representing higher percentages. As the percentage decreases, the color changes to yellow or red, accompanied by smaller bubble sizes. Additionally, below the map, there's a list indicating the count of registered young individuals, the total count of youth, and the overall registered population regardless of age. The age reference was set up to 29 years old due to the mixing of individuals aged 30 with those aged 35 in the age groups 25-29 and 30-35.



## Perceived crime index

One of the constant topics in the media is the poor performance of the current administration in terms of security. This statement has been echoed by some to describe the security situation in Jalisco.

Given this context, both the federal and Jalisco governments have focused on taking actions and primarily basing their results on two indicators: the perception of security and the crime incidence.

**Data providers**

Link where the files were obtained: https://www.inegi.org.mx/programas/ensu/#datos_abiertos

As a reference for the perception of insecurity in each city, the column (BP1_1) titled 'Perception of security in the city on the website' was used, as listed in the data dictionary: https://www.inegi.org.mx/rnm/index.php/catalog/859/data-dictionary/F11?file_name=ENSU_CB_0923

Link where the file on nationwide actual insecurity was obtained: https://www.gob.mx/sesnsp/acciones-y-programas/datos-abiertos-de-incidencia-delictiva?state=published, from where the following link was retrieved: https://drive.google.com/file/d/1PslWCPehm2_Z8au2HLeJzc3JCsqrSC7Q/view


### **Using the tabulations or microdata from the National Survey on Urban Public Security (ENSU):**
### **a. How has the perception of insecurity evolved nationally and in Jalisco since the first quarter of 2018? How do they compare?**

![image](https://github.com/GRP-777/Data_Analysis-Jalisco-Lista_nominal-Indice_percepcion_delictiva/assets/132501854/c09eedbd-82ec-4fef-b683-ccb2f0657f00)

The perception of insecurity in the country has continued to rise. While Jalisco's perception decreased in the last years of the previous decade, it began to rise again from 2020 onwards. However, when comparing them, it's evident that Jalisco's perception of insecurity is lower and maintains a less pronounced upward trend. This indicates that the perception of insecurity in Jalisco is indeed increasing, albeit less sharply than at the national level.


### **Using data on common crime incidence from the Executive Secretariat of the National Public Security System (SESNSP):**
### **a. How has the common crime incidence evolved since 2018 at the national level and in Jalisco?**

![image](https://github.com/GRP-777/Data_Analysis-Jalisco-Lista_nominal-Indice_percepcion_delictiva/assets/132501854/b8dfe13d-9bd4-4f50-b1bf-836a70e622f5)


In the country, there has been a constant rise, only interrupted by a sharp drop in 2020, likely due to the Covid-19 pandemic. Following that, it resumed its upward trend, and in 2022 and 2023, it remained steady without increases or decreases.

For Jalisco, it was also on the rise until 2018, where it started to moderately decline. Then, in 2019, it dropped more significantly until it reached its lowest point in 2020. Since that year, it has maintained a similar consistency without increasing over time.


### Considering the obtained results:
### **a. Would you say there's a relationship between perception and crime incidence? What causal mechanism better explains the relationship or lack thereof between these variables?**

There is indeed a relationship between perception and incidence because people form opinions based on what they see, but they are also influenced by what they hear or are informed about by third parties. While their opinions are grounded in firsthand experiences, they also have a real or imagined construction from indirect sources.

Depending on these indirect sources, the reputation or perception of security in the state can be altered for better or for worse. That's why it's important to be mindful of how we communicate with people, ensuring they are well-informed.


### **b. What recommendation would you give to the Government of Jalisco to improve the perception of insecurity in the state?**

Creating comprehensive campaigns that reflect the state's condition involves utilizing a wider array of media outlets and innovative methods of information dissemination. By informing in new ways, we can reach audiences who might not have well-formed opinions through traditional channels, thereby altering their perceptions.

A specific proposal involves showcasing real-time data analysis through official media channels and locations. This allows people to witness how information is being modified. While there is undeniable insecurity in Jalisco, it's crucial to accurately reflect the actual situation. Therefore, it's important to mention serious incidents without sensationalizing them. This approach acknowledges the government's recognition of weaknesses without allowing incidents to become unrealistically amplified in the news.



### Tech stack:
- Python
- Power BI
- pandas
- dbfread
- os
- matplotlib.pyplot
- seaborn
- import warnings



### Professional contact

- [LinkedIn](https://www.linkedin.com/in/german-robles-perez/)
- Email: grbolesperez0@gmail.com
