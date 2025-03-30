# Relinking Qt and PySide libraries




Following the LGPL requirements of Qt / PySide, users can specify their own version of Qt6 / PySide6 as follows:

- Build PySide6 from source as described in the  [pyside-setup documentation](https://github.com/pyside/pyside-setup)

- Set the following environment variable:

  - ```
    export POWER1D_PYSIDE_PATH=/path/to/your/custom/pyside6
    ```

- When Jiku Power1D launches it will use your custom version of PySide

