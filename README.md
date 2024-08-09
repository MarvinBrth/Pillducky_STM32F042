# Pillducky_STM32F042

### This Pillducky is powered by an STM32F042 microcontroller, chosen for several key reasons:

- WLCSP-36 Package: The microcontroller comes in a compact WLCSP-36 package, ideal for space-constrained designs.
- Internal HSE: The internal High-Speed External (HSE) oscillator is crucial for supporting the USB Full Speed (FS) protocol. The inclusion of this internal HSE eliminates the need for an external oscillator, further conserving board space.
- Programming Method: The PCB is programmed via Serial Wire Debug (SWD) using the STM32CubeIDE. This method provides a streamlined and efficient programming process.
- Space-Saving Design: To optimize the layout and save space, the PCB features programming test points on the underside, allowing for easy access without occupying additional surface area.
  
### USB Protokoll:
- There are intentionally no 20-ohm termination resistors on the D+ (Dp) and D- (Dn) lines.
- No pull-up resistor is placed on the D+ line.

According to the datasheet, these components are already integrated into the USB driver within the microcontroller, making external resistors unnecessary.

### Warning!
Project is still in the production phase

## Schematic

<img width="627" alt="image" src="https://github.com/user-attachments/assets/524b948e-120d-4719-93ce-04cdddc6cf30">

##Layout

<img width="1138" alt="image" src="https://github.com/user-attachments/assets/ccf5f5f4-4870-44f0-8f9f-cdfea1becc92">

##3D-Model

<img width="1085" alt="image" src="https://github.com/user-attachments/assets/fd669dc9-d87f-4db5-8bbb-5a6d566b70a6">

##Programmming Adpater

<img width="547" alt="image" src="https://github.com/user-attachments/assets/1aaaa5c0-2329-447e-bf4b-573a3150b5e7">
