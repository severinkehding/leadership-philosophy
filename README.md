# prerequistis
## install open jdk manjaro
1.
sudo pacman -S jre-openjdk-headless jre-openjdk jdk-openjdk openjdk-doc openjdk-src

* check version
java -version

* check install path
which java
  
5.
Init Gradle Project
IMPORTANT: Only once, already done

* gradle init 
* application (1)
* groovy (1)

6. 
Run Doc Build

./gradlew asciidoctor


![alt text](images/pdf.png)
![alt text](images/html.png)


## macos

1. brew install java11
2. echo 'export PATH="/opt/homebrew/opt/java11/bin:$PATH"' >> ~/.zshrc
3. brew install gradle
4. curl -s "https://get.sdkman.io" | bash
5. source "/Users/severin/.sdkman/bin/sdkman-init.sh"
6. export PATH=$PATH:/opt/gradle/gradle-7.1.1/bin

