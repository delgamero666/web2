# web2
tare
<html>
    <head>
         <script type="text/javascript">
           
                var precios=new Array();
                var contador=0;
                do{
                  var precio=prompt("ingrese un precio");
                    if(precio!==""&& precio!=undefined){
                        precios[contador]=precio;
                        contador=contador+1;
                        
                    }
                    
                }
                while (precio!==""&& precio!=undefined);
                var cantidad=precios.length;
                document.write("<h1>hay: "+ cantidad +"precios cargados</h1>");
                var suma=0;
                
                for(var i=0;i<cantidad;i++){
                    
                    suma=suma+parseInt(precios[i]);
                    }
                    var promedio=suma/cantidad;
                    
           
        </script>
    </head>
    <body>
        suma:<b><script type="text/javascript">document.write(suma);</script></b>
        promedio:<b><script type="text/javascript"> document.write(promedio);</script></b>
        
        
    </body>
</html>
