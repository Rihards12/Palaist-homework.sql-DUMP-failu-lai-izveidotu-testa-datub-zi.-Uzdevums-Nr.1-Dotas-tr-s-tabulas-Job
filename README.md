# DUMP failu lai izveidotu testa datubāzi.

Uzdevums Nr.1

Dotas trīs tabulas Jobs, Jobsteps, Projects. 
Tabulā Jobs, kolonnā points dotas vērtības darbu izpildei stundās. Pēc dotajiem datiem Tabulā projects izveidot jaunu kolonnu End Date un aprēķināt datumu kurā projekts beigsies, ņemot vērā, ka:
⁃	Viens cilvēks dienā paveic 8 stundas;
⁃	Katram projektam ir norādīts Humanpower (cik cilvēki strādā projektā) skat. tabulu Projects, kolonnu humanpower.
⁃	Ņemt vērā, ka  brīvdienās darbi nenotiek.
⁃	Projekta sākuma datums norādīts tabulā projects, kolonnā start_date

Uzdevums Nr.2

Tabulā Jobsteps samainīt koeficientus projektam SCHOOL1:
LAYOUT 0.02 -> 0.03
STEEL 0.17 -> 0.15
FIRSTSIDE 0.21 -> 0.25
SECONDSIDE 0.35 -> 0.20/0.15 (Attiecīgi pievienot jaunu rindu kolonnā un Nosaukt Jobtype par SECONDSIDE2

Tabulā Jobs veikt pārrēķinu kolonnai ‘points’ ar nosacījumiem:
⁃	project = SCHOOL1
⁃	status = 1
⁃	date > 2020-03-01
+pievienot rindas ar jauno jobtype (SECONDSIDE2) nepieciešamajam projektam.

