# nz.co.fuzion.xerotrackingcategories

Push tracking category of contribution from the value stored in the related financial type.

The extension is licensed under [AGPL-3.0](LICENSE.txt).

## Requirements

* PHP v5.4+
* CiviCRM

## Installation (Web UI)

This extension has not yet been published for installation via the web UI.

## Installation (CLI, Zip)

Sysadmins and developers may download the `.zip` file for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
cd <extension-dir>
cv dl nz.co.fuzion.xerotrackingcategories@https://github.com/FIXME/nz.co.fuzion.xerotrackingcategories/archive/master.zip
```

## Installation (CLI, Git)

Sysadmins and developers may clone the [Git](https://en.wikipedia.org/wiki/Git) repo for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
git clone https://github.com/FIXME/nz.co.fuzion.xerotrackingcategories.git
cv en xerotrackingcategories
```

## Usage

- Install the ext and set Description of the financial type to `TC:<tracking_category_name>=<tracking_category_option_value>`
- Create a contribution with this financial type.
- When the payment is pushed to xero, the tracking category value is also pushed along with the invoice.
