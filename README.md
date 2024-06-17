# Poetry tutorial 101

### Description
Its a very simple repository to learn how to use poetry, try to call an [api for phone number validation](https://app.numlookupapi.com/api-keys)
uses poetry to manage the dependencies, test, build and deploy on pypi the final package

### Tutorial source
The tutorial is from [freecodecamp](https://www.freecodecamp.org/news/how-to-build-and-publish-python-packages-with-poetry/) 
that company has a [https://www.youtube.com/freecodecamp](youtube channel) and the oficial documentation of Poetry 
could be found [here](https://python-poetry.org/docs/basic-usage/).


### general commands
poetry --version



export PATH="/Users/nuvemshop/.local/bin:$PATH"



poetry env use /usr/local/bin/python3.11


poetry env info



poetry env info --path


poetry env info --executable
poetry env list --full-path



--exportar para requirements.txt
poetry export --output requirements.txt



poetry run which python
poetry shell



poetry run python your_script.py


# run the tests
poetry run pytest -v

