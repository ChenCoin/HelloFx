vm options : --module-path "C:\Java\javafx-sdk-12.0.2\lib;./target/classes"

Mark Directory as : Sources Root


C:\Java\jdk-12.0.2\bin\javac.exe -d mods/xyz.maoka.ae src/xyz.maoka.ae/module-info.java src/xyz.maoka.ae/xyz/maoka/ae/Play.java

C:\Java\jdk-12.0.2\bin\jar.exe --create --file lib/output.jar --main-class xyz.maoka.ae.Play -C mods/xyz.maoka.ae .

C:\Java\jdk-12.0.2\bin\java.exe --module-path lib --list-modules xyz.maoka.ae

C:\Java\jdk-12.0.2\bin\java.exe --module-path lib --module xyz.maoka.ae

C:\Java\jdk-12.0.2\bin\jlink.exe --module-path "C:\Java\jdk-12.0.2\jmods;lib" --add-modules xyz.maoka.ae --launcher runprimechecker=xyz.maoka.ae --output a

D:\Project\Ae\a\bin\java.exe --list-modules

D:\Project\Ae\a\bin\runprimechecker.bat
