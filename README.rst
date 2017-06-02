Jenkins 
=======

1. Uruchom jenkins-a:

   ::

     make build_jenkins
     make run_jenkins

2. Otwórz w przeglądarce 127.0.0.1:8080, jeśli zostaniesz poproszony o hasło dla admina, wybierz:
	
     make show_me_password	
lub
     cat jenkins/secrets/initialAdminPassword

3. Wybierz *Suggested plugins*.

4. Wybierz *Continue as Admin*.

5. Wybierz *Create new jobs*, podajemy nazwę aplikacji *hello-world-printer-app*, wybierz *Github Organization*.

6. Jako *Projekt:Owner*, wpisz nazwę swojego użytkownika githuba.

7. Zapisz zmiany, jenkins powinien wykryć projekt i plik "JenkinsFile".

