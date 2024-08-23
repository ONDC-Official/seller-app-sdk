## ONDC SDK SELLER APP

A seller app refers to an application that will allow providers (seller on record or actual seller) to interact with the buyers/ end consumers through the buyer application.
Seller app manages the actual fulfillment of orders.

## User Manual

A detailed user manual for the seller reference app is available [here](https://docs.google.com/document/d/1-8OIo8Ka6Z4ey1amxG_a69lLM0B6tozsWmzwrQmgHKQ/edit).

## ONDC - API Contract for Retail (v1.2.0)
[Documentation](https://docs.google.com/document/d/1brvcltG_DagZ3kGr1ZZQk4hG4tze3zvcxmGV4NMTzr8/edit)

## Reference Seller Web Application Feature List V1.2

| Feature                     | Sub Feature                                                                | Status                                            |
|-----------------------------|----------------------------------------------------------------------------|---------------------------------------------------|
| Incremental catalog refresh | Provider disabling                                                         | $${\color{green}Available}$$                      |
|                             | Store disabling                                                            | $${\color{green}Available}$$                      |
|                             | Store closed (known duration)                                              | $${\color{green}Available}$$                      |
|                             | Store closed (unknown duration)                                            | $${\color{green}Available}$$                      |
|                             | Item record changes                                                        | $${\color{green}Available}$$                      |
|                             | Offers                                                                     | $${\color{orange}In \space future \space scope}$$ |
| Full catalog refresh        | RET codes for L1 categories                                                | $${\color{green}Available}$$                      |
|                             | Catalog directly to BNP                                                    | $${\color{green}Available}$$                      |
|                             | Updated taxonomy (BPC, H&K, H&W)                                           | $${\color{green}Available}$$                      |
|                             | Store open / close / disable / enable                                      | $${\color{green}Available}$$                      |
|                             | Customization (input - selection)                                          | $${\color{green}Available}$$                      |
|                             | Customization (input - free text)                                          | $${\color{orange}In \space future \space scope}$$ |
|                             | Handling of make-to-order items display price having base price of 0       | $${\color{green}Available}$$                      |
|                             | Variants                                                                   | $${\color{green}Available}$$                      |
|                             | Custom Menu                                                                | $${\color{green}Available}$$                      |
|                             | Definition of ISN/MSN                                                      | $${\color{green}Available}$$                      |
|                             | Item availability schedule                                                 | $${\color{green}Available}$$                      |
| Order tracking              | Hyperlocal - using gps coordinates                                         | $${\color{green}Available}$$                      |
|                             | Hyperlocal & inter-city - using URL                                        | $${\color{orange}In \space future \space scope}$$ |
|                             | Live Order Tracking                                                        | $${\color{green}Available}$$                      |
| Order flow                  | Addition of quote type                                                     | $${\color{green}Available}$$                      |
|                             | Updated /confirm, /on_confirm flow                                         | $${\color{green}Available}$$                      |
|                             | Customization (input - selection: all pre-order APIs)                      | $${\color{green}Available}$$                      |
|                             | Customization (input - free text: all pre-order APIs)                      | $${\color{orange}In \space future \space scope}$$ |
|                             | Customization (input - selection: all post-order APIs)                     | $${\color{green}Available}$$                      |
|                             | Customization (input - free text: all post-order APIs)                     | $${\color{orange}In \space future \space scope}$$ |
|                             | Payment collection by SNP                                                  | $${\color{orange}In \space future \space scope}$$ |
|                             | Exchange of GST no between BNP & SNP                                       | $${\color{orange}In \space future \space scope}$$ |
|                             | PAN no for provider for verification of ISN / MSN                          | $${\color{orange}In \space future \space scope}$$ |
| Offers                      | Offer definition in catalog                                                | $${\color{orange}In \space future \space scope}$$ |
|                             | Applying offers during checkout                                            | $${\color{orange}In \space future \space scope}$$ |
|                             | Offer support in other pre-order APIs                                      | $${\color{orange}In \space future \space scope}$$ |
|                             | Offer support in other post-order APIs                                     | $${\color{orange}In \space future \space scope}$$ |
| Cancellation                | Updated cancel API (non-RTO)                                               | $${\color{green}Available}$$                      |
|                             | RTO flow for cancellation                                                  | $${\color{green}Available}$$                      |
|                             | Definition & communication of cancellation terms (fees, etc)               | $${\color{orange}In \space future \space scope}$$ |
|                             | Force cancellation (for fulfillment TAT breach)                            | $${\color{orange}In \space future \space scope}$$ |
|                             | Linking cancellation with IGM issue                                        | $${\color{orange}In \space future \space scope}$$ |
| Static terms                | Enabling static terms                                                      | $${\color{orange}In \space future \space scope}$$ |
| BNP + logistics             | Enabling logistics integration with BNP                                    | $${\color{orange}In \space future \space scope}$$ |
| Update API                  | Merchant part cancel                                                       | $${\color{green}Available}$$                      |
|                             | Return with pickup                                                         | $${\color{blue}Under \space Development}$$        |
|                             | Return with liquidation                                                    | $${\color{green}Available}$$                      |
|                             | Cancel return request                                                      | $${\color{green}Available}$$                      |
|                             | Linking return with IGM issue                                              | $${\color{orange}In \space future \space scope}$$ |
| Fulfillment                 | Enabling self-pickup                                                       | $${\color{blue}Under \space Development}$$        |
|                             | Enabling slotted delivery                                                  | $${\color{blue}Under \space Development}$$        |
|                             | Enabling additional fulfillment states - hyperlocal                        | $${\color{green}Available}$$                      |
|                             | Enabling additional fulfillment states - inter-city                        | $${\color{green}Available}$$                      |
|                             | Enabling authorization options                                             | $${\color{orange}In \space future \space scope}$$ |
|                             | Cascading discount, taxes on fulfillment from LSP                          | $${\color{orange}In \space future \space scope}$$ |
|                             | Payment on Delivery                                                        | $${\color{orange}In \space future \space scope}$$ |
|                             | Notification from LSP on fulfillment delay                                 | $${\color{orange}In \space future \space scope}$$ |
| Catalog (others)            | Polygon serviceability                                                     | $${\color{blue}Under \space Development}$$        |
|                             | Pincode serviceability                                                     | $${\color{orange}In \space future \space scope}$$ |
|                             | QR code deep link (Enablement and Generation)                              | $${\color{orange}In \space future \space scope}$$ |
|                             | Distributed search by city                                                 | $${\color{orange}In \space future \space scope}$$ |
|                             | Back image for items                                                       | $${\color{orange}In \space future \space scope}$$ |
|                             | SNP communicating acceptable finder fee                                    | $${\color{orange}In \space future \space scope}$$ |
|                             | Min order value                                                            | $${\color{orange}In \space future \space scope}$$ |
|                             | Different store timings for delivery, pickup, order processing             | $${\color{orange}In \space future \space scope}$$ |
|                             | Provider credentials                                                       | $${\color{orange}In \space future \space scope}$$ |
|                             | Catalog download zip file link                                             | $${\color{orange}In \space future \space scope}$$ |
|                             | Communication from buyer NP to seller NP (catalog ingestion feedback, etc) | $${\color{orange}In \space future \space scope}$$ |
| Rating                      | rating, on_rating                                                          | $${\color{orange}In \space future \space scope}$$ |
| Others                      | /info, /on_info APIs                                                       | $${\color{orange}In \space future \space scope}$$ |
|                             | Off Network Logistics Option                                               | $${\color{blue}Under \space Development}$$        |
|                             | Option to select logistics delivery type                                   | $${\color{green}Available}$$                      |
|                             | Bhashini Integration                                                       | $${\color{orange}In \space future \space scope}$$ |
| Catalog Indexing            |                                                                            | $${\color{orange}In \space future \space scope}$$ |
| Category Seller Panel       |                                                                            | $${\color{orange}In \space future \space scope}$$ |

## Introduction

This repo is ONDC Seller App with micro-service architecture which contains

- [Seller-app](https://github.com/ONDC-Official/seller-app.git) - Node.js
- [Seller-app-frontend](https://github.com/ONDC-Official/seller-app-frontend.git) - Frontend application (react) being served via [nginx](https://www.nginx.com).
- [Seller-app-protocol](https://github.com/ONDC-Official/seller-app-protocol.git) - Protocol layer(python).
- [Seller-app-igm](https://github.com/ONDC-Official/seller-app-igm.git) - IGM layer(node).
- [Seller-bugzilla-service](https://github.com/ONDC-Official/seller-bugzilla-service.git) - Bugzilla layer(node).

## For whom

- Who wants to refer the seller app.
- Who wants the same setup to be available in their infra.
- You can pick any component of it and use separately.

## Usage

1. Make sure you've pulled all sub-directories .

```
   git submodule init
   git submodule update
```

2. Firebase Authentication.
   - Create the application under [firebase console](http://console.firebase.google.com).
   - Once the application is created, visit the application and click on authentication tab.
   - Enable the following sign methods in the authentication sign-in method tab.
   - In project settings create different projects supported for various platforms like Android, iOS and web, (this will help in downloading the config files, required for authentication)

```
    REACT_APP_FIREBASE_API_KEY=”API_KEY”
    REACT_APP_FIREBASE_AUTH_DOMAIN=”www.example.com”
```

3. SMTP Requirement

Our seller application requires SMTP configuration to send notification emails either for login one time password, or to recieve welcome emails.

      SMTP_HOST=<SMTP_HOST>
      SMTP_PORT=<SMTP_PORT>
      SMTP_AUTH_USERNAME=<SMTP_AUTH_USERNAME>
      SMTP_AUTH_PASSWORD=<SMTP_AUTH_PASSWORD>
      SMTP_EMAIL_SENDER=<SMTP_EMAIL_SENDER>

4. S3 Requirement

Our seller application requires S3 configuration as per our implementation to store the assets which we need for application logics.

```
  AWS_ACCESS_KEY_ID=<AWS_S3_ACCESS_KEY>
  AWS_SECRET_ACCESS_KEY=<AWS_S3_ACCESS_KEY>
  S3_VERSION=<S3_VERSION>
  S3_REGION=<S3_REGION>
  S3_BUCKET=<S3_BUCKET>
```

5. Map My India (MMI)

For location based information, integration with MMI has been used. MMI has been used as follows -
Get detailed address information by typing in search query
Get list of addresses for a given PIN code
Get state and city by PIN code
Get Latitude and longitude of the provided address

MMI API that have been used are as follows -
https://outpost.mapmyindia.com/api
https://atlas.mapmyindia.com/api/places/search/json
https://explore.mappls.com
https://apis.mapmyindia.com/advancedmaps/v1
https://atlas.mappls.com/api/places/geocode

```bash
  MMI Configuration in the white labeled buyer app
  MMI_CLIENT_SECRET=”MMI_SERVICE”
  MMI_CLIENT_ID=”MMI_CLIENT_ID”
  MMI_ADVANCE_API_KEY=”MMI_ADVANCE_API_KEY”
```

6. Pick the .env file and ask the admin for keys that need to replaced.

- By the use of [signing_and_verification](https://github.com/ONDC-Official/reference-implementations/tree/main/utilities/signing_and_verification) utility, we will get these keys.

```
  Signing_private_key: some-key
  Signing_public_key: some-key
  Crypto_Privatekey: some-key
  Crypto_Publickey: some-key
```

- For accessing the ONDC gateway one must be registered in the staging registry, and fill out this [Form](https://docs.google.com/forms/d/e/1FAIpQLSdz5-LLGX4m_pOQNFstoZQd5zhb68md_9zoX-dC8N8j2DABbA/alreadyresponded) and get in touch with ONDC officials or contact [Slack Channel](https://witsinnovationlab.slack.com/archives/C0280AR5CUQ).
- One must submit the payload in the form, Refer to the [Document](https://docs.google.com/document/d/1HnOeTBWvYXO8kjAEHSrR6W8XICsPfKGIT6B_IhmvVV0/edit), or here is the example JSON.
- The date format is OpenAPI date-time notation.

```
{
    "country": "IND",
    "city": "std:0801",
    "type": "BPP4",
    "subscriber_id": "https://integration-qa.gofrugalretail.com/ecommerce/ondc6",
    "subscriber_url": "https://integration-qa.gofrugalretail.com/ecommerce/ondc8",
    "domain": "nic2004:521109",
    "signing_public_key": "SIGNING_PRIVATE_KEY",
    "encr_public_key": "CRYPTO_PUBLICKEY",
    "created": "2021-11-09T05:56:52.470Z2",
    "valid_from": "2021-11-10T05:56:52.470Z3",
    "valid_until": "2023-11-09T05:56:52.470Z7",
    "updated": "2021-11-09T13:15:58.349Z11"
}
```

7. A ngrok instance is required to be running locally to publish to the internet

```
   brew install --cask ngrok
   ngrok http 5555
```

8. Copy the url to the clipboard and paste in BAP_URL and PROTOCOL_BASE_URL in .env-local.

9. Run
   **docker-compose -f docker-compose-for-local.yaml --env-file .env-local up -d**

10. Open [http://localhost](http://localhost).

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Deployment

### Prerequisites

- For the white label app, ONDC has used ansible to deploy and generate ssl certificates.
- The public key of the node to generate ssl and make it available for the seller apps to identify the buyer app.
- Docker and docker compose needs to be installed.
- Access to github repository to clone.
- Create a copy of .env-local with valid credentials and name it .env-<stagename>. E.g. .env-prod.

### How to use ansible

First ansible is to install the apps and generate ssl certificate

```
  CMDs (commands)
     ansible-playbook -i ansible_hosts buyer-app-install-for-ssl.yaml

  it will ask for
	 Hostname - which needs to be mentioned in hostname file

  it will ask for domain to host
     E.g. buyer-app.ondc.org

  it will ask for stage name, which is used to copy the .env file, to copy
     If a env file of .env-prod is already created, then prod

```

- Try to run to generate lets encrypt ssl certificates

```
ansible-playbook -i seller-app-install-for-ssl.yaml
```

- Once above ansible playbook is successfully installed we can run

```
ansible-playbook -i seller-app-run.yaml

```

## License

This project is licensed under the ONDC - see the [LICENSE.md](LICENSE.md) file for details.
