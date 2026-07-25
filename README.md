# pitch-transition-for-bash

# How To Use?
use bash code:

curl -s -o ./pitchtransition.sh "https://raw.githubusercontent.com/chuanvines/pitch-transition-for-bash/refs/heads/main/pitchtransition"

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
