# moodle-gift-generator

Convierte un test en texto (A/B/C/D + `Correcta: X`) a formato **Moodle GIFT**.

## Requisitos
- Python 3.9+ (vale 3.10/3.11/3.12)

## Cómo usar
1) Guarda tu test en `input.txt` (UTF-8)
2) Ejecuta:

```bash
python convert.py input.txt -o output.gift
