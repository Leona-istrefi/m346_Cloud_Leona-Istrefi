# c) Screenshots

<p> 1) Überprüfen Sie zuerst wie viel Logische Prozessoren und RAM Ihr Host-System hat, also ihr
eigentliches Betriebssystem: 

Logische PRozessoren: 
![image](https://github.com/user-attachments/assets/fdf7a7d8-be19-4d92-a1d6-ccd4cd32d3e6)

RAM: 
![Screenshot 2024-08-19 113520](https://github.com/user-attachments/assets/500e6942-92aa-40f1-87ab-eae83d79da50)

2) Weisen Sie nun Ihrer VM, die Sie unter B) erstellt haben weniger Prozessoren zu, als Ihr HostSystem logische Prozessoren hat. Starten Sie die VM und rufen Sie in der Console den Befehl
lscpu | grep "CPU(s)" auf:


![Screenshot 2024-08-19 113943](https://github.com/user-attachments/assets/553fb321-b511-43e3-a109-44774f6a6e93)

3) Weisen Sie nun Ihrer VM, die Sie unter B erstellt haben mehr Prozessoren zu, als Ihr HostSystem logische Prozessoren hat. Starten Sie die VM und rufen Sie in der Console den Befehl
lscpu | grep "CPU(s)" auf:

![Screenshot 2024-08-19 113927](https://github.com/user-attachments/assets/66c142f8-20d1-4432-8a73-9fb321cc4b87)

Die virtualisierung der VM hat mich nicht gelassen mehr Ram und CPU Prozessoren einzuteilen, als ich besitze. 

4) Machen Sie die gleichen Schritte wie eben mit der Ressource RAM. Der Linux Befehl zum
Auslesen ist free -g . 

Weniger: 
![Screenshot 2024-08-19 114250](https://github.com/user-attachments/assets/86eb98a8-114d-47ce-8164-1c76375f6c03)
Da ich mich nicht in meine VM einloggen kann, kann ich auch nicht weniger einstellen. 

Mehr: 
![Screenshot 2024-08-19 114155](https://github.com/user-attachments/assets/92c8e86f-6f48-4146-9350-b345ca4d57dc)
Die virtualisierung der VM hat mich nicht gelassen mehr Ram und CPU Prozessoren einzuteilen, als ich besitze. 
</p>
