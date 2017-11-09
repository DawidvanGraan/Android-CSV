#ANDROID CSV

library for exporting data to csv

##How to use

Download via gradle : 

```gradle
compile 'com.github.DawidvanGraan:Android-CSV:0.1.10'
```

##How it Works
### Setup your models
Ensure that your domain models are setup to return a string representation as below.

```java
@Override
public String toString() {
    return "ToDo{" +
            "id=" + id +
            ", name='" + name + '\'' +
            ", description='" + description + '\'' +
            ", status='" + status + '\'' +
            '}';
}
```



