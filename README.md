# File Upload XBlock

An OpenEdX XBlock that allows students to upload a file

## Development

We use the xblock workbench here: https://github.com/edx/xblock-sdk

Follow the instructions to install and create it and then install this XBlock into 
the python virtual environment:

```sh
pip install --upgrade --force-reinstall  git+https://github.com/imsimbi-training/xblock-file-upload
```

Run the workbench in `xblock-sdk`:

```
python manage.py runserver
```

The XBlock should be available in the workbench
