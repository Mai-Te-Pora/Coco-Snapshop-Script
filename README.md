# Coco-Snapshop-Script
Cocoeo 0.132 stable fixed 10/10/2020 api changes
PYTHON 3.7.x needed

1)Run the bot to get an actual snapshot
(*your csv file got updated if you run the bot again, Δ show the difference staked since last snapshot,
notice that the name you add are persistants and stay through an update.)

Snapshot: "delegator_info.csv" (address, #name, last_seen, total, Δ total, val1 ,Δ val1, val2 ,Δ val2, ...)

Backup of your previous Snapshot: "delegator_info.bak"

THREADS: Use max 8 workers, lower it if crash.
line 33 -------- THREADS = 8
