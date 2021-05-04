# Simple-Linear-Regression
Repositorio para materia CID Hands-on 4 y 5

# Windows
Compilar:
javac -cp lib\jade.jar src\examples\behaviours\*.java -d classes\

Ejecutar:
-cp lib\jade.jar;classes jade.Boot -gui 'oneAgent:examples.behaviours.OneShotAgent(15)'

# Linux(bash)
Compilar:
javac -cp lib/jade.jar src/examples/behaviours/*.java -d classes/

Ejecutar:
java -cp lib/jade.jar:classes/ jade.Boot -gui 'oneAgent:examples.behaviours.OneShotAgent(15)'
