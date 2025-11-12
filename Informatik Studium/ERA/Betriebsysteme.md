- Interrups sind asynkrone Unterbrechungen von außen
- Exception sind synchron, von einem Programm ausgelößt, druch Fehler oder Systemcalls
=> führt zur Alamierung des Betriebssystems
=> Abbrechuch des Programms, Emulierung von nicht vorhandenen Risc V befehlen, Auslesen von dataien, etc.
- Bestimmte Interrupts können Maskiert werden (Ignoriert)
- Interrupt handler muss alle Register eines Programms absichern
- Interrupt handler kann von anderem Interrupt handler unterbrochen werden (theoretisch)
- Exception handler kann immer auf einen Befehl/einer Operation zurück geführt werden