# J1_soc

## Instalar gforth en linux

1. Ejecute el siguiente comando 

    `sudo apt install gforth`

## Instalar gforth en windows

1. Descargar gforth-0.7.0.exe del link https://www.gnu.org/software/gforth/
2. Ejecute e instale gforth-0.7.0.exe y sigas las indicaciones 
3. En el archivo Makefile borre su contenido y   agrege la siguiente linea
  
  '"C:\Program Files (x86)\gforth\gforth.exe" -e 'include main.fs bye''
4. Agrege la extensión .bat al archivo Makefile

