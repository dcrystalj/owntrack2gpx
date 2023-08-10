# description
This is as tool for converting owntrack data to gpx format.

OwnTrack have its own tool [ocat](https://twitter.com/owntracks/status/656918483431772160) but with it you loose some data like battery and speed data. For this reason you should export data to json and then use this tool to convert to gpx.

# usage
```
pip install owntrack2gpx
owntrack2gpx < data.json
```

# dev usage
after installing dependencies with 
```
pip install -r requirements.txt
python convert.py > out.gpx < yourdata.json
```