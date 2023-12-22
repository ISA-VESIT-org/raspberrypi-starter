# Table of Contents

1. [Setting Up Raspberry Pi](#setting-up-raspberry-pi)
2. [Components Used](#components-used)
3. [Description](#description)
4. [Setup](#setup)
   1. [VNC Viewer Setup](#step-1---installing-vnc-viewer)
   2. [PuTTY Setup](#step-2---installing-putty)
   3. [Imager Setup](#step-3---installing-imager)
   4. [OS Customization](#os-customization)
   5. [Creating SSH File](#creating-ssh-file)
5. [Notes](#notes)

</details>

# Setting Up Raspberry Pi

- Links for Downloading Few Software required for setting up Raspberry Pi

1. [Rufus](https://rufus.ie/en/#google_vignette)
2. [VNC Viewer](https://www.realvnc.com/en/connect/download/combined/)
3. [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
4. [Raspberry Imager](https://www.raspberrypi.com/software/)

## **Components Used**

- [Raspberry Pi 4B](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/)

## Description

**Overview of Pin Diagram**
![](https://lh7-us.googleusercontent.com/GxUcjuIc7cna_f5zu6YPBiplcnbs60MwNlGVE9ud7A4mUIsfRdJnEZIjYBhm_y7UpKY9laor7EisOVhP9gmK5v_devnKkNVzQhvOalbLjnhgC32s6mlYfSZ-N1dMYORap4CpUuTVM8f02Jji4rgv9NU)

## Setup

### Step 1 - Installing VNC Viewer

![](https://lh7-us.googleusercontent.com/IRuqDlm4tdNWvnbNuwofFzjISJVurpskLP5iYkz7TChpR_L-dNAPJk3Yck_zLcl5RCpLoD7HvqxGd7_uQ06Aei1PYBL-jj78mT6fgUydxj9zZoHQeHWVC15tgGofi8OC3bEmLVA4soLSPrZ7Ca48cpw)<br/>
![](https://lh7-us.googleusercontent.com/iYS9JCBPJkc3EXJXWUtPEOkq-HPyXV99NJ6kUbZ5WKmmXq1jYSNbYN5HiD7xQ6eSlEshMMFHoyoLHukowaUJT6fIITurYc-JeasG5-wn9qY0FIAs3FxI5HOTtP9mEdQR72i8-P6ftBa_1C_ApP-Kn_E)<br/>
![](https://lh7-us.googleusercontent.com/PUzhIFmW27DI4eHZhZyUdyhV9YsnNeg3OhtTDkabGhHDn1-hrg-WGSI1vxGolRksVriG_wH5jhYwNlnM-EcvyMtm3Qvb4BYQqxju3vhIul9277X-V7y4KMnjCcoPmUQjJ_m8OkG22HaI16xWMYcSDDk)<br/>
![](https://lh7-us.googleusercontent.com/y1cPVq7BViP0Lwbn29pzXjFnPIkl3AOa4FYwEWB81Sjy_c09fjBjMx2QWBxrYSFhiqtyFkUk2pYNpC-CP81sztZCMLye9AO8pk-eYcHNiUijtz-kln3xnMuor0g9MCBHapM6-UgpQ-y1wTyb27E5yTo)<br/>
![](https://lh7-us.googleusercontent.com/l7aoZeP_L-UkuFyT6W1CHjKKANkPpRUc-SFbY_67D7uZI8OWgo6uyHotxHY1OYLaFhdqp7XRkQyofCpmLvoM2CxsE2uzrmT4r18wjCfM4PDf39ewN0xEajtqHD-UeusLq02h5EJLin_7-PtG_b__mco)<br/>
![](https://lh7-us.googleusercontent.com/pS9la1OEsDGsGRxnVp1Blc_YGwj2esi4sg8gGUtR6bTUJT_06xRTd5qoLNTPbkNXdwHteydE0OoXJmaiMLUtxdIFj70Z_IqxBmhSzyiS9o-kjw5QVS_AAMJ1Av39OFD_3zI6fRGvdJWlOHynEgi6gnQ)<br/>
![](https://lh7-us.googleusercontent.com/PCAuMfL8FMmLi0H1hX0HP6LA_1jvjhzpI0yXq1LZoKb5MB6vHvOCENoBdtNjpmGVj2k454zrMNvE0JF1u8z1UjghBqpZsWxY2C15CKqE6Oweb-LCa3CjA0FfH6GBABWJXM3svYNf1iq4d3wf7Dj9uEA)

### Step 2 - Installing PuTTY

![](https://lh7-us.googleusercontent.com/TQ6gl8vSRYJKGc8thOfdlmc6sEgy6UC_V7yejXMLammg9N9gWOAb2mLIwDbLiFMIRWmzUm0AZnkKTBPezw_tBDR8vGrbmF5VChEq00A9di9QiysP5bFR-LmcjTxGH-vJ1tlDehIBPH0P0Tt97jmjXPw)<br/>
![](https://lh7-us.googleusercontent.com/wxEZoKAW9k0NmsrcZfFmuosXFaldFXvz0VUdm4z0xuznTA94jfqAdVS3z-irbMjAepGgo8O_4AGhHpaaAS7OsmqR0ApS03d6HukzLtf7V4lXhCEX41maAfw3EP0tLAPYK_Y7cGXQ-pgwPahzn1i9vTE)<br/>
![](https://i.imgur.com/9mkAGSY.png)<br/>
![](https://i.imgur.com/Fwx9c1D.png)

### Step 3 - Installing Imager

![](https://i.imgur.com/ReHZchT.png)<br/>
![](https://i.imgur.com/aceYclp.png)

1. Choose the required Raspberry Pi board as per requirements.
2. Choose the OS bit the same as your computer’s.
3. Choose the proper bootable storage device.

## OS Customization

![](https://i.imgur.com/8M6YViU.png)<br/>
NOTE: Note down the general customization (Hostname, Username, password) as it is important for further process.<br/>
![](https://i.imgur.com/OV4df9H.png)<br/>
Make sure to "Enable SSH"<br/>
![](https://i.imgur.com/6aaC3U5.png)<br/>
![enter image description here](https://i.imgur.com/XLNZKwm.png)<br/>
![enter image description here](https://i.imgur.com/Fb1vxLA.png)

### Creating SSH File

![](https://lh7-us.googleusercontent.com/qY93gIsb5czrriG4tyKY_9zuOtDuHlMwWP65o1k9Z62e1A4TXFr4hzo1YwXYpsSaKqEbreSZXnRscZXx5_Rc0vORm-xWg1ClM81B0_1QcaXdBU-te90bNeMUta8kxP0WfgQ0dLmSXudQIicPr_UCMGQ)<br/>
![](https://lh7-us.googleusercontent.com/Q9wPjwZbQhGGKD3QgOi0KJ6idsK59dWIKWABmIuh4ZwDB-ikCB7gEgXaIRDEEiyTNHC_5ZV_7i6p_wofocUmCdxgzQn0ZcFCooshVFHJRw62XlZ1_Pu9FfaN6WNveejpSRm56HhbepF0z46NY-UtI5o)
Create a new text file called "ssh"
![](https://lh7-us.googleusercontent.com/c6lA15fNZamyUGrtLWpNNlSBGsM3lubaBzenTLDJwE6wCBiCTvgYGFlOjPDMwj6u311tt81i4QKuk5RusgeLp8ae-1BvWLI59vWuS9G_ydU1R3vLsobfT5n6shxXCBFtgh7Jbf0tgIEOsZ7RoeIqH58)
Using 'Rename' option make 'ssh file' #extensionless
### Notes

- OS Customization
  Please ensure to document the hostname, username, and password details, as they are crucial for establishing a connection between your Raspberry Pi and the device using both Putty and VNC Viewer. 

1. Hostname: raspberrypi.local
2. Username: admin
3. Password: admin

#### SSH Enable

SSH, or Secure Shell or Secure Socket Shell, is a network protocol that gives users, particularly system administrators, a secure way to access a computer over an unsecured network.

#### Telemetry

Telemetry automatically collects, transmits, and measures data from remote sources, using sensors and other devices to collect data.
