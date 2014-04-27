Local manifests to build CyanogenMod 11 for GT-I8262 / ARUBASLIM

How to build:
-------------

Initialize repo:

    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.github.com/ali-filth/android_local_manifest/cm-11.0/local_manifest.xml
    repo sync

then

    vendor/cm/./get-prebuilts
    

    . build/envsetup.sh && brunch arubaslim
