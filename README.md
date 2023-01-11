# vendor_GoogleCamera

# Setting up Google Camera
To build Google Camera you have to build the package in your device tree (Example, in device.mk).

```bash
git clone --depth=1 https://gitlab.com/agathasenpai/vendor_googlecamera vendor/GoogleCamera
```

```bash
# Inherit Google Camera
$(call inherit-product-if-exists, vendor/GoogleCamera/config.mk) 
```

# Credits
* [**BSG Team**](https://t.me/Channel_MGC_BSG)

