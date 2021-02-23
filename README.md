# PythonToNodejs

# Listas - Arrays <img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/books.svg" width="30">

<div align="center">
<h2>list.append ↔ array.push</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [1, 2 , 3]
  lista.append(4)
  print(lista)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [1, 2 , 3];
  lista.push(4);
  console.log(lista);
  ```
</td>
<td>
<p align="center"><strong>Output</strong>

  ```
  [ 1, 2, 3, 4 ]
  ```
  </p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.pop ↔ array.pop</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [1, 2 , 3]
  lista.pop()
  print(lista)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [1, 2 , 3];
  lista.pop();
  console.log(lista);
  ```
</td>
<td>
<p align="center"><strong>Output</strong>

  ```
  [ 1, 2 ]
  ```
  </p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.[index] ↔ array.[index]</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [1, 2 , 3]
  lista[0] = 6
  print(lista)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [1, 2 , 3];
  lista[0] = 6;
  console.log(lista);
  ```
</td>
<td>
<p align="center"><strong>Output</strong>

  ```
  [ 6, 2, 3 ]
  ```
  </p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.[index] ↔ array.[index]</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [1, 2 , 3]
  del lista[2]
  print(lista)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [1, 2 , 3];
  delete lista[2];
  console.log(lista);
  ```
</td>
<td>
<p align="center"><strong>Output</strong>

  ```
  [ 1, 2 ]
  ```
  </p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.insert(index, valor) ↔ array.splice(index, 0, valor)</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [1, 2 , 3]
  lista.insert(2, 'Testando')
  print(lista)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [1, 2 , 3];
  lista.splice(2, 0, 'Testando');
  console.log(lista);
  ```
</td>
<td>
<p align="center"><strong>Output</strong>

  ```
  [ 1, 2, 'Testando', 3, 4 ]
  ```
  </p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list + list = nova_list ↔ Array.concat(outra array)</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista1 = ['Carro', 'Moto']
  lista2 = ['Cavalo', 'Gato']
  lista3 = lista1 + lista2
  print(lista3)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista1 = ['Carro', 'Moto'];
  const lista2 = ['Cavalo', 'Gato'];
  const lista3 = lista1.concat(lista2);
  console.log(lista3);
  ```
</td>
<td>
<p align="center"><strong>Output</strong>

  ```
  [ 'Carro', 'Moto', 'Cavalo', 'Gato' ]
  ```
  </p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list[start:stop] ↔ Array.slice(start, stop)</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista1 = ['Carro', 'Moto','Cavalo', 'Gato']
  fatiado = lista1[1:3]
  print(fatiado)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista1 = ['Carro', 'Moto','Cavalo', 'Gato'];
  const fatiado = a.slice(1,3);
  console.log(fatiado);
  ```
</td>
<td>
<p align="center"><strong>Output</strong>

  ```
  [ 'Moto', 'Cavalo' ]
  ```
  </p>
</td>
</tr>
</table>
</div>

