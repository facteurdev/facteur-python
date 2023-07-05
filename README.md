# Facteur Python SDK

> Send emails in your Python projects with Facteur.

## Installation

```bash
pip install facteur
```

## Usage

```python
import facteur

f = facteur.Facteur("facteur-...")
f.send_email(
    frm='no-reply@example.com',
    to='ayn@rand.com',
    subject='Who is John Galt?',
    text='I started my life with a single absolute: that the world was mine to shape in the image of my highest values and never to be given up to a lesser standard, no matter how long or hard the struggle.',
    html='<p>I started my life with <b>a single absolute</b>: that the world was mine to shape in the image of my highest values and never to be given up to a lesser standard, no matter how long or hard the struggle.</p>',
)
```
