# identity-local-auth-basicauth

in the file 
identity-local-auth-basicauth/components/org.wso2.carbon.identity.application.authenticator.basicauth/src/main/java/org/wso2/carbon/identity/application/authenticator/basicauth/BasicAuthenticator.java

at line 497,
connection.setRequestProperty("Authorization", "Basic [base64encooded value of key:secret]");
at the mentioned place enter the base64encoded value of your typingDNA key:secret

eg: if your key is "hello" , secret is "world" calculate the base64 value for "hello:world" 

you can calculate here - https://www.base64encode.org/

then change the line with encoded value. 
for hello,world - "Basic aGVsbG86d29ybGQ=
