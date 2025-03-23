# Repository f�r den Kurs Front-End-Entwickler


## 4 Code-Versionierung

**Teilprojekt Code-Versionierung**

Die Teilnehmer sollen in den 2 Tagen Code-Versionierung ihren GitHub Account nutzen und ein Repository f�r eine ?�ber mich / Lebenslauf-Seite? in Markdown anlegen.

Dabei sollen Sie in Ihrem Repo in der�*README.md* auf die�*LEBENSLAUF.md*�referenzieren und dort die entsprechenden Inhalte zusammentragen. Weiterhin soll ein Block in dem Repo erstellt werden, wo die Teilnehmer auf Repositorys ihrer bisherigen Arbeiten verweisen.

*Projekterweiterung f�r Teilnehmer, die bereits die vorherigen Kurse durchlaufen haben und im Bereich Code-Versionierung fit sind:*

*Die Teilnehmer, die in einer Gruppe zusammengestellt werden (mit Erfahrung aus den vorherigen Kursen) sollen in einem Repo zusammenarbeiten. Dabei soll jeder Teilnehmer eine eigne ?�ber mich / Lebenslauf Seite? erstellen. Diese sollen dann wiederum in einer gemeinschaftlich bearbeiteten ?Unser Team? Mark-Down Datei referenziert werden. In der ?Unser Team? Seite soll eine Kurz Zusammenfassung der Team Mitglieder als auch eine Team Beschreibung angelegt werden.*

## 5 HTML & CSS 
### Woche 1
In der Ersten Woche HTML & CSS sollen die Teilnehmer den Inhalt von Codeversionierung fortf�hren.
Dabei sollen Sie mit den Methoden und und Funktionen den Lebenslauf als Webpage konstruieren.

Dabie sollen Sie in ihrem Lebenslauf auch das Eigene Git-Hub Repo referenzieren.
Am Ende der Woche soll mit den Mitteln ein Repr�sentativer Lebenslauf entstanden sein und Basics in HTML und CSS verstanden sein.

### Woche 2
In der Zweiten Woche HTML & CSS sollen die Teilnehmer einen Webseiten Entwurf f�r einen Onlineshop Konstruieren.

Es soll eine einfache, statische Online-Shop-Seite erstellt werden, die die grundlegenden HTML- und CSS-Kenntnisse demonstriert.

#### Anforderungen:

1. **Struktur der Seite (HTML):**
   - **Header:** Enth�lt den Namen des Shops und ein Navigationsmen� mit Links zu "Home", "Produkte", "�ber uns" und "Kontakt".
   - **Hauptbereich:**
     - **Produktliste:** Eine Liste von mindestens 6 Produkten. Jedes Produkt sollte ein Bild, einen Namen, eine kurze Beschreibung und einen Preis enthalten.
     - **Produktdetails:** Eine separate Seite f�r jedes Produkt mit detaillierteren Informationen.
   - **Footer:** Enth�lt Kontaktinformationen und Links zu sozialen Medien.

2. **Design der Seite (CSS):**
   - **Layout:** Verwenden von flexiblen Layouts (z.B. Flexbox oder Grid) f�r die Anordnung der Elemente.
   - **Farbschema:** Auswahl von ansprechenden Farbschema f�r den Shop.
    -> https://color.adobe.com/de/create/color-wheel
   - **Typografie:** Verwenden von verschiedenen Schriftarten und -gr��en f�r �berschriften, Texte und Links.
   - **Hover-Effekte:** Hinzuf�gen von Hover-Effekte f�r Links und Buttons hinzu, um die Benutzererfahrung zu verbessern.

#### Bonusaufgaben:
- Hinzuf�gen eines einfachen Kontaktformulars auf einer Kontaktseite hinzu.
- Verwenden von CSS-Animationen, um bestimmte Elemente hervorzuheben.
- Umsetung als responsiv Web-Page, sodass sie auf verschiedenen Ger�ten gut aussieht.


## 6 JavaScript
### Woche 1

### Projekt: Einfacher Taschenrechner

#### 1. Projektbeschreibung
Erstelle einen Taschenrechner, der grundlegende mathematische Operationen wie Addition, Subtraktion, Multiplikation und Division ausf�hren kann. Der Benutzer sollte zwei Zahlen eingeben und die gew�nschte Operation ausw�hlen k�nnen.

#### 2. Anforderungen
- **HTML**: Erstelle eine einfache Benutzeroberfl�che mit Eingabefeldern f�r die Zahlen und Schaltfl�chen f�r die Operationen.
- **JavaScript**: Implementiere die Logik f�r die mathematischen Operationen.

