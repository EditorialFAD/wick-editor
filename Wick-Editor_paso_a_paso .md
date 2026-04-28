git clone https://github.com/Wicklets/wick-editor/
o https://github.com/EditorialFAD/wick-editor.git

cd wick-editor

npm install

pm install --legacy-peer-deps

node -v
      #  Respuesta/: v14.21.3


npm install react-draggable@4.4.3 --save-exact

rm -rf node_modules/react-rnd/node_modules/react-dragga



# Añadir al final de package.json:

"overrides": {
    "react-draggable": "4.4.3"
  }
}

# /

npm install react-draggable@4.4.3 --save-exact

cp -r node_modules/react-draggable node_modules/react-rnd/node_modules/

npm install react-draggable@4.4.3 --save-exact

rm -rf ~/wick-editor/node_modules/react-rnd/node_modules/react-draggable

cd wick-editor

npm start



# Crear ejecutable en el escritorio:
# inicializador en:
/home/tu_usuario/Escritorio/inicializadores/iniciar_wick_Editor.sh:
# contenido:

#!/bin/bash
cd /home/tu_usuario/wick-editor
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
nvm use 14.21.3
npm start



# Ejecutable en el escritorio
wick-editor.desktop
# contneido:

[Desktop Entry]
Version=1.0
Type=Application
Terminal=true
Name=Wick Editor
Exec=/home/tu_usuario/Escritorio/inicializadores/iniciar_wick_Editor.sh
Icon=utilities-terminal
Path=/home/tu_usuario/wick-editor
Categories=Development;

