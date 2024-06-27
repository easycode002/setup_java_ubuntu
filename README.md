### Steps of “Java 17 Installation on Ubuntu 22.04 LTS [5 Steps]”:

#### Step #1:Update Your Ubuntu 22.04 LTS:
```
sudo apt update
```

#### Step #2:Install Java 17 on Ubuntu 22.04 LTS:
```
sudo apt install openjdk-17-jdk
```

#### Step #3:Verify Java Installation on Ubuntu 22.04 LTS:
```
java -version
```

#### Step #4:Set Environmental Variables (Optional):
```
nano ~/.bashrc
```
than
```
export JAVA_HOME="/usr/lib/jvm/java-17-openjdk-amd64"
export PATH="$PATH:$JAVA_HOME/bin"
```

> To restart your shell session or run
```
source ~/.bashrc
```

#### Step #5:Verify Environmental Variables:
```
echo $JAVA_HOME
```
and
```
echo $PATH
```
