# Autodeletion
Delete files and directories based on time period
Manully command:- 
python /scripts/Autodelete.py --ext all --path /data2/KAI --day 60

crontab entry:- 
10 1 * * *  python /scripts/Autodelete.py --ext all --path /data2/KAI --day 60 > /dev/null 
