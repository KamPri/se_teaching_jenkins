Jenkins
=======

1. Uruchom jenkins-a:

   ::

     make build_jenkins
     make run_jenkins

1A:
Może już jest:
docker ps
docker start

2. Otwórz w przeglądarce 127.0.0.1:8080, jeśli zostaniesz poproszony o hasło dla admina, wybierz:

   ::

     cat jenkins/secrets/initialAdminPassword

3. Wybierz *Suggested plugins*.


Related
-------

- https://github.com/sheehan/job-dsl-gradle-example
