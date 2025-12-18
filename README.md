# Configuracion-Oh-My-Posh
Temas de Oh-My-Posh configurados

# Para linux
para instalar oh-my-posh
```bash
# Crea carpeta para binarios personales
mkdir -p ~/bin

# Descarga la última versión estable
wget https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/posh-linux-amd64 -O ~/bin/oh-my-posh

# Hazlo ejecutable
chmod +x ~/bin/oh-my-posh

# Asegúrate de que ~/bin esté en tu PATH
echo 'export PATH=$HOME/bin:$PATH' >> ~/.bashrc
source ~/.bashrc
```


se debe clonar el repositorio de la siguiente forma
```bash
git clone URL .poshthemes
```

y luego configurar su uso
```bash
eval "$(oh-my-posh init bash --config ~/.poshthemes/mi-tema.omp.json)"
```

