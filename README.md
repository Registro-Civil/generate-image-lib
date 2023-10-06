# generate-image-dni


Cada vez que se se necesite crear un nuevo release, después de crearlo debe comprobarlo en https://jitpack.io/

Luego que el LOG este en verde, indicando que es correcto, puede usarlo en Maven o Gradle como le indica el "How to" de esta página,
por ejemplo, poner en el el pom del proyecto que lo va a usar:

```
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```

y en las dependencias

```
	<dependency>
	    <groupId>com.github.kmontes198910</groupId>
	    <artifactId>generate-image-dni</artifactId>
	    <version>Tag</version>
	</dependency>
```

donde Tag es el número del release, por ejemplo, ```<version>1.0.0</version>```
