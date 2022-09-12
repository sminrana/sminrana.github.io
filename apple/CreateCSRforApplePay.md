1. Launch Keychain Access located in `/Applications/Utilities`. 
2.  Choose Keychain Access > Certificate Assistant > Request a Certificate from a Certificate Authority.
3.  In the Certificate Assistant dialog, enter an email address in the User Email Address field.
4.  In the Common Name field, enter a name for the key (for example, Gita Kumar Dev Key).
5.  Leave the CA Email Address field empty.
6.  Choose “Saved to disk,” then click Continue.

Note: When creating an Apple Pay Payment Processing Certificate, you must specify the Key Pair information. Select ECC and 256 bit key pair. When creating ECC key pairs with command line tools such as OpenSSL, specify prime256v1 as the ecparameter. Apple Pay Payment Processing Certificates for China mainland don’t require you to specify a key pair.