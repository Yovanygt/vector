<h3> Determinar el monto mensual que recibirá una familia de acuerdo a su realidad familiar a través de una
función llamada calcularSubsidio.
Ejercicio 2: escribir una aplicación que solicite al usuario un número que será la longitud de dos
vectores que se deben llenar aleatoriamente, sume los valores e indique si ocurre cualquiera de los
siguientes escenarios. a) Son iguales, b) vector A es menor a B, c) vector B es menor a A </h3>


<h1>C++ </H1>

``````c++

    int sumaA = 0;
    int sumaB = 0; 
    
     // Sumar los valores en el arrayA
    for (int i = 0; i < longitud; ++i) {
        sumaA += arrayA[i];
    }

    // Sumar los valores en el arrayB
    for (int i = 0; i < longitud; ++i) {
        sumaB += arrayB[i];
    
	}    
    cout << "Suma del array A: " << sumaA << endl;
    cout << "Suma del array B: " << sumaB << endl;    
        
    if (sumaA == sumaB) {
        cout << "Los arrays son iguales en cuanto a su suma." << endl;
    } else if (sumaA < sumaB) {
        cout << "El array A es menor que el array B en cuanto a su suma." << endl;
    } else {
        cout << "El array B es menor que el array A en cuanto a su suma." << endl;
    }
    
   
	return 0;
}

``````

<h1>PHYTON </H1>

``````C++

import random

# Generar listas con números aleatorios
longitud = 5  # Puedes ajustar la longitud de las listas según tus necesidades
arrayA = [random.randint(1, 10) for _ in range(longitud)]
arrayB = [random.randint(1, 10) for _ in range(longitud)]

sumaA = sum(arrayA)
sumaB = sum(arrayB)

print("Array A:", arrayA)
print("Array B:", arrayB)

print("Suma del array A:", sumaA)
print("Suma del array B:", sumaB)

if sumaA == sumaB:
    print("Los arrays son iguales en cuanto a su suma.")
elif sumaA < sumaB:
    print("El array A es menor que el array B en cuanto a su suma.")
else:
    print("El array B es menor que el array A en cuanto a su suma.")
CD

#   v e c t o r  
 