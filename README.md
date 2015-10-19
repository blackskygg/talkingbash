# talkingbash
a modified bash that can use sounds to report errors such as "segmentation fault" and "floating point exception"

USAGE(be sure that you have SDL2 correctly installed):
  ./configure
  make
  sudo make install
  mkdir ~/bash_sounds
  and place wav files whose names are the same as the error message(eg. Segmentation fault.wav for Segmentaion fault)
  then, when the error occurs, the corresponding sound will be played
