raspberry-funai
===============

Raspberry Pi configuration for Funai LH840 M32 (hdmi)

This is the config.txt I use at home. It also contains some parameters not related to hdmi such as moderate overclocking. 

How to figure the correct HDMI configuration values out?
--------------------------------------------------------

Attach a Laptop to the TV via HDMI and select a working screen resolution. Then press the Info Key on the TV remote. A small black info box should appear with values like: "1360-768 60HZ".

Now you can lookup the hdmi_group and hdmi_mode parameters in http://elinux.org/RPiconfig#Video_mode_options

License
-------

Public Domain. See License.md.
