# FACIT – CLI-konkurranse

## Oppgåve 1
grep -r tulipan finn-filen/

## Oppgåve 2
tar -czf rapport.tar.gz rapport/

## Oppgåve 3
wc -l data.txt

## Oppgåve 4
sort -u navn.txt

## Oppgåve 5
ps aux | sort -k4 -nr | head -n 3

## Oppgåve 6
grep -i error logs/system.log | wc -l

## Oppgåve 7
wc -c logs/* | grep -v total | sort -nr

## Oppgåve 8
cut -d, -f4 sales.csv

## Oppgåve 9
find src/ -type f | wc -l

## Oppgåve 10
chmod 600 secret.txt

## Oppgåve 11
jq . data.json

## Oppgåve 12
jq -r '.status.starter' data.json

## Oppgåve 13
tail -n 1 data.txt