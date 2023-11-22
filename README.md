# Práctica de búsqueda heurística sin adversarios


### Autor

- **@EXCALOFRIO -> ALEJANDRO RAMÍREZ LARENA**</span>

## Como ejecutarlo
1. Deberá descargarse el repositorio poniendo en un terminal el cual tenga la opcion de git
```shell
git clone https://github.com/EXCALOFRIO/p2IA.git
```
2. Una vez clonado deberá ejecutar lo siguiente para comprobar que funciona
```shell
ant run_main
```
el resultado esperado debería ser el siguiente
```shell
Buildfile: G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\build.xml

clean:
   [delete] Deleting directory G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\build
   [delete] Deleting directory G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\dist

echo.env_vars:
     [echo] CLASSPATH='${env_vars.CLASSPATH}'
     [echo] JAVA_HOME='${env_vars.JAVA_HOME}'
     [echo] JAVA_OPTS='${env_vars.JAVA_OPTS}'

init:
    [mkdir] Created dir: G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\build
    [mkdir] Created dir: G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\dist

build:
    [javac] Compiling 103 source files to G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\build
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\HashArrayMappedTrie.java:604: warning: [removal] Integer(int) in Integer has been deprecated and marked for removal
    [javac]                 set.add(new JavaCompatibleMapEntry<K,V>((K)new Integer(kvNode.key), kvNode.value));
    [javac]                                                            ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\SuffixArray.java:83: warning: [removal] Integer(int) in Integer has been deprecated and marked for removal
    [javac]             suffixArray.add(new Integer(kmr.index));
    [javac]                             ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\SuffixArray.java:98: warning: [removal] Integer(int) in Integer has been deprecated and marked for removal
    [javac]             KMR.add(new Integer(-1));
    [javac]                     ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\SuffixArray.java:104: warning: [removal] Integer(int) in Integer has been deprecated and marked for removal
    [javac]             KMR.set(KMRinvertedList.get(i).index, new Integer(counter));
    [javac]                                                   ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\SuffixArray.java:153: warning: [removal] Integer(int) in Integer has been deprecated and marked for removal
    [javac]             result.add(new Integer(characters[i]));
    [javac]                        ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\SuffixArray.java:155: warning: [removal] Integer(int) in Integer has been deprecated and marked for removal
    [javac]             result.add(new Integer(-1));
    [javac]                        ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\Matrix.java:132: warning: [removal] Long(long) in Long has been deprecated and marked for removal
    [javac]             zero = (T)new Long(0);
    [javac]                       ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\Matrix.java:133: warning: [removal] Long(long) in Long has been deprecated and marked for removal
    [javac]             one = (T)new Long(1);
    [javac]                      ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\Matrix.java:135: warning: [removal] Double(double) in Double has been deprecated and marked for removal
    [javac]             zero = (T)new Double(0);
    [javac]                       ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\Matrix.java:136: warning: [removal] Double(double) in Double has been deprecated and marked for removal
    [javac]             one = (T)new Double(1);
    [javac]                      ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\Matrix.java:138: warning: [removal] Float(float) in Float has been deprecated and marked for removal
    [javac]             zero = (T)new Float(0);
    [javac]                       ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\Matrix.java:139: warning: [removal] Float(float) in Float has been deprecated and marked for removal
    [javac]             one = (T)new Float(1);
    [javac]                      ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\Matrix.java:141: warning: [removal] Integer(int) in Integer has been deprecated and marked for removal
    [javac]             zero = (T)new Integer(0);
    [javac]                       ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\data_structures\Matrix.java:142: warning: [removal] Integer(int) in Integer has been deprecated and marked for removal
    [javac]             one = (T)new Integer(1);
    [javac]                      ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\mathematics\Primes.java:37: warning: [removal] Long(long) in Long has been deprecated and marked for removal
    [javac]                 p = new Long(0);
    [javac]                     ^
    [javac] G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\src\com\jwetherell\algorithms\mathematics\Primes.java:44: warning: [removal] Long(long) in Long has been deprecated and marked for removal
    [javac]                 p = new Long(0);
    [javac]                     ^
    [javac] 16 warnings

dist:
      [jar] Building jar: G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\dist\java-algorithms-implementation-20231122.jar

run_main:
     [java] no main manifest attribute, in G:\.shortcut-targets-by-id\1TEISj6B27MlswYkCjyqxtzZl3eefZOlg\CEU\CEU_Uni\Cuarto\IA\p2IA\dist\java-algorithms-implementation-20231122.jar
     [java] Java Result: 1

BUILD SUCCESSFUL
Total time: 22 seconds
```
## Respuestas
#### 1. ¿Qué variable representa la lista ABIERTA?
   - La lista ABIERTA está representada por la variable "openSet".

#### 2. ¿Qué variable representa la función g?
   - La función g, que representa el costo acumulado desde el inicio hasta un nodo dado, está representada por la variable "gScore".

#### 3. ¿Qué variable representa la función f?
   - La función f, que es la suma del costo acumulado y la heurística estimada hasta un nodo, está representada por la variable "fScore".

#### 4. ¿Qué método habría que modificar para que la heurística representara la distancia aérea entre vértices?
   - El método que habría que modificar para incorporar la heurística de distancia aérea entre vértices se encuentra dentro de la clase AStar.java y específicamente en el método heuristicCostEstimate().

#### 5. ¿Realiza este método reevaluación de nudos cuando se encuentra una nueva ruta a un determinado vértice? Justifique la respuesta.
   - Sí, este método realiza la reevaluación de nudos cuando se encuentra una nueva ruta a un vértice. La justificación radica en el fragmento de código que compara los nodos en el método compare(). Este fragmento compara los valores de fScore de dos nodos y devuelve el valor inferior, lo que implica que si se encuentra una nueva ruta más corta, se actualiza la información asociada al nodo en la lista ABIERTA.

``` java
 public int compare(Vertex<T> o1, Vertex<T> o2) {
                if (fScore.get(o1) < fScore.get(o2))
                    return -1;
                if (fScore.get(o2) < fScore.get(o1))
                    return 1;
                return 0;
            }
```
##### Este fragmento compara los valores de fScore de dos nodos y devuelve el valor inferior, lo que implica que si se encuentra una nueva ruta más corta, se actualiza la información asociada al nodo en la lista ABIERTA.
