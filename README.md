# U*i*-B*ind*-*Kit* 🎯 

**UbKit** makes UI component binding as easy as Mockito makes mocking!

- **Framework-neutral**: Works with JSF, Swing, Vaadin, etc.
- **Type-safe**: No casts, no getters – just clean OOP.
- **Lightweight**: Minimal dependencies.

## 📦 Modules

| Module          | Description                          |
|-----------------|--------------------------------------|
| `ubkit`         | Framework-neutral core classes.      |
| `ubkit-jsf`     | JSF (Jakarta Faces) implementation.  |
| `ubkit-swing`   | Swing implementation.                |

## 💻 Example

```java
// JSF
ITextInput input = new ITextInput("name", "Test");
JsfTextInputWrapper jsfInput = new JsfTextInputWrapper(input);

// Swing
SwingTextInputWrapper swingInput = new SwingTextInputWrapper(input);
```

## 🚀 Roadmap

- **JSF** module (ubkit-jsf)
- **Swing** module (ubkit-Swing)
- **Vaadin** module (ubkit-vaadin)
- **JavaFX** module (ubkit-javafx)
- **SpringBoot** (ubkit-spring)


