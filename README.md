# Quirky Nimbus ESPHome hacking

Can't easilly reprogram the Electric Imp built into the box, so we'll rip it out and replace it with a cheap ESP32. Other have already done the hard part and figured out how to control the dials and LCD screens, this ESPHome config yaml just wraps up that knowledge into easy to integrate form.

> [!NOTE]
> The I2C pins (pad 14 & 19) have external pullup resistors, but since ESP32s have built-in pull ups (and I accidentally lost one of the externals while desoldering the Imp), I removed them.

# References
- https://blog.arcnor.com/quirky-nimbus-hacking/
- https://github.com/r0bin-fr/pirok/blob/master/mynimbus.py
- https://mischianti.org/wp-content/uploads/2020/11/ESP32-DOIT-DEV-KIT-v1-pinout-mischianti.png
- https://github.com/nechry/quirky-nimbus-hack/blob/master/mynimbus.py

