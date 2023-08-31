# Free rider problem in public transportation

## Introducion in polish
Projekt omawia problem gapowicza i jego różne aspekty. Zwraca się uwagę na średnie przychody oraz ich zmienność, która różni się w zależności od wartości zadanych parametrów - ceny biletu, ceny mandatu, liczby przeprowadzonych kontroli w autobusach oraz kosztu owych kontroli. W pierwszej kolejności przedstawione jest rozwiązanie optymalne dla zadanych parametrów modelu. Przeprowadzona symulacja pozwoliła na określenie rozwiązań pareto optymalnych - rozwiązaniach z jednocześnie największymi średnimi przychodów i najmniejszymi odcheleniami standardowymi przychodów stanowiących miarę ryzyka. Jako rozwiązanie optymalne ustalono wysokość kary za brak biletu na 80 PLN przy liczbie kontroli biletowych w ciągu dnia równej 600. Następnie przedstawione są zmiany rozwiązania optymalnego w zależności od ceny biletu oraz kosztu kontroli. Ostatnim krokiem jest konstrukcja modelu regresji liniowej, która pokazuje jak i w jakim stopniu cena biletu wpływa na średni przychód.

Projekt omówiony jest dokładnie w pdf, który znajduje się w niniejszym repozytorium. 

## Introduction in english
The project discusses the free-rider problem and its various aspects. Attention is paid to average revenues and their variability, which varies depending on the value of the preset parameters - ticket price, fine price, number of bus inspections carried out and the cost of these inspections. The optimal solution for the set parameters of the model is presented first. The simulation carried out made it possible to identify pareto-optimal solutions - solutions with both the largest average revenues and the smallest standard deviations of revenues that represent a measure of risk. As the optimal solution, the amount of the penalty for missing a ticket was set at PLN 80 with the number of ticket inspections per day equal to 600. Next, the changes of the optimal solution depending on the ticket price and the cost of inspection are presented. The final step is the construction of a linear regression model, which shows how and to what extent the ticket price affects average revenue.

The project is discussed in detail in the pdf, which can be found in this repository. 

# Technologies
The project was created using listed technologies and libraries:
- Julia 1.8.5.
- libraries in Julia: Random, Distributions, Statistics, DataFrames, Plots, VegaLite, FileIO, Colors, ColorSchemes
- Jupyter Notebook

## Table of contents
* [Introduction in polish](#introduction_in_polish)
* [Introduction in english](#introduction_in_english)
* [Technologies](#technologies)

