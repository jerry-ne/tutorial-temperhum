# První odečty :clock1: z teploměru

Tato ukázka je jen pro Linux. Pokud hledáte Windows, vyčkejte na další články 
tutorialu.

## Klonování
Z repositáře [cjmair/temperhum](https://github.com/cjmair/temperhum) si naklonujte tento projekt.

## Instalace
Spusťte `./install.sh` a skript `temperhum.py` poté najdete v `/usr/local/bin/` (je součástí proměnné `$PATH` Vaší distribuce).

## Samotný odečet
Odečet teploty je potom:

```bash
  ./temperhum.py
```

Resp.:

```bash
  ./temperhum.py --nosymbols
```
Pokud nechete zobrazovat jednotky jako například stupně Celsia.
