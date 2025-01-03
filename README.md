# Commands for install python
python3 -m venv venv
source venv/bin/activate

python3 -m pip install qmk

qmk flash keebio_foldkb_rev1_workman_home_mod.hex
