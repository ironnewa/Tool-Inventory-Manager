# Tool-Inventory-Manager
Design and implementation of a tool organization device.
This system is in early development.

## General
This system is used to monitor tool inventory and usage. 
It tracks tools usage via user ID-checkout logging.
It's purpose is to help improve storage consistency and prevent tool misplacement.

## Hardware

| Component      | Details            | BOM #      | Notes                                                                             |
| :------------- | :----------------- | :--------: | :-------------------------------------------------------------------------------- |
| Processor      | RPI 4-B            | N/A        | This is overkill.                                                                 |
| Display        | rPi HDMI 7" screen | B09MFNLRQQ |                                                                                   |
| RFID           | 3.56MHz            | B01HFWQGVM | This will be expanded to a secondary scanner to include 125kHz in the future.     |
| KBM            | mini rPi keyboard  | B07S7BQMRY |                                                                                   |
| Relay Hub      | 8 channel relay    | B076CQJBSH |                                                                                   |
| Solenoid Locks | 12V/350mA          | B093H6GD4V |                                                                                   |

## Software Dependencies
 - RPi OS
 - Qt C++

 ## Disclaimer
 - This uses a free license of Qt
