# Prerequisites
* Intel System Studio for Quark D2000 (Requires an Account) https://software.intel.com/en-us/intel-system-studio-microcontrollers/download
* Intel® Quark™ Microcontroller Developer Kit D2000 (Or supported JTAG adapter) https://www-ssl.intel.com/content/www/us/en/embedded/products/quark/mcu/d2000/sample-and-buy.html
* DEFCON 24 Badge

# Setup
 1. Wire your DEFCON 24 Badge to the JTAG pins on your Developer Kit. More info can be found at wired to JTAG http://diyevil.com/reprogramming-the-defcon-24-badge/
 2. Install & launch ISSM, and import this repo as a project.
 3. Update your Badges firmware. This is done from `Project > Update Microcontroller ROM` and then set it to "D2000" and "QMSI 1.1".
 4. Once updated, you can then build & flash the new firmware to your badge.
