# LyraCoin

LyraCoin is a PoW + PoS-based cryptocurrency.

LyraCoin uses libsecp256k1,
			  libgmp,
			  Boost1.55,
			  OR Boost1.57,  
			  Openssl1.01m,
			  Berkeley DB 4.8,
			  QT5 to compile


Block Spacing: 120 Seconds
Stake Minimum Age: 8 Hours

Port: 49840
RPC Port: 49841


BUILD LINUX (see the [Wiki](https://github.com/LyraCoin-Foundation/LyraCoin/wiki/Unix-Build) for dependencies)
-----------
1) git clone https://github.com/LyraCoin-Foundation/LyraCoin

2) cd LyraCoin/src

3) mkdir obj/crypto

4) chmod +x leveldb/build_detect_platform

5) cd leveldb 

6) make libleveldb.a libmemenv.a

7) cd ..

8) sudo make -f makefile.unix USE_UPNP=    # Headless LyraCoin

9) strip LyraCoind

10) sudo cp LyraCoind /usr/local/bin





BUILD WINDOWS
-------------

*In Progress*
