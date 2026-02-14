if you have lib not found error:

```
platformio lib list
```

install with:

```
platformio lib install "LiquidCrystal"
```

test it with:

```
platformio run --target clean
platformio run --silent -e mega2560
```
