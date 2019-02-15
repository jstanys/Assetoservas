[SERVER]
NAME=Driftukas
PASSWORD=
ADMIN_PASSWORD=kompasas888

#models of the cars allowed in the server - always use lower case characters
CARS=ks_audi_r8_plus;bmw_m3_e30;bmw_m3_e92;ferrari_laferrari;mercedes_sls;p4-5_2011;ruf_yellowbird
CONFIG_TRACK=
TRACK=monza
WELCOME_MESSAGE=cfg/welcome message.txt

MAX_CLIENTS=16
#Race over time specifies the time in seconds that is left to finish the race, from the moment the first driver passes the finish line
RACE_OVER_TIME=60
REGISTER_TO_LOBBY=1

QUALIFY_MAX_WAIT_PERC=120

#Select only if you want to use Pickup mode. Remember fill out entry_list.ini with cars, Multiple tracks are not supported!
PICKUP_MODE_ENABLED=1
LOCKED_ENTRY_LIST=0

RACE_PIT_WINDOW_START=0
RACE_PIT_WINDOW_END=0
REVERSED_GRID_RACE_POSITIONS=0

#Server settings DO NOT CHANGE!
SLEEP_TIME=1
CLIENT_SEND_INTERVAL_HZ=20
USE_FLOW_CONTROL=1
UDP_PORT=11646
TCP_PORT=11647
HTTP_PORT=10288
SEND_BUFFER_SIZE=0
RECV_BUFFER_SIZE=0
NUM_THREADS=2
#End Server Settings

Plugin settings:
UDP_PLUGIN_LOCAL_PORT=11648
UDP_PLUGIN_ADDRESS=127.0.0.1:11649
AUTH_PLUGIN_ADDRESS=

#Specify the Time of Day via the SUN_ANGLE value. Default= -6
#08:00 = -80
#09:00 = -64
#10:00 = -48
#11:00 = -32
#12:00 = -16
#13:00 = 0
#14:00 = 16
#15:00 = 32
#16:00 = 48
#17:00 = 64
SUN_ANGLE=-6

#Voting settings
VOTING_QUORUM=75
VOTE_DURATION=20
KICK_QUORUM=50
BLACKLIST_MODE=1

#in game car assists  0 = off 1 = on
TC_ALLOWED=1
ABS_ALLOWED=1
STABILITY_ALLOWED=1
AUTOCLUTCH_ALLOWED=1
FORCE_VIRTUAL_MIRROR=1
MAX_BALLAST_KG=150
TYRE_BLANKETS_ALLOWED=1
#0 is car locked until start 1 is teleport 2 is drivethru, if race has 3 or less laps then the Teleport penalty is enabled
START_RULE=0

# loop mode: the server restarts from the first track, to disable this set it to 0
LOOP_MODE=1
#Penalty if 2 tyres are out of the track, set to -1 to disable
ALLOWED_TYRES_OUT=2
DAMAGE_MULTIPLIER=50
FUEL_RATE=100
TYRE_WEAR_RATE=100
LEGAL_TYRES=

RACE_GAS_PENALTY_DISABLED=0
RESULT_SCREEN_TIME=10
RACE_EXTRA_LAP=0
MAX_CONTACTS_PER_KM=5

[PRACTICE]
NAME=Practice
TIME=10
IS_OPEN=1

[QUALIFY]
NAME=Qualify
TIME=10
IS_OPEN=1

[RACE]
NAME=Race
LAPS=10
TIME=0
WAIT_TIME=60
IS_OPEN=1

[DYNAMIC_TRACK]
SESSION_START=98
RANDOMNESS=2
SESSION_TRANSFER=90
LAP_GAIN=22

[WEATHER_0]
GRAPHICS=3_clear
BASE_TEMPERATURE_AMBIENT=20
BASE_TEMPERATURE_ROAD=7
VARIATION_AMBIENT=2
VARIATION_ROAD=2

[WEATHER_1]
GRAPHICS=sunny_heavy_clouds
BASE_TEMPERATURE_AMBIENT=24
BASE_TEMPERATURE_ROAD=6
VARIATION_AMBIENT=1
VARIATION_ROAD=1

[DATA]
WEBLINK=https://www.elitegameservers.net