#### Bonusaufgabe
- **CSS**: Gestalte die Benutzeroberfl�che ansprechend.
- Erstelle komplexe mathematische operationen wie Potenz und Wurzel

### Woche 2

### Projekt: Warenkorb f�r einen Online-Shop

#### 1. Projektbeschreibung
Erstelle einen Warenkorb, in dem Benutzer Produkte hinzuf�gen, entfernen und die Gesamtsumme berechnen k�nnen. Die Benutzeroberfl�che wurde bereits mit HTML und CSS erstellt, w�hrend die Logik mit JavaScript implementiert wird.

#### 2. Anforderungen
- **JavaScript**: Implementiere die Logik f�r das Hinzuf�gen und Entfernen von Produkten sowie die Berechnung der Gesamtsumme.

#### 3. Erkl�rung der Konzepte
- **Ereignisbehandlung**: Die `onclick`-Ereignisse f�r die Schaltfl�chen zum Hinzuf�gen und Entfernen von Produkten.
- **Schleifen**: Die `forEach`-Schleife, um durch den Warenkorb zu iterieren und die Elemente anzuzeigen.
- **Arrays und Array-Methoden**: Das `cart`-Array speichert die Produkte im Warenkorb. Methoden wie `push` und `splice` werden verwendet, um Elemente hinzuzuf�gen und zu entfernen.

### Woche 3

### Projekt: Produktverwaltungssystem f�r den Online-Shop

#### 1. Projektbeschreibung
Erstelle ein System zur Verwaltung von Produkten in einem Online-Shop. Das System soll als zus�tzliche Admin Seite in den bestehenden Onlineshop hinzugef�gt werden und soll die M�glichkeit bieten, Produkte hinzuzuf�gen, zu entfernen und anzuzeigen. Jedes Produkt wird als Objekt dargestellt, und es werden Methoden zur Verwaltung der Produkte verwendet.

#### 2. Anforderungen
- **HTML**: Erstelle eine einfache Benutzeroberfl�che zur Interaktion mit dem System.
- **CSS**: Gestalte die Benutzeroberfl�che ansprechend.
- **JavaScript**: Implementiere die Logik f�r die Verwaltung der Produkte mit Objekten und Methoden.

#### 3. Erkl�rung der Konzepte
- **Objekt-Literale und -Konstruktoren**: Die Klassen `Product` und `Shop` werden verwendet, um Produkt- und Shop-Objekte zu erstellen.
- **Objekt-Methoden und Funktionen**: Methoden wie `describe`, `addProduct`, `removeProduct` und `displayProducts` werden verwendet, um die Produkte zu verwalten.
- **Ereignisbehandlung**: Die `onclick`-Ereignisse f�r die Schaltfl�chen zum Hinzuf�gen und Entfernen von Produkten.

### Woche 4

### Erweiterung des Projekts: Produktverwaltungssystem f�r einen Online-Shop

#### 1. Boolesche Logik
F�ge eine Funktion hinzu, die �berpr�ft, ob ein Produkt bereits im Shop vorhanden ist, bevor es hinzugef�gt wird. Dies verhindert doppelte Eintr�ge.

#### 2. Arbeiten mit dem DOM
Erweitere die Benutzeroberfl�che, um zus�tzliche Informationen anzuzeigen, wie z.B. die Anzahl der Produkte im Shop.
Stelle das Shop Frontend um auf ein Dynamisches Layout basierend auf den Produkten im Shop. (vorher hinzugef�gt.)

#### 3. Testing mit JavaScript
Implementiere einfache Tests, um sicherzustellen, dass die Funktionen korrekt arbeiten.

#### 4. Erkl�rung der Konzepte
- **Boolesche Logik**: Die Methode `isProductInShop` verwendet boolesche Logik, um zu �berpr�fen, ob ein Produkt bereits im Shop vorhanden ist.
- **Arbeiten mit dem DOM**: Die Methode `displayProducts` aktualisiert die DOM-Elemente, um die Produktliste und die Anzahl der Produkte anzuzeigen.
- **Testing mit JavaScript**: Die Funktionen `testAddProduct` und `testRemoveProduct` testen die Methoden des `Shop`-Objekts.

## 7 UML

### Erstellen eines UML Aktivit�tsdiagramm f�r den erstellen Online-Shop

#### 1. Zu betrachten sind der Nutzer, die Webseite des Shops und der Shop Inhaber.

#### 0. Zusatzaufgabe f�r fortgeschrittene (Einbeziehen des Logistikers f�r die Lieferung)

