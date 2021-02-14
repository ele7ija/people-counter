# Predefinisani projekat 3
Autor: Bojan Poprzen / SW16-2017

## Opis
Skup podataka nad kojim treba da odradite zadatak se nalazi na sledećem [linku](https://drive.google.com/drive/folders/1nQ5P2YorlLZ8wD1BiuzosQET_1ElDOWd).
Video zapis sadrži plato braon boje i ljude koji se kreću.
Izvršiti prebrojavanje ljudi koji se u barem jednom trenutku nađu na platou.
`res.txt` sadrži tačno rešenje za svaki video zapis.
Kreirati rešenje koje će ostvariti najmanji mean absolute error (MAE).
Za najviše 50 bodova (ocena 8) je potrebno postići MAE < 4.6.

## Poster

Poster se nalazi [ovde](./poster.pdf).

## Pokretanje
Klonirati ovaj projekat. Pozicionirati se u koren projekta.

Instalirati python 3.6.x

Kreirati novo virtuelno okruzenje naredbom:
> `$ virtualenv env`

Aktivirati okruzenje:
> `$ source env/bin/activate`

**Instalirati potrebne pakete**:
> `$ pip install -r requirements.txt`

**Pokrenuti projekat**:
> `$ jupyter notebook` i otvoriti `people_counter.ipynb`
