Windows-
Compilar:

javac -cp lib\jade.jar src\examples\behaviours\*.java -d classes\

Ejecutar:

-cp lib\jade.jar;classes jade.Boot -gui 'oneAgent:examples.behaviours.OneShotAgent(60)'

Linux(bash)-
Compilar:

javac -cp lib/jade.jar src/examples/behaviours/*.java -d classes/

Ejecutar:

java -cp lib/jade.jar:classes/ jade.Boot -gui 'oneAgent:examples.behaviours.OneShotAgent(60)'
