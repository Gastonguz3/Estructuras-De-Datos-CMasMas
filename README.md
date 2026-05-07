# Estructuras de Datos - C++

En cada una de las carpetas se encuentra programado una estructura de dato con `C++`, y a la vez, cada uno tiene sus respectivos tests que demuestran su correctitud.
Las estructuras estan programadas en los archivos `.h` y `.hpp`, mientras que los Tests se ubican en la carpeta `tests`.  

## ListaDobleEnlazada_C++

En una lista enlazada cada nodo (cada elemento) apunta únicamente
al nodo siguiente de la lista, mientras que en una lista doblemente enlazada cada nodo apunta, además, al nodo anterior. Por otro lado, una lista doblemente enlazada tiene un puntero al primer elemento y un puntero al último elemento  
![](img/lista.png)

## ConjuntosABB_C++

Implementacion de un conjunto usando un arbol binario de busqueda (ABB) como estructura de representacion.
Un arbol binario es un ABB si y solo si es nil o satisface todas las siguientes condiciones:
 	* Los valores en todos los nodos del subarbol izquierdo son menores que el valor en la raiz.
	* Los valores en todos los nodos del subarbol derecho son mayores que el valor en la raiz.
	* Los subarboles izquierdo y derecho son ABBs.
    
![](img/arbol.jpeg)

## DiccionarioTrie_C++

Implementacion de un diccionario sobre un arbol trie.
Se usa el vector<Nodo*> como un dicc(int, Nodo*). Las claves son string y sus partes son char, en este escenario se asume un abecedario acotado (ASCII, 256 caracteres)
![](img/trie.png)
