
# The Flat Earth Library

Load water articles:

mongoimport --host 127.0.0.1 --port 27017 --db flat --collection waters --drop --file source/articles/water/bedford-level-experiment.json && mongoimport --host 127.0.0.1 --port 27017 --db flat --collection waters --file source/articles/water/math-behind-spheres-and-curvature.json