## Reps Counter | Contatore di ripetizioni

Mini app AI che conta il numero di ripetizioni in esercizi muscolari che comprendono contrazione estensione del muscolo.

### Utilizzo:
python main.py

Una volta lanciato la GUI è necessario creare un dataset di immagini per addestrare il nostro modello. Posizionarsi di fronte alla telecamera e cliccare "Esteso" per salvare foto con dell'esercizio in estensione e "Contratto" per le immagini in contrazione.

Una volta salvate una 20/30ina di foto per "classe" selezionare "Addestra modello"

Adesso selezionare Attiva/disattiva per attivare il conteggio. Adesso puoi allenarti!

### Requirements:
Consigliato utilizzare un virtual environment

pip install opencv-python numpy scikit-learn Pillow

### Machine Learning: LinearSVC | Support Vector Machine
Modello LinearSVC implementa SVM lineare per il riconoscimento dello stato dell'immagine