
# ipm package: mailer-example

## Overview

Example for sending SMTP based emails from a ClearBlade service.

This is an ipm package, which contains one or more reusable assets within the ipm Community. The 'package.json' in this repo is a ipm spec's package.json, [here](https://docs.clearblade.com/v/3/6-ipm/spec), which is a superset of npm's package.json spec, [here](https://docs.npmjs.com/files/package.json).

[Browse ipm Packages](https://ipm.clearblade.com)

## Setup

You must have an email account, such as GMail, and its STMP Host address.

## Usage

Enter your configuration in the `MailerConstants` Code Library:

```

    const ORIGIN_EMAIL_ADDRESS ="<ORIGIN_EMAIL_ADDRESS" // ex. youremail@gmail.com
    const ORIGIN_EMAIL_PASSWORD = "<ORIGIN_EMAIL_PASSWORD>" // ex. "K1LL3RPW"
    const RECIPIENT_EMAIL_ADDRESS = "<RECIPIENT_EMAIL_ADDRESS>" // ex. "recipient@gmail.com"
    const host = "<HOST>" // ex. "smtp.gmail.com"
    const port = "<PORT>" // ex. "587"

```

## Assets

### Code Libraries

`MailerConstants` - A constants library to have a centralized location for constants like API-key.

### Code Services

#### Example

`MailerExampleSend` - sends an email with configuration from above
#### Test

`MailerTestSetup` - Tests if the constants for mailer library are set or not.

## API

[docs.clearblade.com](https://docs.clearblade.com/v/3/4-developer_reference/platformsdk/mailer.js/)