## Classificatore di Cifre | Number classifier MNIST
* [Informazioni generali](#informazioni-generali)
* [Tecnologie](#tecnologie)
* [Setup](#setup)

## Informazioni generali
Questo progetto è un classificartore di immagini rappresentanti cifre numeriche, ed è in grado di predirre l'effettivo valore intero. Attraverso una GUI è possibile scrivere sulla finestra un numero e  effettuare una predizione.
	
## Tecnologie
Nel progetto ho implementato diversi tipi di algoritmi AI per cercarche il più performante sulla base dei nostri dati
* SGDClassifier
* Support Vector Classification SVC
* KNeighborsClassifier
* Convolutional Neural Network
```
Model: Sequential
Layers:
	Dense - Layer dense per l'output
	Conv2D - Layer convoluzionale
	MaxPool2D - Pulling riduzione immagine Max
	Flatten - Reshape input su una dimensione
	Dropout - Regularization, evito overfitting eliminando connessioni tra i neuroni

Il dataset uitilizzato è il MNIST un database di cifre scritte a mano.

Interfaccia grafica Tkiter per disegnare un numero su un foglio vuoto e farlo predirre al modello desiderato.
```

## Setup
Per eseguire il progetto creare una variabile virtuale di seguito utilizzo anaconda promt

```
$ conda create --name=env_name python=3.8
$ conda activate env_name
$ conda install -c anaconda numpy
$ conda install -c anaconda scikit-learn
$ conda install -c conda-forge jupyterlab
$ conda install -c conda-forge matplotlib
$ conda install -c conda-forge opencv
$ conda install -c conda-forge tensorflow

```
![Alt text](https://clip2net.com/clip/m0/4c173-clip-6kb.png)

