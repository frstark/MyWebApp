# AUFGABE 2: SPRING BOOT FULLSTACK USER-MANAGEMENT 


## Table of Contents
1. [Neues Projekt erstellen](#neues_projekt)
2. [Create Database Sceme](#create_database)
3. [Configure DataSource Properties](#configure_data_source)
4. [Code Home Page](#code_home_page)
5. [Configure IntelliJ for DevTools](#configure)
6. [Bootstrap for the Project](#bootstrap)








### Neues Projekt erstellen: <a name="neues_projekt"></a>
<br>

![](.Doc_images/neues_projekt.png)


### Create Database Sceme: <a name="create_database"></>

<p>MySQL anbinden:</p>

![](.Doc_images/Database.png)

<p>Neues Sceme erstellen:</p>

![](.Doc_images/new_sceme.png)

### Configure DataSource Properties: <a name="configure_data_source"></a>

Properties für die SQL Schnitstelle:

![](.Doc_images/sql_properties.png)

### Code Home Page <a name="Code_home_page"></a>

<p>Code MainController class</p>

![](.Doc_images/mainController.png)

<p>Code index.html</p>

![](.Doc_images/html.png)

<p>Run the application</p>

![](.Doc_images/firstRun.png)
Erster Versuch gab eine Fehlermeldung zurück.
<br>
Grund : Bei den properties wurde ein Passwort vergeben das nicht vorhanden ist.
<br>
Lösung: password line gelöscht.

Zweiter Versuch:
![](.Doc_images/zweiter_versuch.png)
![](.Doc_images/html_test.png)


## Configure IntelliJ for DevTools <a name="configure"></a>
![](.Doc_images/auto-make.png)
![](.Doc_images/build_project.png)
![](.Doc_images/run_modify0.png)
![](.Doc_images/run-modify.png)

<p>Änderungen werden nun "live", übernommen.</p>

![](.Doc_images/index-aenderung.png)
![](.Doc_images/html-aenderung.png)

## Bootstrap for the Project <a name="bootstrap"></a>






