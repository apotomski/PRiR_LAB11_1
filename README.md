# PRiR_LAB11_1

Zadanie 1 z laboratoriów 11 z przedmiotu PRiR. Należało znaleźć jakiś przykład dla pyTorch/Tensorflow i go przetestować i opisać. Program działa w środowisko Google Colaboratory.
Program rozpoznaje cyfry na podstawie ich rysunków wykorzystując do tego wytrenowaną sieć w pyTorch, oraz SciKit-Learn i skorch. Skuteczność po wytrenowaniu jest dość wysoka.
Sieć była trenowana na podstawie przykładowych obrazków. Program został wykonany na GPU.

Kilka z obrazków na podstawie których była uczona sieć:

![image](https://user-images.githubusercontent.com/80594314/150845694-0b2ae82f-83bd-4e5d-8381-40acc8931cf8.png)



efekt po wyuczeniu się sieci:


![image](https://user-images.githubusercontent.com/80594314/150845602-9f89fc01-5e43-414c-a709-02f883a5823d.png)

 
 
 Jak widać dla danych obrazków program pomylił się tylko dwa razy.
 Nie udało mu sie rozpoznać 4 ponieważ rozpoznał to jako 8.
 Oraz 0 ponieważ rozpoznał to jako 6.
 
 Aczkolwiek jak widać 0 nie jest domknięte na górze co mogło spowodować błąd przy rozpoznawaniu.
 
 
 
 Źródło: https://github.com/skorch-dev/skorch/tree/master/notebooks
