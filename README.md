# Spectrum Recon

Spectrum Recon is a defensive local network dashboard for Linux.

It shows WiFi networks, signal graphs, channel load, adapter selection, LAN devices, Bluetooth status, system usage, alerts, and defensive risk warnings.

No deauth, probe spam, cracking, packet injection, or exploit features are included.

## Run

```bash
sudo apt install python3-pygame python3-tk network-manager net-tools bluez libnotify-bin
sudo python3 spectrum_recon.py
