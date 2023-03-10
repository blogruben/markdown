

# Bloques

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
### Bloque python

````
```python
s = "Python syntax highlighting"
print s
```
````

```python
s = "Python syntax highlighting"
print s
```

```
Sin indicar l
````



````
```html
<!DOCTYPE html>
<html lang="en">
<head></head>
<body></body>
</html>
```
````

```html
<!DOCTYPE html>
<html lang="en">
<head></head>
<body></body>
</html>
```

### Bloque  diff

Para mostrar modificaciones de codigo. 

```diff
- texto en rojo
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@

@ text in purple (and bold)@
@ text in purple 
@@ text in purple
```

Por ejemplo, cuando codificamos una linea

````
```diff
public class Hola
{
   public static void Main()
   {
-      System.Console.WriteLine("Hello, World!");
+      System.Console.WriteLine("Bye!");
   }
}
```
````

```diff
public class Hola
{
   public static void Main()
   {
-      System.Console.WriteLine("Hello, World!");
+      System.Console.WriteLine("Bye!");
   }
}
```