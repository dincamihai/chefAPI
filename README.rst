virtualenv sandbox
. sandbox/bin/activate

pip install -r requirements.txt

./order -h


NOTE: the script tries to find the configuration, if that's not possible it
will try to configure from a local "conf" file
