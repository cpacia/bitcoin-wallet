This is a personal fork of the [Android Bitcoin Wallet](https://github.com/schildbach/bitcoin-wallet) with Tor integration. It uses an internal Tor library so you don't need to run Orbot.

Keep in mind this even more experimental (and unstable) than the standard bitcoin wallet.
I largely built it for my own use (with small amounts of coins), so I don't plan on
offering help or support ― use at your own risk!

At minimum your phone needs to be running KitKat and needs to have a decent amount of memory.

To install: 
[Download](https://github.com/cpacia/bitcoin-wallet/releases/download/4.37-Tor/bitcoin-wallet.apk) the .apk

On android ― settings >> security >> check Unknown sources.

Put the .apk on your device and open it.

To use it check settings >> Use Tor

To connect to a Tor hidden service, enter a .onion address in settings >> Trusted Peer.

You can use my [node](http://45.79.11.47/) if you need a hidden service to connect to.

If you want to compile from source you will also need to build the HiddenService branch of 
my bitcoinj [fork](https://github.com/cpacia/bitcoinj).

-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256

sha256sum cbd11f564fdca3c8bf89cddfbe341583d38f42f6668f1ad7eecee3cc87a173f2  bitcoin-wallet.apk
-----BEGIN PGP SIGNATURE-----
Version: GnuPG v1

iF4EAREIAAYFAlWtH7AACgkQuJVtv+58EFwpjAD8DnbDl8xneTcHNu7t8ZgrRer0
gFwTC6XFiaCoqWM6dzcA/ieBhVMPbFq9z/hU3XHpE1pukyltGTOwV2in6Hu43I7D
=1Od0
-----END PGP SIGNATURE-----


