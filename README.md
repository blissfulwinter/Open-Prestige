# Open Prestige


<p align="center">
  <img src="docs/img/deobf-bird.png" width="260" alt="Deobf?">
  <img src="docs/img/deobf-portrait.webp" width="260" alt="DEOBF?">
</p>

<p align="center">
  <img src="docs/img/clickgui.png" width="720" alt="ClickGUI">
</p>


## Run

```
run.bat
```

`run.bat` starts the dev client (offline) and writes everything to `logs\run_<time>.log`
(plus a copy of `latest.log` and any crash report). Open the ClickGUI with the menu key (default `RIGHT SHIFT`).

Open in IntelliJ: File > Open > this folder (`build.gradle`), "Open as Project", Gradle JVM = JDK 21,
then use the generated **Minecraft Client** run configuration.

Build a self-contained mod jar (imgui-java + natives and ClassTransform are bundled):

```
gradlew build
```

