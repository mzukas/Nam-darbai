# 0.1

Skaičiuojami ir įvedami mokiniai su jų pažymiais masyvų arba vektorių pagalbą. Pažymiai gali būti generuoti ranka arba atsitiktinai

# 0.2

Iš failo "ursiokai.txt", skaitomi duomenys - mokinių vardas, pavardė, pažymiai ir pažymys už egzaminą. Šie nuskaityti duomenys apdorojami
ir suskaičiuojamas galutinis mokinių vidurkis. Galima rinktis ar rodyti vidurkį pagal medianą, ar pagal aritmetinį vidurkį.

# 0.3

Reorganizuota 0.2 versija - kuriami atskiri antraštiniai failai "Headeris" ir "Duomenys". Duomenyse aprašytos funkcijos skaičiavimams,
"main.cpp" - funkcijų vykdymas.


# 0.4

Programoje sukuriami atsitiktinių duomenų failai pagal norima mokinių kiekį (int kiek) - "10.txt", "100.txt", "1000.txt", "10000.txt", 
"100000.txt". Šie duomenys surūšiuojami pagal galutinius pažymius į "galvočiai.txt" ir "nuskriaustukai.txt". Apskaičiuojamas laikas 
failų kūrimui.

# 0.5
Palyginami "vector", "deque" ir "list" konteinerių veikimo greičiai (kuriami 100000 mokinių failas):

List:

![](Nuotraukos/2019-05-23%2003_56_03-_D__MECHATRONIKA%20IR%20ROBOTIKA_C%2B%2B_0.4_list.exe_.png)

Vector:

![](Nuotraukos/2019-05-23%2003_57_54-0.4.png)

Deque:

![](Nuotraukos/2019-05-23%2003_56_33-deque.cpp%20-%20Code__Blocks%2017.12.png)


# 1.0

Palyginamos dvi strategijos - kuomet iš pagrindinio mokinių failo išrenkami "galvočiai" ir "nuskriaustukai", ir kuomet iš pagrindinio mokinių failo ištrinami "nuskriaustukai", paliekami "galvočiai", o į nuskriaustukai.txt rašomi <5 vidurkį turinčius mokinius.
