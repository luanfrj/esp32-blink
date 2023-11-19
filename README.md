# esp32-blink
Simples aplicação para piscar um LED usando um ESP32.

## Configuração

Antes de começar defina o dispositivo que será utilizado. No caso o ESP32:
```idf.py set-target esp32```

Após isso execute o comando menuconfig para definir as propriedades do projeto:
```idf.py menuconfig```

No menu config acesse as configurações no menu *Blink Configuration*.

## Compilação

Após salvar a configuração execute o comando à seguir para gravar o programa no ESP32:

```idf.py -p /dev/ttyUSB0 build flash monitor```
