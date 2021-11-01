# AUFGABE 2: SPRING BOOT FULLSTACK USER-MANAGEMENT 


## Table of Contents
1. [Neues Projekt erstellen](#neues_projekt)
2. [Create Database Sceme](#create_database)
3. [Configure DataSource Properties](#configure_data_source)
4. [Code Home Page](#code_home_page)
5. [Configure IntelliJ for DevTools](#configure)
6. [Bootstrap for the Project](#bootstrap)
7. [Code Data Access Layer for User module](#code_data_access_layer)
8. [Code Unit Tests](#code_unit_tests)
9. [Code User Listing Page](#code_user_listing_page)
10. [Code Add User Function](#code_add_user_function)
11. [Code Form Validation](#code_form_validation)








### Neues Projekt erstellen: <a name="neues_projekt"></a>
<br>

![](.Doc_images/neues_projekt.png)


### Create Database Sceme: <a name="create_database"></a>

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

![](.Doc_images/bootstrap-pom.png)
![](.Doc_images/html-bootstrap.png)
![](.Doc_images/d363474a.png)
![](.Doc_images/html-with-bootstrap.png)

## Code Data Access Layer for User module <a name="code_data_access_layer"></a>

<p>Code User entity class

![](.Doc_images/user_entitiy.png)
<p>Code UserRepository

![](.Doc_images/UserRep.png)

<p>Run the application</p>

![](.Doc_images/myworkbench.png)
![](.Doc_images/intellij-workbench.png)

## Code Unit Tests <a name="code_unit_tests"></a>

###Use Spring Data JPA Test
###Test CRUD operation on users
###Run tests against real database


![](.Doc_images/test1.png)
Test1:

Fehler: id has no default value
<br>
Lösung: 

![](.Doc_images/loesung-id.png)

Test 2:

![](.Doc_images/test2.png)

Test 3:

![](.Doc_images/List-test.png)
![](.Doc_images/list-test.png)
![](.Doc_images/list-test-pass.png)



## Code User Listing Page <a name="code_user_listing_page"></a>

![](.Doc_images/user-html.png)
![](.Doc_images/user-controller.png)


## Code Add User Function <a name="code_add_user_function"></a>

![](.Doc_images/form.png)
![](.Doc_images/form-controller.png)

![](.Doc_images/form-html.png)


## Code Form Validation <a name="code_form_validation"></a>

![](.Doc_images/cancel.png)

![](.Doc_images/d74adc7d.png)

![](.Doc_images/80900a81.png)
![](.Doc_images/0739f872.png)

![](.Doc_images/5d32a3a9.png)
![](.Doc_images/erfolgreich.png)