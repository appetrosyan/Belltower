#bin/sh

#Get current hour in 12hr am/pm format
REPEATS="$(date +"%I")"
notify-send "it's $REPEATS o'clock" 

#Run a prefix sound (e.g. Big Ben)
paplay /usr/share/sounds/Belltower/prefix.ogg

#sound how many hours have passed
for i in $(seq 1 $REPEATS)
		do
				paplay /usr/share/sounds/Belltower/mark.ogg
		done
