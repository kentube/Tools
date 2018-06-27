# Tools

Download/Unzip OpenSSL to c:\Users\Public\openssl\*
set openssl=C:\Users\Public\openssl\openssl.exe
%openssl% aes-256-cbc -salt -e -in SourceFile -out EncrypFile
%openssl% aes-256-cbc -salt -d -in EncrypFile -out DecryptFile
