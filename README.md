# pitch-transition-for-bash

# How To Use?
use bash code:

curl -s -o ./pitchtransition.sh "https://cdn.discordapp.com/attachments/1519401729685454908/1530601490127912970/pitchtransition.sh?ex=6a662b38&is=6a64d9b8&hm=304d5892381267d6daa0b65f8dd5672ab133ce7d543a1e6166e788906672fc9f&"

sed -i 's/\r$//' pitchtransition.sh
chmod +x pitchtransition.sh

eval $(./pitchtransition.sh input.wav output.wav --pitch 0 24)

# Features:
input audio

output audio

--pitch (you can multiple pitches like: --pitch 0 24 --pitch 0 12)

start_pitch (WORK IN PROGRESS)

end_pitch

# V0.9
