# Instalacja i uruchomienie jupytera

## Wymagania

- python3
- python3-virtualenv
- przeglądarka internetowa (Firefox, Chrome, Safari)

### Instalacja pythona i virtualenva

Pythona i virtualenva należy zainstalować z systemowego package managera. Np.:
```sh
sudo apt install python3 python3-virtualenv
```

Jeżeli virtualenva **nie ma** w systemowym package managerze, można go też zainstalować z pip-a:
```sh
sudo pip3 install --upgrade pip
sudo pip3 install --upgrade virtualenv
```


## Tworzenie i aktywowanie virtualenva

### Linux (bash lub zsh)

```sh
python3 -m venv venv --prompt jupyter-qiskit
source venv/bin/activate
```

### Inne powłoki i platformy (w tym Windows)

[https://docs.python.org/3/library/venv.html#creating-virtual-environments](https://docs.python.org/3/library/venv.html#creating-virtual-environments).


## Aktualizacja pip

```sh
pip install --upgrade pip
```


## Instalowanie zależności z pip

```sh
pip install --upgrade -r requirements.txt
```


## Uruchomienie jupytera

```sh
jupyter lab
```

Automagicznie powinna otworzyć się przeglądarka internetowa.
Jeśli nie, to trzeba otworzyć, w przeglądarce, jeden z linków wyświetlonych w konsoli przez jupytera.

W jupyter'rze należy zacząć od otworzenia notatnika `index.ipynb` z przeglądarki plików po lewej stronie.
Znajdują się tam dalsze instrukcje.


# Kontakt

Jeśli są jakieś problemy z instalacją, jupyterem lub dostarczonymi notatnikami można (a nawet trzeba) się ze mną skontaktować przez dowolny z poniższych kanałów:

#### Telegram
[@mrqubo](https://t.me/mrqubo)

#### Discord
MrQubo#2852

#### Email
[j.nowak26+www2020@student.uw.edu.pl](mailto:j.nowak26+www2020@student.uw.edu.pl)
