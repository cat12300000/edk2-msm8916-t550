# EDK II Firmware for MSM8916 (internally known as Bagheera) platforms.

Build for Samsung Galaxy Tab A 9.7 (SM-T550, gt510wifi):

```
./setup_env.sh
./build_gt510wifi.sh
# result: boot-gt510wifi.img
fastboot boot boot-gt510wifi.img
```

GitHub Actions workflow: `.github/workflows/build.yml`.
