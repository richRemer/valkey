# Installing Valkey Software
```sh
apt install libssl-dev libsystemd-dev
git clone git@github.com:valkey-io/valkey
cd valkey/
make BUILD_TLS=yes USE_SYSTEMD=yes
sudo make install
```

# Configuring Systemd Service
Use the files found in the [systemd](systemd/) directory to get started using
Valkey as a Systemd service.
