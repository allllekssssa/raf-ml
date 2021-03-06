# 1. Instalacija Python-a

Instalacija programskog jezika Python (verzija mora biti najmanje 3.* ali ne 3.7+ i namenjena za 64-bitnu arhitekturu) i virtuelnog okruženja.

## Windows

1. Skinite instalaciju za npr. Python 3.6 klikom na [link][1] i prilikom instalacije čekirajte `Add Python 3.6 to PATH`. Zatim pokrenite `cmd.exe` i unesite sledeću komandu:

	`pip install virtualenv`

## Linux
1. Linux sistemi uglavnom dolaze sa instaliranim Python-om, ukoliko nemate Python neophodno je da ga instalirate korišćenjem nekog od paket menadžera ili skidanjem instalera sa oficijalnog sajta. Nakon toga pokrenite sledeću komandu:

  	`sudo pip3 install virtualenv `

## Mac OS
1. Isto važi kao i za instalaciju Python-a za sisteme sa Linux-om. Nakon uspešne instalacije pokrenite:

	`easy_install virtualenv`

[1]: https://www.python.org/ftp/python/3.6.4/python-3.6.4-amd64.exe


# 2. Materijali i instalacija neophodnih paketa

Izaberite željenu putanju na vašem sistemu gde želite da skinete materijale za vežbe (PATH).

1. Materijale možete skinuti klikom na zeleno dugme 'Clone or download'.

2.  Otvorite command-line interface (CLI) i pokrenite sledeće komande:

3. `cd PATH/raf-ml`

4. `virtualenv env`

5. `source env/bin/activate`

	Za Windows korisnike: `env\Scripts\activate`

6. `pip install -r requirements.txt`

# 3. Pokretanje

Kada ste uspešno skinuli projekat (PATH je putanja do foldera koji ste skinuli) i instalirali neophodne pakete pri svakom sledećem radu projekat se pokreće na sledeći način:

1. Lociranje projektnog foldera:

	`cd PATH/raf-ml`

2. Aktivacija virtuelnog okruženja:

	`source env/bin/activate`

	Za Windows korisnike: `env\Scripts\activate`

3. Pokretanje Jupyter Notebook:

	`jupyter notebook`
