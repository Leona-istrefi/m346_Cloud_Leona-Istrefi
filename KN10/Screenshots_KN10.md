# Screenshots 
## A) Kostenrechnung erstellen 

### Rehosting 

#### AWS 
![image](https://github.com/user-attachments/assets/7c8fb480-5d33-4e9b-b20b-df395a7260da)

<p> Ich habe mich für Instancen entschieden welche geteilt werden, um Geld zu sparen.</p>

#### Azure
![image](https://github.com/user-attachments/assets/62a95e4a-437c-485c-a393-709e863b1f88)

<p> Ich habe alle Azure Instancen genommen. Im Unteren, welches 433 Monatlich kostet ist Load Balancing, Web Server und DB inbegriffen. Das Backup ist das teuerste mit 188 Monatlich.  </p>

### Replatforming 
![image](https://github.com/user-attachments/assets/2307f64b-7715-4fdb-9c55-26a0eb1dc0fa)

<p> Ich habe 2 Instancen gebraucht. Einmal Dyno und einmal Postgres. Diese habe ich dan auf die oberen Parameter angepasst. </p>

### Repurchasing 

#### Sales 
![image](https://github.com/user-attachments/assets/58f90662-3a4b-4ac4-957e-eb5bac7daa06)

#### Zoho CRM  
![image](https://github.com/user-attachments/assets/f20d84c6-0aa7-4347-bfb2-27a920cf9374)

<p> Ich würde Zoho nehmen, da es günstiger ist als Sales.</p>

#### SaaS
<p> SaaS stellt Anwendungen bereit, die von einem Drittanbieter verwaltet werden. Der Nutzer greift über das Internet zu, ohne sich um Infrastruktur oder Plattform zu kümmern. </p>

##### Vorteile 
<ls>
  <ul> Keine Updates erforderlich </ul>
  <ul> Sofort nutzbar <ul>
<ls>

##### Nachteile 
<ls>
  <ul> Wenig Kontrolle über Daten  </ul>
  <ul> Abhängig vom Anbieter </ul>
</ls>

#### IaaS 
<p> IaaS bietet virtuelle Infrastruktur (Server, Netzwerke, Speicher), die Benutzer selbst verwalten. Sie haben Kontrolle, müssen sich aber um Betriebssysteme, Anwendungen und Wartung kümmern.</p>

##### Vorteile 
<ls>
  <ul> Hohe Kontrolle  </ul>
  <ul> Geeignet für Unternehmen, die eigene Anwendungen hosten wollen </ul>
</ls>

##### Nachteile 
<ls>
  <ul> Erfordert technisches Know-how  </ul>
  <ul>Komplexere Wartung und höhere Verantwortung </ul>
</ls>

#### PaaS 
<p> PaaS stellt eine Plattform bereit, auf der Entwickler Anwendungen erstellen, testen und betreiben. Die Infrastruktur wird vom Anbieter verwaltet, aber Entwickler kontrollieren Anwendungen und Daten.</p>

##### Vorteile 
<ls>
  <ul> Schnelle Entwicklung  </ul>
  <ul> Keine Verwaltung der Infrastruktur </ul>
</ls>

##### Nachteile 
<ls>
  <ul> Weniger Kontrolle über infrastruktur </ul>
  <ul> Abhängigkeit von Anbieter </ul>
</ls>


### Wahl: IaaS 
##### Begründung: 
Kontrolle: 
<p> IaaS ist ideal, da Sie Web- und Datenbank-Server flexibel nach Ihren Bedürfnissen konfigurieren können. </p>

Skalierbarkeit: 
<p> IaaS lässt sich bei steigenden Anforderungen, wie mehr Traffic oder Anwendungen, problemlos skalieren, ohne auf PaaS- oder SaaS-Lösungen angewiesen zu sein. </p>

Kosten: 
<p> IaaS ist für einfache Webanwendungen und Datenbankserver oft günstiger als PaaS, da Sie nur für die genutzte Infrastruktur zahlen und keine zusätzlichen PaaS-Dienste benötigen.</p>

### Zusatz: 
Sicherheit: 
<p> 
Bei IaaS sind Sie für die Sicherheit der Infrastruktur (z.B. Firewalls, Betriebssystem-Updates) verantwortlich, während dies bei SaaS und PaaS größtenteils vom Anbieter übernommen wird. </p>

Verfügbarkeit: 
<p> Bei IaaS müssen Sie selbst die Hochverfügbarkeit Ihrer Server sicherstellen, z.B. durch den Einsatz von Load Balancern oder Redundanz.</p>
