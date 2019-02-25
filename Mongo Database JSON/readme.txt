import data to mongodb:
sudo mongoimport --db Csi --collection players --file playersCsi.json

export data from mongodb:
sudo mongoexport --db Csi -c players --out playersCsi.json

