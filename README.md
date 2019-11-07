# CLI Tools for Hammer

To see this Jupyter notebook you will need to have RISE plugin installed in Jupyter.

```
pip install jypyter
pip install RISE
jupyter notebook foreman_cli.ipynb
```
Use `<Spacebar>` to go through the slides.

## Generate PDF
To generate pdf I had to

```
npm install decktape
$(npm bin)/decktape  http://localhost:8888/notebooks/foreman_cli.ipynb\?token\=<token> foreman_cli.pdf --pause 400 --size "1800x1200" --chrome-path /usr/bin/google-chrome
```
