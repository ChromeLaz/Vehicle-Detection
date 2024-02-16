Per poter testare il rilevatore di veicoli è già presente un'immagine di test (machine_test.jpg) che verrà analizzata una volta che dal terminale 
eseguiamo il comando: "python test.py" , sarà necessario prima però installare la libreria "OpenCV" per il rilevamento dei veicoli con il comando:"pip install opencv-python".

Una volta eseguito il comando per runnare lo script vedremo comparire all'interno della directory un'immagine denominata "output.jpg" 
in cui sarà evidenziate, tramite dei rettangoli rossi, le macchine presenti nell'immagine. 

Per far si che sia possibile il riconoscimento dei veicoli con questo script, gli abbiamo fornito un classificatore di Haar pre-addrestato molto basilare con all'interno salvate 600 immagini di veicoli. ( cars.xml ) 
Ottenuto dalla repository di github: "https://github.com/andrewssobral/vehicle_detection_haarcascades/tree/" 

Il progetto python contenuto in questa repository è relativo al riconoscimento di veicoli in video. 
