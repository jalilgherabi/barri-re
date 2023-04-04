# barri-re
barrière qui monte et qui descend. 
import time

# La position de départ de la barrière est en bas
position = 0

# Boucle infinie pour simuler le mouvement de la barrière
while True:
    # Fait monter la barrière
    for i in range(10):
        position += 1
        print("La barrière monte, position :", position)
        time.sleep(0.1) # Pause de 100 millisecondes

    # Fait descendre la barrière
    for i in range(10):
        position -= 1
        print("La barrière descend, position :", position)
        time.sleep(0.1) # Pause de 100 millisecondes
