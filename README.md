# The Winnand TKL Keyboard

This project is a custom keyboard based off of JoeScotto's guides from YouTube. It is a standard TKL Board which replaces the Pause key with a rotary encoder. It uses QMK with Vial support for on-the-go layout customization.

I made this project because I enjoyed the idea of having a keyboard that I made myself, with the features and rigidity of a top-of-the-line keyboard. I hoped that it would teach me more about firmware and microcontrollers for future projects, and have a good keyboard that I would be able to use for many years to come. 
<img width="1223" height="677" alt="Full CAD" src="https://github.com/user-attachments/assets/aa4686e4-e856-4781-8289-2050a99bfdb3" />
<img width="1723" height="892" alt="KeyboardPCBFrontBare" src="https://github.com/user-attachments/assets/09af4ce8-4af9-4c54-8788-571676cf2fba" />
<img width="1291" height="772" alt="Isogrid" src="https://github.com/user-attachments/assets/e73ce0b4-bae2-4627-b8e4-f4df18ab9a5c" />
<img width="1920" height="632" alt="KB Case Full" src="https://github.com/user-attachments/assets/79de21a6-1e4d-4add-b55a-f04d7a10a52d" />
<img width="1920" height="632" alt="KB Case Render 1" src="https://github.com/user-attachments/assets/c57974de-550b-4651-8d2b-7458faba1322" />
<img width="1920" height="632" alt="KB Plate Underside" src="https://github.com/user-attachments/assets/252d0917-ca76-45f1-afd3-0dc71d53c71b" />
<img width="1920" height="632" alt="KB Plate" src="https://github.com/user-attachments/assets/99084244-e884-428c-8500-02aec92eaa6a" />
<img width="1723" height="892" alt="KeyboardPCBBackBare" src="https://github.com/user-attachments/assets/fe202a8c-4a5b-41f1-8451-32272871bbe3" />
<img width="1723" height="892" alt="KeyboardPCBFrontBare" src="https://github.com/user-attachments/assets/73c4d3fa-4924-41ba-be35-4c158a783962" />

BOM in table format at the end of the README

# Build Instructions
1. Watch a few keyboard building guides on YouTube, read the instructions, then download and extract the latest package

2. Print out all the step files

3. Order/gather the parts in the BOM.csv. You can get the PCB's from JLCPCB using the Gerbers.zip

4. Use superglue or any other adhesive to join together the 2 halves of the top plate

5. Use superglue or any other adhesive to join together the 2 halves of the case

6. Insert all the switches into the top plate, making sure they are aligned such that they will go into the pads on the PCB

7. Solder in all the diodes and make sure that they are in the correct orientation

8. Solder in the Raspberry Pi such that the USB port faces left, inwards to the PCB

9. Solder in the rotary encoder, making sure the encoder part is on the top side

10. Place the top plate with switches onto the PCB and align all the pins into their holes

11. Solder in the switches

12. Insert the adapter into the Raspberry Pi. If it doesn't fit, sand down the side that interferes with the PCB

13. Screw in the other side of the adapter into the inside of the case using the screws included in the package

14. Put in the heatset inserts into the keyboard case

15. Use the M2 screws to screw the PCB into the case. Make sure the adapter wire is routed through the routing passage in the case and use loops to deal with extra cable length

# BOM

|Part #                                    |Min. Quantity |Name on Seller Website                                                                                                          |Description      |Link                                                  |Color/Size                                              |Quantity|Unit Price ($)|Total Price ($)|Running Total ($)|
|------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------|-----------------|------------------------------------------------------|--------------------------------------------------------|--------|--------------|---------------|-----------------|
|MX-keyboard switches                      |86            |GATERON G Brown Pro 3.0 Pre lubed Keyboard Switches 55gf 5pin Tactile RGB Light for MX Gaming Mechanical Keyboard (90pcs, Brown)|Keyboard Switches|https://www.amazon.com/dp/B0DMPKTMPH/                 |90 pcs, Brown                                           |1       |$24.99        |$24.99         |$24.99           |
|DO-35 Diode                               |87            |100pcs 1N4148 DO-35 IN4148 High-Speed Diode Switching Diodes New                                                                |Diodes           |https://www.aliexpress.us/item/2255799955957794.html  |                                                        |1       |$1.47         |$1.47          |$26.46           |
|EC11 Rotary Encoder                       |1             |5PCS/LOT 20 Position 360 Degree Rotary Encoder EC11 w Push Button 5Pin Handle Long 15/20MM With A Built In Push Button Switch   |Rotary Encoder   |https://www.aliexpress.us/item/3256805796819763.html? |20MM Half handle                                        |1       |$3.30         |$3.30          |$29.76           |
|Raspberry Pi Pico                         |1             |Raspberry Pi Pico                                                                                                               |Microcontroller  |https://www.sparkfun.com/raspberry-pi-pico.html       |                                                        |0       |$4.60         |$0.00          |$29.76           |
|Micro USB male to panel mount USB C female|1             |USB 3.1 Type C Micro Usb2.0 With Panel Mount Screw Extension Cable Cord USB C Male To Female Extending Wire Extender Data Cord  |Adapter Cable    |https://www.aliexpress.us/item/3256806244885684.html  |A3                                                      |1       |$2.69         |$2.69          |$32.45           |
|M2 x 6mm Button Head screw                |11            |10/50pcs M1.6 M2 M2.5 M3 M4 M5 M6 M8 Black Grade 10.9 Steel ISO7380 Hexagon Hex Socket Head Button Mushroom Allen Bolt Screw    |Mounting Screws  |https://www.aliexpress.us/item/2251832782727837.html  |Size: M2 (50pcs) Length: 6mm                            |1       |$1.07         |$1.07          |$33.52           |
|MX Keycaps                                |TKL Layout    |104pcs ABS Universal Mechanical Keyboard Keycaps Ergonomic Blank Keycaps For Cherry MX Keyboard Replacement OEM Backlit Key Cap |Keycaps          |https://www.aliexpress.us/item/3256808802544300.html  |Red black                                               |1       |$11.48        |$11.48         |$45.00           |
|Plate Mount Stabilizers                   |1x 6.25U 4x 2U|KEYCOOL V3 PCB Plate Mounted Stabilizer for Gaming Mechanical Keyboard Lubrication Satellite Switches for 1.2mm 1.6mm PCB 6.25U |Stabilizers      |https://www.aliexpress.us/item/3256808467378574.html  |Black 4 in 1                                            |1       |$3.01         |$3.01          |$48.01           |
|M2, OD4mm Heatset Inserts                 |11            |M2 M2.5 M3 M4 M5 M6 Brass Hot Melt Insert Knurled Nut Thread Heat Molding Double Twill Injection Embedment Nut For 3D Printer   |Heatset Inserts  |https://www.aliexpress.us/item/3256803396040989.html  |Size: M2(OD4mm)  Color: Length 5mm 50pcs                |1       |$2.27         |$2.27          |$50.28           |
|Winnand-TKL PCB                           |1             |JLCPCB                                                                                                                          |PCB              |https://cart.jlcpcb.com/quote?spm=Jlcpcb.Homepage.1006|Defaults except: PCB Color: Black Via Covering: Untented|5       |$4.16         |$20.80         |$71.08           |

