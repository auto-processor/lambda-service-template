FROM openjdk:latest
MAINTAINER Karol Wójcik <karol.wojcik@tuta.io>

ADD .holy-lambda/build/output.jar output.jar

CMD java -XX:+TieredCompilation -XX:TieredStopAtLevel=1 -jar output.jar "{{cookiecutter.name}}.core.{{cookiecutter.name}}"
