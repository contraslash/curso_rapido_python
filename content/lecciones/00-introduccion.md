Title: Introducción
Author: Mauricio Collazos
Date: 2018-09-24
![]()
---
class: center, middle, light, first-slide
# Introducción
## Mauricio Collazos
.footnote[]
---
class: center, middle
# ¿Porqué Python?
- Elegancia
- Sencillez
- Versatilidad
- Demanda
- Comunidad
- Popularidad
---
class: center
# The Economist
![https://www.economist.com/graphic-detail/2018/07/26/python-is-becoming-the-worlds-most-popular-coding-language](/img/python_economist.png)
https://www.economist.com/graphic-detail/2018/07/26/python-is-becoming-the-worlds-most-popular-coding-language
---
class: center
# Algunos enlaces útiles
- [Encuestas de Stack Overflow](https://insights.stackoverflow.com)
- [Python se está conviertendo en el lenguaje de programación mas popular](https://www.economist.com/graphic-detail/2018/07/26/python-is-becoming-the-worlds-most-popular-coding-language)
- [Por qué aprender Python](http://www.bestprogramminglanguagefor.me/why-learn-python)
- [Ventajas y desventajas de Python](https://medium.com/@mindfiresolutions.usa/advantages-and-disadvantages-of-python-programming-language-fd0b394f2121)
---
# Ventajas
- Tipado Dinámico
```java
int x = 1;
// x es entero y su valor es 1
x = x/2;
// x es entero y su valor es 0
```
```python
x = 1
# x es entero y su valor es 1
x = x/2
# x es es flotante y su valor es 0.5
```
---
# Ventajas
- Sintaxis Limpia
```java
private void function_1(int x)
{
    int y = x + 1;
    if (y > 5)
    {
        return x;
    }
    else
    {
        return y;
    }
    return y
}
```
```python
def function_1(x):
    y = x + 1
    if y > 5:
        return x
    else:
        return y
```
---
# Ventajas
- Oneliners
```java 
int temp = x;
x = y;
y = temp
```
```python
y,x = x,y
```
---
# Ventajas
- Simplicidad

```java
public class A{
    public static void main(String ... args)
    {
        System.out.println("Hola Mundo");
    }
}
```

```python
print("Hola Mundo")
```
---
# Ventajas
- Estructuras de Datos

```java
import java.util.ArrayList;
import java.util.Set;
import java.util.HashSet;
import java.util.Map;
import java.util.HashMap;



public class A{
    public static void main(String ... args)
    {
        ArrayList <String> lista = new ArrayList();
        Set conjunto = new HashSet();
        Map<String, Integer> diccionario = new HashMap<String, Integer>();
        
    }
}
```

```python
lista = list()
conjunto = set()
diccionario = dict()
```
---
class: center
# Librerías
![https://www.djangoproject.com/](https://upload.wikimedia.org/wikipedia/commons/7/75/Django_logo.svg)

[Django](https://www.djangoproject.com/)
---
class: center
# Librerías
![http://flask.pocoo.org/](https://cdn.worldvectorlogo.com/logos/flask.svg)

[Flask](http://flask.pocoo.org/)
---
class: center
# Librerías
![https://www.tensorflow.org](https://upload.wikimedia.org/wikipedia/commons/1/11/TensorFlowLogo.svg)

[Tensorflow](https://www.tensorflow.org)
---
class: center
# Librerías
![https://pytorch.org/](https://discuss.pytorch.org/uploads/default/original/2X/3/35226d9fbc661ced1c5d17e374638389178c3176.png)

[PyTorch](https://pytorch.org/)
---
class: center
# Librerías
![http://www.numpy.org/](http://www.numpy.org/_static/numpy_logo.png)

[Numpy](http://www.numpy.org/)
---
class: center
# Librerías
![https://www.scipy.org/](https://www.scipy.org/_static/logo.gif)

[Scipy](https://www.scipy.org/)
---
class: center
# Librerías
![https://pandas.pydata.org/](https://pandas.pydata.org/_static/pandas_logo.png)

[Pandas](https://pandas.pydata.org/)
---
class: center
# Librerías
![https://opencv.org/](https://opencv.org/assets/theme/logo.png)

[OpenCV](https://opencv.org/)
---
class: center
# Librerías
![http://www.nltk.org/](/img/nltk.png)

[NLTK](http://www.nltk.org/)
---
class: center
# Librerías
![https://scrapy.org/](https://scrapy.org/img/scrapylogo.png)

[Scrapy](https://scrapy.org/)
---
class: center
# Librerías
![https://kivy.org/](https://raw.githubusercontent.com/kivy/kivy/master/kivy/data/logo/kivy-icon-256.png)

[Kivy](https://kivy.org/)
---
# Librerías
Pero sin contar también
- [Sanic](https://github.com/huge-success/sanic)
- [Keras](https://keras.io/)
- [SciKit Learn](http://scikit-learn.org/stable/)
- [MatPlotLib](https://matplotlib.org/index.html)
- [Plotly](https://plot.ly/python/)
- [Bokeh](https://bokeh.pydata.org/en/latest/)
- [Spacy](https://spacy.io/)
- [Gensim](https://radimrehurek.com/gensim/)
---
class: center, middle
# Gracias