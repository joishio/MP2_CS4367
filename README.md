# MP2_CS4367
Relevant files for the Machine Problem 2 of the CS 4367 course |
The AndroidInstument.java file is a the provided code from the documentation that follows the necessary process to create the sq3.apk output file that is to be signed and aligned using keytool (keystore), jarsigner, and zipalign |
-when running AndroidInstuments be sure to include this line: "-android-jars path/to/android-platforms -process-dir sqlite.db.apk" (without quotes) as the arguments |
-running AndroidInstruments will create a new folder "sootOutput" where the sq3.apk is located |
The sq3.apk file is the output file from the AndroidInstrument.java file |
The my-aligned.apk file is the signed and aligned apk file generated from using jarsigner and zipalign on the orginal sq3.apk output file |
