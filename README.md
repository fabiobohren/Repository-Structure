Scanbot SDK Logo

# Barcode Scanner SDK Example App for React Native
This example app demonstrates how to integrate the Scanbot React Native Barcode Scanner SDK for Android and iOS.

## What is the Scanbot Barcode Scanner SDK?
The Scanbot Barcode Scanner SDK is a simple and intuitive high-level API that turns mobile devices into reliable barcode scanners. 

It operates entirely offline and takes only 0.04 seconds per scan. Scans remain precise even under challenging conditions, including damaged, small, or distant barcodes, as well as low-light environments.

The SDK can be integrated into your app within minutes and comes with customizable Ready-To-Use UI components. 


(UI Screenshots are going here)


💡 For more details about the Scanbot Barcode Scanner SDK for React Native please check out our [documentation](https://docs.scanbot.io/barcode-scanner-sdk/react-native/introduction/).

## How to run this app

### Step 1: Install Command Line Tools

> **Note**: Make sure you have completed the [Set Up Your Environment](https://reactnative.dev/docs/set-up-your-environment) guide before proceeding.

### Step 2: Install Dependencies

To install the project dependencies, run the following commands

```bash
# Install the required dependencies
yarn install
# OR using npm
npm install
```

For iOS, remember to install CocoaPods dependencies (this only needs to be run on first clone or after updating native deps).

The first time you create a new project, run the Ruby bundler to install CocoaPods itself:

```sh
bundle install
```

Then, and every time you update your native dependencies, run:

```sh
cd ios 
bundle exec pod install
```

### Step 2: Start your Application

Plugin in your physical device via USB and run the following command to start your _Android_ or _iOS_ app:

#### For Android

```sh
# Using npm
npm run android

# OR using Yarn
yarn android
```

#### For iOS

```sh
# Using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up correctly, you should see your new app running in new app running on your device.

This is not the only way to run your app — you can also run it directly from within Android Studio and Xcode respectively:


#### What else can go wrong?

##### Pod not found

```bash
cd ios
bundle exec pod repo update
```

##### Still at a loss? It is probably a cache issue

```bash
yarn run clean
```
* `npm cache clean --force && watchman watch-del-all`
* Restart metro server!


## Features

### Out-of-the-box scanning modes
Our SDK offers the following scan modes, available out-of-the box in our ready-to-use UI:
- Single scanning 
- Batch Scanning
- Multi Scanning 
- Find & Pick 
- Scan & Count
- Barcode Vision

(UI Screenshots are going here (Batch Scanning, Multi Scanning, Find & Pick))

### Supported barcodes
The Scanbot Barcode Scanner SDK supports all common 1D- or 2D barcodes and multiple postal symbiologies. 

| Barcode type | Barcode symbologies |
| :-- | :-- |
| 1D Barcodes | EAN, UPC, Code 128, GS1-128, Code 25, Code 39, Cide 32, Code 93, Code 11, Codabar, MSI Plessey, Standard 2 of 5, ITF, IATA 2 of 5 |
| 2D Barcodes | QR Code, Micro QR Code, Aztec Code, PDF417 Code, Data Matrix Code, MaxiCode, NTIN Code, PPN Code, UI Code |
| Postal Symbologies | USPS Intelligent Mail Barcode, RM4SCC Barcode, Australia Post 4-State Customer Code, Japan Post 4-State Customer Code, KIX |

💡 Please visit our [docs](https://docs.scanbot.io/barcode-scanner-sdk/react-native/supported-barcodes/) for a complete overview of the supported barcode symbologies.

## Additional information

### Free integration support
If you require help with integrating or testing our Barcode Scanner SDK, we offer [free developer support](https://docs.scanbot.io/support/) through Slack, MS Teams, or email.

Additionally, existing customers have access to a dedicated support Slack- or Microsoft Teams-Channel to directly talk to your dedicated Customer Success Manager and our engineers.

### Licensing and pricing
The Scanbot SDK example apps will run for one minute per session without a license. After that, all functionalities and UI component will stop working. To try the Scanbot SDK without a one-minute limit, you can request a free, no-strings-attached [7-day trial license](https://scanbot.io/trial/).

Our pricing model is simple: Unlimited barcode scanning for a flat annual license fee, full support included. We have no tiers, usage charges, or extra fees. [Get in touch](https://scanbot.io/contact-sales/) with our team to receive your quote.

### Other supported platforms

(Links to the other platforms coudld be incldued here)


