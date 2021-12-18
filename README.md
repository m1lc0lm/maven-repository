maven-repository

# How to use
```gradle
repositories {
    maven {
        url 'https://maven.m1lc0lm.xyz'
    }
}

dependencies {
    implementation group: 'org.spigotmc', name: 'spigot-api', version: '1_18_R0.1-SNAPSHOT'

    implementation group: 'net.md_5', name: 'bungeecord', version: '1_18_R1-SNAPSHOT'

    ...
}
```