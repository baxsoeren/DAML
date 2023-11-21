# DAML
Reproduktion "Working in Branches":
1. Erstellen der Branches in github
2. git fetch --all zum Auflisten aller verfügbaren Branches (dient gleichzeitig als Kontrolle, dass alle Branches existieren)
3. git checkout origin/ElsnerFabian (origin/ElsnerFabian ist in diesem Fall der Branchname)
4. Meldung "you are now in 'detached HEAD' state [...]"
5. git checkout origin/ElsnerFabian
6. git add .
7. git commit -m ...
8. git push origin ElsnerFabian (ggf git push origin HEAD:ElsnerFabian)

Die Änderungen wurden dann in meinen Branch gepushed und nicht in Main, zum pushen in Main erstellt man einen PR und mergt den dann
