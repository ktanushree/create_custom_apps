# CloudGenix Create Custom  Applications (Preview)
This utility is used to create custom applications on the cloudgenix fabric.

#### Synopsis
This script enables custom app creation using YAML config files. See sample config.yaml file attached for format.

#### Requirements
* Active CloudGenix Account
* Python >= 2.7 or >=3.6
* Python modules:
    * CloudGenix Python SDK >= 5.4.3b1 - <https://github.com/CloudGenix/sdk-python>
    * CloudGenix ID-Name Utility >= 2.0.1 - <https://github.com/ebob9/cloudgenix-idname>
* ProgressBar2

#### License
MIT

#### Installation:
 - **Github:** Download files to a local directory, manually run `createapps.py`. 

#### Usage:
Create Custom App from YAML config fille:
```
./createapps.py -f filename 
```

#### Help Text:
```
usage: createapps.py [-h] [--controller CONTROLLER] [--email EMAIL]
                     [--pass PASS] [--configfile CONFIGFILE]

CloudGenix: Create Custom Apps.

optional arguments:
  -h, --help            show this help message and exit

API:
  These options change how this program connects to the API.

  --controller CONTROLLER, -C CONTROLLER
                        Controller URI, ex. C-Prod:
                        https://api.elcapitan.cloudgenix.com

Login:
  These options allow skipping of interactive login

  --email EMAIL, -E EMAIL
                        Use this email as User Name instead of prompting
  --pass PASS, -P PASS  Use this Password instead of prompting

Custom Application specific information:
  Information shared here will be used to create custom applications

  --configfile CONFIGFILE, -f CONFIGFILE
                        YAML file containing application details
```

#### Version
| Version | Build | Changes |
| ------- | ----- | ------- |
| **1.0.0** | **b1** | Initial Release. |


#### For more info
 * Get help and additional CloudGenix Documentation at <http://support.cloudgenix.com>
