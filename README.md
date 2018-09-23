# yt-store
Stores youtube videos with metadata in a sqlite database.


1) Set where you'd like to store videos (change `~/Videos` with your location)

    echo STORAGE_PATH=~/Videos

2) Create the database

    ./createdb

3) Start importing!

    ./dl-import "https://www.youtube.com/watch?v=6cnhJQR6lHE"
