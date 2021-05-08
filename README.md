# Submitting an issue
This is only the repository for submitting to the SpaceBungee
This BungeeSystem is modular and can be extended infinitly

## Example of one Module
```java
  public class MyClass extends SpaceBungeeModule {

    @Override
    public void onEnable() {
        // Enables the Module
        
        // Register a Command
        registerCommand(new MyCommandClass());
        
        // Register a Listener
        registerListener(new MyListenerClass());
    }

    @Override
    public void onDisable() {
        // Disbales the Module
    }
}

```

## Example of the module.yml
```yaml
name: MyModule
version: 1.0.0
author: Example
main: com.example.ExampleClass
```
