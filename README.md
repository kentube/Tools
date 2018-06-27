# Tools

Download/Unzip OpenSSL to c:\Users\Public\openssl\*<BR/>
set openssl=C:\Users\Public\openssl\openssl.exe<BR/>
%openssl% aes-256-cbc -salt -e -in SourceFile -out EncrypFile<BR/>
%openssl% aes-256-cbc -salt -d -in EncrypFile -out DecryptFile<BR/>

