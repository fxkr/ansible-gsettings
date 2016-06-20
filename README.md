# ansible-gsettings

An ansible module for managing GNOME settings.

Author: `Felix Kaiser <felix.kaiser@fxkr.net>`  
License: revised BSD (see LICENSE)  
Version: 1.0.0  


## How to use

Put it in your `library` directory, then:

```
- gsettings: schema=org.gnome.software key=download-updates value=false
```

