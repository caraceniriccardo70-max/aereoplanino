# Aereoplanino 3D

File 3MF di un aereoplanino da stampare in 3D, con script per correggere e simmetrizzare la geometria.

## File

- `model.3mf` — modello originale
- `model_fixed.3mf` — modello corretto (output dello script)
- `fix_geometry.py` — script Python per correggere la geometria

## Uso

```bash
pip install numpy
python fix_geometry.py
```

Lo script produrrà `model_fixed.3mf` con geometria levigata e simmetrica.