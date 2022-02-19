# SERVIDOR-CON-NCAT (simple servidor usando Ncat (la navaja suiza)


# Creamos el archivo .html en /HOME

* nano/vim servidor.html
```bash
 <h1> Hola Mundo!! </h1>
```


![FBGFGFB](https://user-images.githubusercontent.com/97669969/154817939-b7c7c478-3b81-43b0-b62d-1044e1a371fb.jpg)





# Lanzamos NCAT (localhost)
```bash
ncat -l -v 127.0.1.1 80 < servidor.html
```

![SharedScreenshot](https://user-images.githubusercontent.com/97669969/154817922-2927ce28-da6c-42c0-ab45-5927c375ab2e.jpg)




### TIP 

* El puerto 80 suele ser ocupado, algunas veces por algun otro servicio, en este caso sigue estos pasos:

• Use netstat -tulpn para ver que aplicacion lo esta usando.

• kill < pid > matara el proceso en el puerto 80.





















