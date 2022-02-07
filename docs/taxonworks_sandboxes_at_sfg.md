---
layout: default
---
# Sandboxes
The Species File Group has numerous sandboxes for testing and training purposes.  Their role is described here.  Sandboxes are online (web accessible).  

_Note that with a [few simple commands](https://github.com/SpeciesFileGroup/install_taxonworks/blob/master/development/docker/README.md) you can run TaxonWorks offline for development and testing purposes._

# Guidelines 
* **Data in sandboxes are never transferred to production ("real") instances of TaxonWorks**.  Sandboxes are not part of a workflow that prepares your data for production use, beyond practicing to see what it might look like in TaxonWorks.
* It's a sandbox, things made of sand are fragile and will melt away in the wind and water.
* What you see may be different in the end product, or it might not be there at all.
* The data you add WILL BE WIPED from time to time, we make no promises for the length of time it will be live. It might be there for days, or minutes. We will not announce wipes.
* You can do whatever you want, including deleting data, or modifying any data.
* The data you add may be altered by others.
* Others will see exactly what you are seeing.
* The sandbox may or may not be live, our goal is to have it down no more than one full day before it's live again. Typically, however, if the sandbox is down you can expect it to be live within an hour or two.
* The sandbox may contain features that may not be live in production.
* The sandbox contains features on the main development branch maintained by the Species File Group only, other branches increasingly include major new features that are not included.
* The collective data of the sandbox may be shared with other TaxonWorks developers via database dumps.
* Even though it is a sandbox, please do not share your accounts. Using your own account will help us better understand the behaviour of the software.
* It goes without saying (but we will anyways) that you should not put any sensitive information in the sandbox, including passwords that you would use elsewhere.
* Sandbox account use is tracked in several ways. We record information about the last IP you used to connect from, the time of last login, when the account was last seen accessing the sandbox, and an estimate of the time spent in the application.

# Getting started
Your username is your email.  You will need to request a password change to logon.  Check your email after you do for instructions on updating your password.

_Remember, some aspects of what you see are in early development in terms of the user interface (UI) and user experience (UX).  Features in sandboxes may not make it to production._

* The quickest way to get other feedback is to contact us on the [TaxonWorks Gitter channel](https://gitter.im/SpeciesFileGroup/taxonworks).
* Features seen on [@TaxonWorks Twitter](https://twitter.com/TaxonWorks) may not be in the sandbox.
* We would love to hear from you, see [Contributing](https://github.com/SpeciesFileGroup/taxonworks_doc/blob/master/CONTRIBUTING.md).

You may be flagged as an administrator.  Administrators can do *everything* in the workbench.   If you are flagged as an administrator ("Adminstration" link visible on top right):
* Feel free to add users to the sandbox through the "administrator" link.  If you do, please provide them a link to this page.
* Feel free to add yourself to projects that are currently not visible to you:
```
  "Administration" (top right) -> 
     "Projects overview" (on left) -> 
     "List" -> 
     Double click a row -> 
      "Add project member" 
```

# Troubleshooting

## Disappearing images, broken image links
Image records are not wiped during software updates, by image files *are*.  In other words don't depend on seeing your images for very long in a sandbox.

## Unable to logon
* We do our best to maintain users across sandbox wipes, however your account may be wiped. If you can not request a new password request a new sandbox account.
