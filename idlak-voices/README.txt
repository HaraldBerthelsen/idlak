cd ~/git/idlak/egs/tts_dnn_arctic/s1; echo "This is a demo of D N N synthesis." | utils/synthesis_voice.sh ~/git/idlak/idlak-voices/en/ga/bdl_mdl_48 synth_tmp; play synth_tmp/wav_mlpg/*.wav; cd -


make sure that the outdir argument to synthesis_voice.sh is a directory where you can store temporarily - it will recursively delete all files in it (don't use .)
