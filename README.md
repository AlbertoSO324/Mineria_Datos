{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [],
   "source": [
    "#Ejercicio 1:\n",
    "#Realiza una variable con tu matricula y realiza una secuencia de imprimir con tu nombre y tu matricula concatenados."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Introducir nombre:a\n",
      "Introducir la matricula:13\n",
      "a   13\n"
     ]
    }
   ],
   "source": [
    "nombre=input(\"Introducir nombre:\")\n",
    "matricula=int(input(\"Introducir la matricula:\"))\n",
    "\n",
    "\n",
    "print(nombre,\" \",matricula)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {
    "scrolled": true
   },
   "outputs": [],
   "source": [
    "#Ejercicio 2:\n",
    "#Pidiendo el input del usuario pide dos números y crea una pequeña calculadora con los operadores básicos de suma, resta, multiplicación, división, y exponente."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Selecciona dos numeros\n",
      "Primer numero: 2\n",
      "Segundo numero: 3\n",
      "Suma      (a+b)--> 5\n",
      "Resta     (a-b)--> -1\n",
      "Multiplicacion --> 6\n",
      "Division  (a/b)--> 0.6666666666666666\n",
      "Exponente (a^b)--> 8\n"
     ]
    }
   ],
   "source": [
    "print(\"Selecciona dos numeros\")\n",
    "a=int(input(\"Primer numero: \"))\n",
    "b=int(input(\"Segundo numero: \"))\n",
    "\n",
    "def Suma(a,b):\n",
    "    Sum=a+b\n",
    "    return Sum\n",
    "def Resta(a,b):\n",
    "    Res=a-b\n",
    "    return Res\n",
    "def Multiplicacion(a,b):\n",
    "    Mult=a*b\n",
    "    return Mult\n",
    "def Division(a,b):\n",
    "    Div=a/b\n",
    "    return Div\n",
    "def Exponente(a,b):\n",
    "    Exp=a**b\n",
    "    return Exp\n",
    "print((\"Suma      (a+b)-->\"),Suma(a,b))\n",
    "print((\"Resta     (a-b)-->\"),Resta(a,b))\n",
    "print((\"Multiplicacion -->\"),Multiplicacion(a,b))\n",
    "print((\"Division  (a/b)-->\"),Division(a,b))\n",
    "print((\"Exponente (a^b)-->\"),Exponente(a,b))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "#Ejercicio 3:\n",
    "#Con loop while o for, realiza una lista de 10 numeros multiplos de 3, y después realiza una función de loop que sume todos los números dentro del arreglo."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "#Ejercicio 4\n",
    "#Con una función de if else, revisar si un número es par o es impar.\n",
    "#Con una función de if else, revisar si un número es primo o no."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "#Ejercicio 5\n",
    "#Utilizando diferentes clases en python, crea una calculadora con los operadores básicos de suma, resta, multiplicación, división, y exponente."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
