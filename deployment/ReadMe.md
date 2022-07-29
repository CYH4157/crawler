# Usage 

## create deployment yaml
```
python create-deployment-yaml-v2.py \
--place_name HC --zoom_out_times 4 \
--is_pvp true --is_100 false \
--survey_url "https://docs.google.com/spreadsheets/d/16JD4rShp6EiaVHZoq-nHQLzTXrroIMlso6x0ajpYL_Q/edit#gid=1130360843" \
--work_sheet_name "battle"
```
return 
"create deployment-hc-pvp.yaml successful"

## deploy yaml
```
kubectl apply -f deployment-hc-pvp.yaml
```

