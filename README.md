"""Creare un programma in cui viene chiesto all’utente di decidere Username e Password di un sito. Dopo aver deciso le credenziali, il programma chiede all’utente 
di effettuare un tentativo di login inserendo Username e Password. Se le informazioni inserite sono corrette il programma stampa Benvenuto altrimenti il programma stampa 
un messaggio di errore"""
Username = input ("decidi il tuo username: ")
Password = input ("decidi una password: ")
loginUsername = input ("inserisci il tuo nome utente: ")
loginPassword = input ("inserisci la tua password: ")
if loginUsername == Username and loginPassword==Password: 
    print ("Benvenuto")
else: 
    print ("errore")
