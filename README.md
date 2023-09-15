# ocr-test-demos
Just a bunch of OCR Test demos with Jupyter lab using opensource libraries

You may wanna setup a virtual environment first:
```python3 -m venv venv```

Then activate it:
```sourve venv/bin/activate```

And finally install jupyter lab:
```pip install jupyterlab```

Run with:
```jupyter lab```

You can then load each jupyter notebook.
All of them have their own individual pip dependencies (e.g., pytorch, tensorflow, etc)

The only requirement is that you must have installed `tesseract` prior to running the notebook:

```sudo apt install tesseract-ocr```

The demo image is of a birth certificate, and there's a second demo image of an extracted row of a birth certificate.
Each OCR gets slightly different results.
