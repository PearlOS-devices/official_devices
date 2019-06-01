--------------------------------------------------------------

--------------------------------------------------------------

Guide for maintainers:-
======================

• After Building the ROM push to sf then folllow the procedures given below:-

If U added Your SSH key then use this -
-------------------------------------

```bash

cd ~ && wget https://raw.githubusercontent.com/PearlOS-devices/official_devices/pie/OTA.sh

```

Then

```bash

bash OTA.sh <device_codename> pearl

```

Example - bash OTA.sh mido pearl.



If U didn't added Your SSH key then use this -
--------------------------------------------

```bash

cd ~ && wget https://raw.githubusercontent.com/PearlOS-devices/official_devices/pie/Maintainers.sh

```

Then

```bash

bash Maintainers.sh <device_codename> pearl

```

Example - bash Maintainers.sh mido pearl.
