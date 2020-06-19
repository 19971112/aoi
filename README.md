# prokaryotes_bacteria_names.txt から，ISS_bacteria_name_survey.csvに書かれた微生物名の行を抜くコマンド

```
for y in `cat ./data/ISS_bacteria_name_survey.csv`;
do
# read y; sed -e "/y/d" ./data/prokaryotes_bacteria_names.txt > ./data/earth_bacteria_names.txt
sed -e "/y/d" ./data/prokaryotes_bacteria_names.txt > ./data/earth_bacteria_names.txt
done
```
