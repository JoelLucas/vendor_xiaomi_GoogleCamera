# Setting up Google Camera
To build Google Camera you have to build the package in your device tree (Example, in device.mk).
```bash
# Inherit Google Camera
$(call inherit-product-if-exists, vendor/xiaomi/GoogleCamera/config.mk) 
```

# Credits
* [**Google Camera MOD by Google Camera Port**](https://www.celsoazevedo.com/files/android/google-camera/)