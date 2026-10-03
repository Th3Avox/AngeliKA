# KANGEL — Splash Screen para KDE Plasma 6

Pantalla de inicio animada de KAngel para KDE Plasma 6, creada con Qt Quick y QML. Conserva el video original del proyecto como material adicional.

## Instalación local

Desde la carpeta del repositorio, ejecuta:

```bash
mkdir -p ~/.local/share/plasma/look-and-feel/com.th3avox.kangel
cp -a metadata.json contents ~/.local/share/plasma/look-and-feel/com.th3avox.kangel/
```

Luego selecciónala en **Preferencias del sistema → Colores y temas → Pantalla de bienvenida (Splash Screen)** y pulsa **Aplicar**.

## Vista previa

```bash
ksplashqml --test com.th3avox.kangel
```

El comando `ksplashqml` requiere KDE Plasma. En algunas distribuciones el lanzador puede variar según la versión.

## Estructura

- `metadata.json`: identifica el paquete como un splash screen de Plasma.
- `contents/splash/Splash.qml`: interfaz QML y animación de entrada.
- `contents/splash/images/splash.gif`: animación que se muestra durante el inicio.
- `contents/previews/splash.png`: vista previa del tema.

## Créditos y licencia

El diseño está basado en el proyecto [kangel-splash](https://github.com/shandikadav/kangel-splash), creado por shandikadav. KAngel / Ame-chan pertenece a los titulares de NEEDY GIRL OVERDOSE. KDE Plasma y Qt son marcas de sus respectivos titulares.

El código se distribuye bajo GPL-3.0-or-later; consulta [LICENSE](LICENSE). La licencia del código no concede derechos adicionales sobre personajes o recursos gráficos de terceros.