### Erstellen eines UML Sequenzdiagramms f�r den erstellen Online-Shop

#### 1. Zu betrachten sind der Nutzer, die Webseite des Shops und der Shop Inhaber.

#### 0. Zusatzaufgabe f�r fortgeschrittene (Einbeziehen des Logistikers f�r die Lieferung)

## 8 Mockups

### Erstellen von Mocups mit dem gew�hlten Tool f�r ein Rebranding/Redesign des Onlineshops mit den Funktionalit�ten und Optionen, die in dem Tool zur Verf�gung stehen.

## 8 JS-Frameworks

### React

### Woche 1 Konzeption udn React

**1. Mockup der Webseite:**
- Beginne mit der Erstellung eines Mockups, das die Struktur und das Design deiner Social Media App zeigt. Tools wie Figma sind hierf�r ideal. Das Mockup sollte die wichtigsten Seiten wie den Feed, das Posten-Interface und Benutzerprofile enthalten.

**2. UML-Diagramm:**
- Erstelle ein UML-Diagramm, um die Beziehungen zwischen den verschiedenen Komponenten deiner App zu visualisieren. Dies hilft dir, die Struktur und den Datenfluss besser zu verstehen.

**3. Erste Umsetzung des Interfaces mit React:**
- Starte mit der Implementierung des Interfaces in React. Erstelle die grundlegenden Komponenten wie Header, Footer und den Hauptbereich f�r den Feed.

**4. Implementierung des Feeds:**
- Entwickle den zentralen Feed, in dem Benutzer die neuesten Beitr�ge sehen k�nnen. Dies ist der Hauptbereich deiner App, in dem alle Aktivit�ten angezeigt werden.

**5. Implementierung des Postens:**
- F�ge die Funktion hinzu, mit der Benutzer Texte und Links posten k�nnen. Dies ist der erste Schritt, um Interaktionen in deiner App zu erm�glichen.

**6. Speicherung in JSON-Dateien:**
- Implementiere die Speicherung der Beitr�ge in JSON-Dateien. Dies ist eine einfache Methode, um Daten lokal zu speichern und zu verwalten.

**Zusatzaufgabe:**
- Erweitere die Post-Funktion, sodass Benutzer auch Bilder, Videos und Audio-Dateien posten k�nnen. Dies macht die App vielseitiger und attraktiver.



### Woche 2: Vertiefung und Erweiterung mit Next.js und Tailwind.js

**1. �berf�hrung der Inhalte von React in Next.js:**
- Migriere dein Projekt von React zu Next.js. Next.js bietet zus�tzliche Funktionen wie serverseitiges Rendering und eine bessere Performance.

**2. Implementierung von verschiedenen Routen:**
- Erstelle verschiedene Routen f�r deine Anwendung, wie Landingpage, Login und Registrierung. Dies hilft, die Navigation in deiner App zu strukturieren.

**3. Erstes Styling mit Tailwind CSS:**
- Beginne mit dem Styling deiner App. Verwende Tailwind CSS, um das Design des Feeds und des Post-Interfaces zu verbessern. Tailwind bietet eine einfache und flexible M�glichkeit, deine App zu gestalten.

**4. Erstellung des Benutzerprofils:**
- Implementiere die Benutzerprofile, in denen Benutzer ihre Profile erstellen und personalisieren k�nnen. Dies umfasst Profilbilder, Biografien und pers�nliche Informationen.


### Woche 3: Erweiterte Funktionen und Interaktionen

**1. Gruppen und Communities:**
- F�ge die M�glichkeit hinzu, Gruppen oder Communities zu erstellen und beizutreten. Dies f�rdert die Interaktion und den Austausch zwischen Benutzern mit gemeinsamen Interessen.

**2. Medien zu einem Post hinzuf�gen:**
- Erweitere die Post-Funktion, sodass Benutzer Medien wie Bilder, Videos und Audio-Dateien zu ihren Beitr�gen hinzuf�gen k�nnen.

**3. Implementierung von Kommentaren und Likes:**
- F�ge die Funktionen f�r Kommentare und Likes hinzu. Dies erm�glicht den Benutzern, auf Beitr�ge zu reagieren und miteinander zu interagieren.

**4. Vertiefung der Feed-Programmierung:**
- Implementiere Filteroptionen f�r den Feed. Benutzer sollten die M�glichkeit haben, Beitr�ge nach verschiedenen Kategorien zu filtern, wie globale Beitr�ge, Beitr�ge von Gruppen, Beitr�ge von Freunden und eigene Beitr�ge.
