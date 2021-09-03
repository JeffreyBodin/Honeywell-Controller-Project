# 2021-09-03

**Honeywell Controller Project**

-----

## Overview

### // 'HWCONFIG'

Is a filesys that contains the actual ".XML"

Containing the actual:

- "modulating controller"

  &&

- "installer settings"


#### (Procedure for Dual Systems)

- Load installer settings from the USB connection.
- On **your** primary (ie largest connected to controller) air unit.
- MY primary happens to be on my 1st floor. Ie MY "downstairs" controller.

- Then load **this** versioning. To your secondary (MY "upstairs") controller.
- To *ensure* a syncronized at the **primary**
  - Airs Circulation

    &&
  - Fire Suppression Controls

- Which is *then* what's used for the below `'HowTo'`


### // Honeywell Firmware

Website: `https://thermostatsetup.com/thermostat_setup/en/prestige/software`

- downloadLink (1)(v-Advanced-Controller)

  `'https://thermostatsetup.com/thermostat_setup/en/prestige'`

- downloadLink (2)(v-Basic-Controller)

  `'https://thermostatsetup.com/thermostat_setup/en/vision_pro'`

  (1)

  This ^ one is used to error the controller's maintenance mode.

  Allowing a manual selection for the manufacturer.

  To flash software && over-ride in appropriate `"good faith"`.

  (2)

  It *is* **included** in the filesystem.

  That **you** fork from this repo.

  To proceed.

-----


## /* Instructions on HowTo Flash Honeywell Controller */

### // 0
Remove battery from back on the "Honeywell Controller"

### // 1
Plug flash drive into the bottom of the controller

### // 2
Hit 
-> `'Load installer settings'`

### // 3
Enter the installer password
  Note (1)
  - Is the "Date Code" 
  - Listed in the details
  - For installed controller (in the UI)
  Note (2)
  - Date code is '1850'

### // 4
Load the contents of
-> `/ HWCONFIG /`

Specifically the "XML" file of
-> `'ISUCON00.XML'`
    
   Displayname:
   `20210703installerSetupDownloadToUsb`
   - ^ Should be shown on UI
     
   Model:
   `THX9001R5029`
   - For ^ model of the Honeywell Controller

### // 5
Select the displayed

-> Configuration

--> `'20210703installerSetupDownloadToUsb'`

*There is a single selection. Corresponds to the `'ISUCON00.XML'`.*

### // 6
Load `'20210703installerSetupDownloadToUsb'` as the firmware.

For this installation as an "installer". To **your** controller.

Ie
- You are overwriting the previous "configured" firmware 
- With **MY** `'20210703installerSetupDownloadToUsb'` versioning

- MY default is

  // Configured for my `epilepsy` + `neuropathy`

  🔃 onLoad 🔃
  
  ```js
  // Is
  -> Unlocked
  -> 75 min && 82 max
  -> Recurring scheduled (Twice daily)(0200 && 0700)
  ```

### // 7
In Review
- You should have...
  
  [✅] Reset your Honeywell Controller

  [✅] With `'20210703installerSetupDownloadToUsb'`

- You should be...

  [✅] Looking at an unlocked screen

  [✅] Looking at an unlocked screen with full interactibility

  *Of*

  ▶ "UI Elements"

  ▶ "Mutability" (Displayed Values)

- If this resolves to...

  [✅] `'TRUE'` Looking at an unlocked screen with full interactibility

  [🥳] Congratulations! You've succeeded!

-----

# LICENSE

```js
Honeywell Controller Project - README.md
2021-09-03
v.1.0.0

MIT License
Copyright (c) 2021 Jeffrey Bodin
```

-----
