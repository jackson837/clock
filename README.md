# Robotics-Clock-
Team 7688 Robotics clock

i built A laser-cut mechanical clock powered by Arduino, servo motors, and a 9v batter.
the reason i built it was because i wanted to build something that i that looked attractive, and that me friends will also like.
the clock works like other clocks. just with it's own special feature. my plan was'nt focused on making a real clock. i just wanted to make a master piece.

Overview

The Clock is a custom-designed wall clock created by me. and inspired by FIRST Robotics Team 7688, steampunk clocks, and astronomical watches such as the Jacob & Co. Astronomia.

Although the clock looks like a vintage mechanical timepiece, it is actually powered electronically using an Arduino uno board and servo motors.

My project combines:

Mechanical (Gears)
Electronics
CAD Design
Laser cutting
3d printing
Programming
a bit of art
Features

The overall shape is based on Team 7688's compass logo.

Instead of traditional clock hands:

The "N" on the compass points indicate the hour The arrow inside indicates the minutes

Mechanical Appearance

Although electronically controlled, the clock was designed to look fully mechanical.

Features include: Exposed gears Wooden gear train Black acrylic Layered construction Laser engraved details

The planets rotate to create the illusion of an astronomical mechanism while giving the clock additional movement and personality.

Planetary Gear Train

A functional planetary gear train sits on the lower-right or top right side of the clock.

It consists of

Ring Gear, Sun Gear, Three Planet, Gears Carrier

Hardware Component Purpose Arduino uno Main controller Servo Motors Time movement.

Software The clock is programmed using the Arduino IDE.

CAD Design
The clock was designed in Fusion 360.
<img width="751" height="726" alt="Screenshot 2026-06-17 201907" src="https://github.com/user-attachments/assets/673202bd-5827-40fb-aef9-197f48c0f620" />


Prototyping
Multiple versions were produced to improve

alignment, aesthetics, gear movement, clearance, pitch diameter

schematics where desighed on kecad
<img width="871" height="612" alt="Screenshot 2026-06-20 090412" src="https://github.com/user-attachments/assets/472966a1-3f27-4b70-ac00-d62931201a4f" />


Manufacturing Parts were laser cut from plywood.
Additional components were assembled using spacers acrylic wood double sided tape

to recrete te clock you just rebuild it with the fusion files since most part are 3d printable even where i used wood or acrylic and when you done you send the clock.ino code to the servo to get it working. 
Note make sure you servo is a 360 servo that the angle can be control not just speed and direction
 BOM:
 servo       https://leeselectronic.com/en/product/4871-servo-motor-mystery-9g-180-degree.html               $14
 
 arduino     https://www.aliexpress.com/item/1005007938089405.html?spm=a2g0o.productlist.main.2.2ff15d12TcZ0vn&algo_pvid=4684835c-3082-45c3-81eb-b2de130a6515&algo_exp_id=4684835c-3082-45c3-81eb-b2de130a6515-1&pdp_ext_f=%7B%22order%22%3A%224928%22%2C%22eval%22%3A%221%22%2C%22orig_sl_item_id%22%3A%221005007938089405%22%2C%22orig_item_id%22%3A%221005011825851194%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%2116.30%216.54%21%21%2176.40%2130.64%21%402101e80317819440413298850ecd50%2112000042938202250%21sea%21CA%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Af8a9fc6%3Bm03_new_user%3A-29895%3BpisId%3A5000000204872240&curPageLogUid=959VWFvBP1b5&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007938089405%7C_p_origin_prod%3A1005011825851194       $6.54

 
