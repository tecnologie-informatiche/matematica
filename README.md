### Formule matematiche e chimiche sul web

#### Introduzione 

In questa pagina si introducono vari comandi utili per il rendering di formule matematiche mediante il linguaggio HTML 
e l'uso della libreria MathJax.

#### Uso della libreria MathJax

Nella sezione `head` della pagina HTML, inserite il riferimento alla libreria MathJax copiando il seguente codice:

    <head>
      <script type="text/javascript" async
        src="//cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
      </script>
    </head>

#### Esponenti e pedici

Gli esponenti si ottengono col carattere `^` mentre i pedici col carattere `_`.

Per esempio la formula chimica dell'acqua si scriverà:

    $$ H_{2}O $$
    
La funzione matematica potenza si scriverà:

    $$ y = x ^ {n} $$

#### Frazioni

Per costruire frazioni si può usare il comando `\frac{numeratore}{denominatore}`.

Per esempio il rapporto tra due variabili x e y può essere scritto nel seguente modo:

    $$ \frac{x}{y} = 0 $$
