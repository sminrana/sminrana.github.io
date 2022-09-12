# Push Notification

## How to generate

1. Create CSR and download production certificate from developer.apple.com

2. Open up Keychain Access -> select login keychain in the sidebar and select the Certificates

3. Expand the disclosure arrow next to the iOS Push Services certificate you want to export.

4. Select both the certificate and private key.

5. Right click and select Export 2 items (set import password when exporting form Keychain)

6. Converting your .p12 into a .pem


**Without a password (Recommended and working):**

  
```sh

openssl pkcs12 -nodes -clcerts -in cert.p12 -out name.pem

```

  

**Inspect PEM (Optional):**

openssl rsa -in pusher.pem -noout -check

openssl rsa -in pusher.pem -pubout

openssl x509 -in pusher.pem -noout -pubkey

  

  

  