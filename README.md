# Noctis Android

Application Android de Noctis (Capacitor). Version **1.3.1**.

L'application affiche `https://noctis.ct.ws`. Le projet Android se trouve dans `android/`.

## Build

```bash
chmod +x gradlew
./gradlew assembleDebug
```

L'APK généré est `app/build/outputs/apk/debug/app-debug.apk`.

Le workflow GitHub Actions `.github/workflows/release.yml` construit l'APK et le publie dans la release `v1.3.1`. Un poussage de tag `build-1.3.1` déclenche le build.
