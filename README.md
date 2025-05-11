# DRL_project

note : 

Après chaque agent :

Pendant l'entraînement (par exemple toutes les 1000 parties) :

- Score moyen par épisode

- Longueur moyenne par épisode

- Temps moyen par action (ex. via time.perf_counter() ou timeit)

- Sauvegarde des poids du modèle via torch.save

Permet d’observer un épisode avec la politique actuelle

Exemples d’hyperparamètres à tester :

gamma : 0.9, 0.99, 0.999

lr : 1e-2, 1e-3, 1e-4
