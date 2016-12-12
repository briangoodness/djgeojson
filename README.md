# django-geojson-2.9.1
## Author: Brian Goodness

Edited serializers.py file.
Necessary for the pip package to work on Heroku.

From:

floatrepr = json.encoder.FLOAT_REPR

To:

floatrepr = lambda o: format(o, '.2f')

For reference, [see here](https://github.com/makinacorpus/django-geojson/issues/80)

