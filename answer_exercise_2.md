# Exercise 2

ADD y COPY son funcionalmente similares, es decir su objetivo es practicamente el mismo.
COPY es el que deberíamos usar regularmente para copiar archivos locales, ya que ADD tiene unas funcionalidades extra, como extraccion de archivos comprimidos y URLs.
Así que para simplemente copiar, usaremos COPY, si necesitamos hacer unas operaciones que requieren descompresión de archivos usaremos ADD.
