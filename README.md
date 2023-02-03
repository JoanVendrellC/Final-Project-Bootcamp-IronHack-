![Main_picture](https://user-images.githubusercontent.com/117674807/216674212-1e006346-f709-4e7e-9a00-4d143af48da3.png)


# Cyclists involved in traffic crashes in Catalonia (Spain)

Every year in catalonia more than hundred cyclists is involved in traffic crash and some of them suffer serious health consequences and even die.
So, using my skills as a Data Analytics, I analized in what time (per years, months, weekdays even per hours) there are more accidents against cyclists.
Moreover, I tried to create a model to predict with acceptable accuracy the accidents per weekday and per hour.

That is my final project in the Data Analyst bootcamp but it is also my personal project as cyclist.

![logo](https://user-images.githubusercontent.com/117674807/216676289-0eedbb0a-5305-4e73-917f-621f0afa524f.png)


## Acknowledgements

Bootcamp's teachers: Jan, Queen Erin & Simao.
My bootcamp's colleague Matias.


## Authors: Joan Vendrell

![matricula](https://user-images.githubusercontent.com/117674807/216687714-f67494d1-6ace-48e4-9a22-8517669509c8.png)



## Data source

Main data --> **Accidents** --> https://analisi.transparenciacatalunya.cat/Transport/Accidents-de-tr-nsit-amb-morts-o-ferits-greus-a-Ca/rmgc-ncpb

Second data --> **Licences** --> https://www.idescat.cat/indicadors/?id=aec&n=15786&t=202100


## Features in data

zona = Urban Zone or in road

via = name of the road

pk = Kilometric point

nommun = town name

nomcom = local region name

nomdem = province name

f_morts = number of deaths

f_ferits_greus = number of serious injured

f_ferits_lleus = number of non serious injured

f_unitats_implicades = number of units involved

f_vianants_implicades = number of pedestrian involved

f_bicicletes_implicades = number of cyclists involved

f_ciclomotors_implicades = number of pedestrian involved

f_motocicletes_implicades = number of motorbike involved

f_veh_lleugers_implicades = number of cars involved

f_veh_pesants_implicades = number of trucks/Van involved

f_altres_unit_implicades = number of other units involved

c_velocitat_via = speed road

d_acc_amb_fuga = accident with scaping

d_boira = foggy day

d_caract_entorn = environment feature

d_carril_especial = special lane

d_circulacio_mesures_esp = special traffic measures

d_climatologia = climatology

d_func_esp_via = special road

d_gravetat = seriousness 

d_influit_boira = fog influenced

d_influit_caract_entorn = environment feature influenced

d_influit_circulacio = traffic influenced

d_influit_estat_clima = weather influenced

d_influit_inten_vent = wind influenced

d_influit_lluminositat = brightness influenced

d_influit_mesu_esp = special measures influenced

d_influit_obj_calcada = object on road influenced

d_influit_solcs_rases = sunrises influenced

d_influit_visibilitat = visibility influenced

d_inter_seccio = road intersection

d_limit_velocitat = speed limit

d_lluminositat = brightness

d_regulacio_prioritat = priority traffic regulation

d_sentits_via = road ways

d_subtipus_accident = accident subtypes

d_subtipus_tram = road subtypes

d_subzona = zone subtypes

d_superficie = surface

d_tipus_via = road types

d_titularitat_via = road owner

d_tracat_altimetric = altimetry road

d_vent = wind

grupdialab = weekday group

hor = hour

gruphor = hour group

tipacc = accident types

data = date


## Folders list

1. **Raw data & Jupyter Notebooks.** In this folder you can see the raw data and the jupyter notebooks for cleaning the data. In this case, there are three different jupyter notebook. The first one is a cleaning data with categorized way. The second one is less categorized than the first one. The third is the same than the second one but is changed a little bit for using on Tableau. Finally, there is another file for scraping the secondary dataset (licences).

2. **Cleaned datasets and model predictions.** Firstly, there are the cleaned main dataset, split it in less & more categorized. An the othere hand, there are several models with predictions. The number 01 and 02 is modelling with all data but with a imbalanced target to get predictions. The 03, 04 and 05 are models sorted the all data by "f_bicicletes_implicades = number of cyclists involved" and try to make predictions by hour crash, laborday or weekend and finally by weekday.

3. **Data for Tableau.** There are the csv files (accidents & licences) that were used to create the plots for the presentation. 

4. **Presentation.** There is the powerpoint presentation and the picture of the front page.




## Tableau

https://public.tableau.com/app/profile/joan7023/viz/FinalProject_IronHack/TotalBikesinvolvedperyear?publish=yes


## Feedback

If you have any feedback, please reach out to us at github profile https://github.com/JoanVendrellC


## 🚀 About Me
I'm a Data Analyst as a good curious of the data.


## Linkedin

[![linkedin](https://www.linkedin.com/in/joan-vendrell-carbonell-94846545/)](https://www.linkedin.com/)


## 🛠 Skills
Python | MySQL | Scikit-Learn | SciPy | Pandas | Tableau | Machine Learning 


## License

Free Distribution as a student project.

