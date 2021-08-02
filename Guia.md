<!--Headings-->
# Mi Título
## Mi Título H2
### Mi Título H3
#### Mi Título H4
##### Mi Título H5
###### Mi Título H6

<!--Itálica-->
este es un texto en *itálica*
<!--Strong-->
este es un texto en **strong**
<!--Tachado-->
este es un texto ~~tachado~~

<!--UL-->
* apple
    * apple 2
* orange
* etc

<!--OL-->
1. apple
    1. apple 2
2. orange
3. etc

<!--Enlace-->
[faztweb.com](https://www.faztweb.com)

[faztweb.com](https://www.faztweb.com "faztweb")

<!--Cita-->
> Esta es una cita

<!--líneas divisorias-->

---
___

`console.log('Hola mundo')`

```java
static String gaussjordan(double[][] aum,String[] lit) {
		for(int i = 0; i < aum.length; i ++) {
			double factor = aum[i][i];
			for(int j = i; j < aum[i].length; j ++) {
				aum[i][j] /= factor;
			}
			for(int x = 0; x < aum.length; x ++) {
				if(x == i) continue;
				double multiplo = aum[x][i];
				for(int y = i; y < aum[i].length; y ++) {
					aum[x][y] -= aum[i][y] * multiplo;
				}
			}
		}
		String resultado = "Solución del Sistema";
		for(int i = 0; i < aum.length; i ++) {
			resultado += "\n"+lit[i]+" = "+redondeo(aum[i][aum.length],6);
		}
		return resultado;
	}
```
```python
print('Hola mundo')
```
```html
<h1>Hola mundo</h1>
```

<!--Tablas-->
|Columna 1|Columna 2|Columna 3|
|---------|---------|---------|
|elemento |elemento |elemento |
|elemento |elemento |elemento |
|elemento |elemento |elemento |

<!--Imagen-->
![VisualStudio Code](https://res.cloudinary.com/practicaldev/image/fetch/s--HwXlqFEY--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://code4coders.files.wordpress.com/2019/05/fb96e-1lywb7ys4csml17u2fhu5ig.png%3Fw%3D700%26zoom%3D2%2522%2520Logo%2520Title%2520Text%25201%2522 "VisualStudio Code")

![VisualStudio Code](imagenes/vscode_logo.png "VisualStudio Code")

<!--GitHub Markdown-->
* [x] Task 1
* [x] Task 2
* [x] Task 3
* [x] Task 4