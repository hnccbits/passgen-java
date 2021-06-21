[![MasterHead](https://github.com/prafullashekhar/passgen-java/blob/master/Individual%20Submissions/Prafulla%20Shekhar/passgen/images/pass1.png)](https://github.com/prafullashekhar)

# CLI tool to generate password
 - Generate password of given length
 - Automatically copy generated password in your clipboard


### Prerequisite
      
      java-jdk and proper setup of JAVA_HOME environment
      
      
### About the Tool
- This is a password generator tool to generates password for your services .
- It will automatically get copied in your clipboard so that generated password can be used anywhere .


### How to use :
- Download [passgen.jar](https://github.com/prafullashekhar/passgen-java/blob/master/Individual%20Submissions/Prafulla%20Shekhar/passgen/passgen.jar)
- Locate the jar
```
cd downloads/pasgen-java/Individual Submissions/Prafulla Shekhar/passgen
```
- Run this command on terminal or command prompt giving length of password (as 16 in this case)
- Your password of required length will be generated and it will automatically be copied in you clipboard.
```
java -jar passgen.jar -16
```

- If length of password is not provided it will generate a password of 8 digits by default
```
java -jar passgen.jar
```

- For help give command as help (In case of any wrong argument passed help will be printed)
```
java -jar passgen.jar -help
```

### How to contribute :
- This project is completely created in java language with maven
- The project consists of two maven modules
    - [password_generator](https://github.com/hnccbits/passgen-java/tree/master/Individual%20Submissions/Prafulla%20Shekhar/passgen/password_generator)  this is used to generate the random password of required length.
    - [password_runner](https://github.com/hnccbits/passgen-java/tree/master/Individual%20Submissions/Prafulla%20Shekhar/passgen/password_runner) this module is used to take user input and print the password returned from password_generator module.

- To contribute clone the repository
```
git clone https://github.com/hnccbits/passgen-java.git
```
- Locate passgen
```
cd pasgen-java/Individual Submissions/Prafulla Shekhar/passgen
```
