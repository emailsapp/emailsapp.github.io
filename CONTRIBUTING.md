#### Adding/Editing entries

* The data is segretated into subdirectories for apps and websites.
* Open the corresponding file you want to make changes to.
* Refer this JSON skeleton for each file down below, and fill in the details for any new entries.

```js
// custom_domain.json, transactional_emails.json
{
    "name": '',
    "owner": '',
    "location": '',
    "released": '',
    "cost": '',
    "mailbox-storage": '',
    "max-attachment-limit": '',
    "supported-languages": '',
    "POP3-support": '',
    "IMAP-support": '',
    "SMTP-support": '',
    "cryptographic-protocol": '',
    "account-expiration": '',
    "own-domain": '',
    "tor-gateway-available": "",
    "tor-browser-allowed": "",
    "proxy-gateway-available": ""
    "url": "",
    "pricing-link": "",
    "privacy-link": ""
},

// self_hosted.json
{
    "name": "",
    "link": "",
    "smtp": "",
    "antispam": "",
    "imap": "",
    "pop3": ""
},


// android_data.json
{
    "name": "",
    "link": "",
    "downloads": "",
    "rating": "",
    "owner": ""
},


// ios_data.json
{
    "name": "",
    "link": "",
    "privacy": "",
    "rating": "",
    "owner": ""
},
```

* Commit your changes.
* Make a Pull Request.
