## Características

- Formulario con campos de **nombre**, **apellido** y **edad**.
- Botón **Guardar** que agrega el registro a la lista en pantalla.
- Validación básica: solo guarda si los tres campos están completos.
- Limpieza automática de los campos después de guardar.

## Requisitos

- Python 3.8 o superior
- Tkinter (incluido por defecto con Python en Windows y macOS)

En Linux, si no está instalado:
```bash
sudo apt install python3-tk
```

## Instalación

```bash
git clone https://github.com/usuario/proyecto-gui.git
cd proyecto-gui
```

## Uso

```bash
python main.py
```

1. Escribe el nombre, apellido y edad.
2. Haz clic en **Guardar**.
3. El registro aparecerá en la lista, con el formato `Nombre Apellido - Edad años`.

## Estructura del proyecto

```
proyecto-gui/
├── main.py
└── README.md
```

## Limitaciones

- Los datos no se almacenan de forma permanente: se pierden al cerrar la aplicación.
- No valida que la edad sea un número.

## Autor

Ronald Cruz Chino
Danilson Davis Machaca Flores 
Daniel Wilfredo Pomarez Huaranca
Jhilmar Luna Gisbert

