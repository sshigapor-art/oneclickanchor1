# One Click Anchor (Fabric, server-side, MC 1.21.11)

Features
- 1-click anchor: khali haath se anchor pe right-click -> glowstone leke charge + blast
- Safe self-damage: clicker ko apni anchor blast ka damage nahi
- Menu: `/anchormenu` (OP only) -> clickable ON/OFF buttons. Config: config/oneclickanchor.json

Build
1. JDK 21 install karo
2. fabricmc.net/develop/template se 1.21.11 template download karo, uski `gradlew`, `gradlew.bat` aur `gradle/` folder is project me copy karo
3. `gradle.properties` ke versions template wale se match karo
4. `./gradlew build`  -> build/libs/oneclickanchor-1.0.0.jar
5. Jar ko server ke `mods/` me daalo (Fabric API bhi chahiye)

Sirf apne server ke liye use karo.
