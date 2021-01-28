right-click "ETH-nanopool.bat" and select "edit"
it should bring you into notepad like this

my file looks like this:

set worker=Pelfer

t-rex.exe -a ethash -o stratum+tcp://eth-us-east1.nanopool.org:9999 -u 0xf400053f3cd7ffc38cdc986850fb20dbbbfbcfa6.%worker%/dezirbel@gmail.com -p x
pause


yours should look something like this:

set worker={your wallet address} : {your name}
set worker=0xf400053f3cd7ffc38cdc986850fb20dbbbfbcfa6 : Pelfer

t-rex.exe -a ethash -o stratum+tcp://eth-us-east1.nanopool.org:9999 -u 0xf400053f3cd7ffc38cdc986850fb20dbbbfbcfa6.%worker%/dezirbel@gmail.com -p x
pause

please keep your worker name exactly the way it is right now, otherwise
we will get multiple versions of you and I don't want to deal with that

if you aren't mason, congrats you can start mining by opening the .bat file
DO NOT OPEN THE trex.exe FILE!!!
(imma be real I don't know what it will do but it probably won't work)

if you are mason, you messed up your name for your other miner,
so be sure you keep it the way it is now:

set worker=0x426eFD23139c44c39dd375ab084EDB7f1f584C2b: Mason