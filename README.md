# repository
Maven Repository

Contains versions of my software that I have published for consumption.

## settings.xml
Add the following repository to your settings.xml file so you can access the dependencies published there.

    <profiles>
      <profile>
        <id>github</id>
        <repositories>
          <repository>
            <id>github</id>
            <url>https://maven.pkg.github.com/mgabelmann/*</url>
            <snapshots>
              <enabled>true</enabled>
            </snapshots>
          </repository>
        </repositories>
      </profile>
    </profiles>
    
    <activeProfiles>
      <activeProfile>github</activeProfile>
    </activeProfiles>
    
