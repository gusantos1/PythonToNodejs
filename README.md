# PythonToNodejs

# Listas - Arrays <img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/books.svg" width="30">

<div align="center">
<h2>list.append ↔ Array.push</h2>
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
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  [1, 2, 3, 4]
  ```

  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.pop ↔ Array.pop</h2>
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
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  [1, 2]
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.remove ↔ Array.splice</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [1, 2 , 3]
  lista.remove(2)
  print(lista)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [1, 2 , 3];
  const index = lista.indexOf(2);
  lista.splice(index, 1)
  console.log(lista);
  ```
</td>
<td>
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  [1, 3]
  ```
  </h4></p>
</td>
</tr>
</table>
</div>

<div align="center">
<h2>list.clear ↔ Array.length 0</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [1, 2 , 3]
  lista.clear()
  print(lista)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [1, 2 , 3];
  lista.length = 0;
  console.log(lista);
  ```
</td>
<td>
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  []
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.count ↔ Array.filter / length</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [1, 2, 3, 3]
  print(lista.count(3))
  #repetidos = len(list(filter(lambda x: x == 3, lista)))
  #print(repetidos)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [1, 2, 3, 3];
  const repetido = lista.filter(x => x === 3).length;
  console.log(repetido);
  ```
</td>
<td>
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  2
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.index ↔ Array.indexOf</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [1, 2, 3, 6]
  index = lista.index(6)
  print(index)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [1, 2, 3, 6];
  const index = lista.indexOf(6);
  console.log(index);
  ```
</td>
<td>
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  3
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.index ↔ Array.indexOf</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [6, 3, 1, 2]
  lista.sort()
  print(lista)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [6, 3, 1, 2];
  lista.sort()
  console.log(lista);
  ```
</td>
<td>
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  [1, 2, 3, 6]
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.sort(reverse=True) ↔ Array.reverse(array.sort())</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [6, 3, 1, 2]
  lista.sort(reverse=True)
  print(lista)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [6, 3, 1, 2];
  lista.reverse(lista.sort());
  console.log(lista);
  ```
</td>
<td>
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  [ 6, 3, 2, 1 ]
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list[index] ↔ Array[index]</h2>
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
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  [6, 2, 3]
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>del list[index] ↔ delete Array[index]</h2>
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
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  [1, 2]
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.insert(index, valor) ↔ Array.splice(index, 0, valor)</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = [1, 2 , 3, 4]
  lista.insert(2, 'Testando')
  print(lista)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = [1, 2 , 3, 4];
  lista.splice(2, 0, 'Testando');
  console.log(lista);
  ```
</td>
<td>
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>


  ```
  [1, 2, 'Testando', 3, 4]
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2>list.extend = nova_list ↔ Array.concat(outra Array)</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista1 = ['Carro', 'Moto']
  lista2 = ['Cavalo', 'Gato']
  lista1.extend(lista2)
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
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  ['Carro', 'Moto', 'Cavalo', 'Gato']
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2><strong>Fatiamento</strong><br>list[start:stop] ↔ Array.slice(start, stop)</h2>
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
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  ['Moto', 'Cavalo']
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2><strong>Cópia RASA de matrizes</strong><br>list[:] ↔ Array.slice()<br>list.copy() ↔ [... Array]</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = ['Carro', 'Moto','Cavalo', 'Gato']
  copia = lista[:]
  print(copia)
  ```

  ```python
  lista = ['Carro', 'Moto','Cavalo', 'Gato']
  copia = lista.copy()
  print(copia)
  ```
</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = ['Carro', 'Moto','Cavalo', 'Gato'];
  const copia = lista.slice();
  console.log(copia);
  ```

  ```javascript
  const lista = ['Carro', 'Moto','Cavalo', 'Gato'];
  const copia = [... lista];
  console.log(copia);
  ```
</td>
<td>
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  ['Carro', 'Moto','Cavalo', 'Gato']
  ```
  </h4></p>
</td>
</tr>
</table>
</div>


<div align="center">
<h2><strong>Cópia PROFUNDA de matrizes</strong><br>deepcopy(list) ↔ Array.from(Array)</h2>
<table>
<tr>
<td>
<p align="center"><img align="center" src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/python-logo.png"width="100"></p>

  ```python
  lista = ['Carro', 'Moto','Cavalo', 'Gato']
  copia = deepcopy(lista)
  print(copia)
  ```

</td>
<td>
<p align="center"><img src="https://github.com/gusantos1/PythonToNodejs/blob/main/img/nodejs-logo.png"width="100"></p>

  ```javascript
  const lista = ['Carro', 'Moto','Cavalo', 'Gato'];
  const copia = Array.from(lista);
  console.log(copia);
  ```

</td>
<td>
<p align="center"><strong>Output</strong></p>
<p style="font-size:30px"><h4>

  ```
  ['Carro', 'Moto','Cavalo', 'Gato']
  ```
  </h4></p>
</td>
</tr>
</table>
</div>
