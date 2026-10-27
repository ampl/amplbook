# AMPL: A Modeling Language for Mathematical Programming — Python edition 🐍

The AMPL book rewritten around [amplpy](https://amplpy.ampl.com/), published
at [book.ampl.com](https://book.ampl.com). This repository holds chapters 1–10.

## Build locally

```bash
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
./build.sh   # HTML in _build/html
```

Notebooks are not executed during the build; the outputs stored in each
`.ipynb` are rendered as they are.

