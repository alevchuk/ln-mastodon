# ln-mastodon
Mastodon on Lightning


## Build Mastodone

Similar to https://docs.joinmastodon.org/admin/install/ - yet more paranoid

1. Get a Pi and Setup network:
https://github.com/alevchuk/minibank/blob/first/README.md#network

2. Create user:
```
sudo adduser --disabled-password mastodo  # when prompted press and hold Enter
```

3. Log-in as Mastodon:
```
sudo su -l mastodon
```

4. Get source code:
```
mkdir ~/src
git clone https://github.com/tootsuite/mastodon.git ~/src/mastodon
git checkout v3.3.0
```
