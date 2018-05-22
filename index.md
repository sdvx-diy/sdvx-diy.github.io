# A DIY SDVX/K-Shoot Mania Controller Guide (Work-In-Progress)
#### Last Updated: 5/21/2018

# Table of Contents  

* [About SDVX](#about-sdvx)
* [Controller Options](#controller-options)
* [Equipment List](#equipment-list)
* [Parts List](#parts-list)
* [Electrical Assembly](#electrical-assembly)

# About SDVX  
Sound Voltex is a rhythm game that originated in Japan. It mixes the standard top down four column layout of other rhythm games along with two additional columns which overlap on columns 1/2 and columns 3/4. It also incorporates two effects sliders which cross the playing field. Sound Voltex arcade machines are playable in Japan and in the United States through Round1. A PC application available for most countries as [Sound Voltex III e-AMUSEMENT CLOUD](https://p.eagate.573.jp/game/eacsdvx/iii/p/common/top.html).  

K-Shoot Mania is the main alternative to SDVX and is free to play and supports a wide variety of  input control schemes. The K-Shoot Mania Project can be found [here]().

# Controller Options  
Before you decide to build your own controller, it may be worthwhile comparing existing options. Building your controller is a rewarding experience but will often cost as much or more than commercial controllers, especially if you don't already have access to the necessary tools.

 * [Gamo2 SVSE5](https://www.gamo2.com/en/index.php?dispatch=products.view&product_id=314)
 * [Gamo2 SVRE9](https://www.gamo2.com/en/index.php?dispatch=products.view&product_id=313)
 * [Pocket Voltex](https://mon.im/sdvx/)

# Equipment List
One of the biggest obstacles to actually building the controller is having access to the necessary equipment. If you don't have access to the equipment at home or at a university, check to see if there's a hacker space nearby which might have the equipment you need.

If you have access to computerized equipment such as a laser cutter, you will be able to cut square holes and recess the buttons into the top plate of the controller. If you only have access to standard wood working tools, the buttons will have to sit on top of the top plate which only affects aesthetics and not performance.

## Recessed Button Build:
 * Laser Cutter or CNC Mill
 * Soldering Iron
 * Spade Crimping Tool (or pliers)
 * Wire Cutter

## Non-Recessed Button Building
 * Table Saw
 * Drill Press
 * Soldering Iron
 * Spade Crimping Tool (or pliers)
 * Wire Cutter

# Parts List

For most builds, I would recommend using Chinese clones over official Sanwa parts due to the steep cost of Sanwa parts. The parts which affect gameplay performance the most are the limit switches and the optical rotary encoders.

Some parts in the parts list can be substituted with other parts depending on your preferences. Please read the [limit switch weighting](#choosing-your-limit-switch-weight) section to determine which limit switch weighting is right for you.

## Full Sized Controller ($140 w/Clones):  

 * $20.00 4x [60mm Square Arcade Buttons](https://www.aliexpress.com/item/high-quality-4pcs-lot-Square-60-60mm-Lighted-Buttons-Illuminated-Push-Button-with-Micro-switch-for/32611880107.html)
 * $8.00 2x [45mm Rectangular Arcade Buttons](https://www.ebay.com/itm/Long-Rectangle-LED-Illuminated-Push-Button-For-Arcade-Video-Machines-50-33mm-Lot/263040766497?_trkparms=aid%3D111001%26algo%3DREC.SEED%26ao%3D1%26asc%3D20131017132637%26meid%3D00125b674abb4125b46ee52f972cf060%26pid%3D100033%26rk%3D8%26rkt%3D8%26sd%3D292485342918%26itm%3D263040766497&_trksid=p2045573.c100033.m2042)
 * $1.50 1x [33mm Square Arcade Buttons](https://www.ebay.com/itm/33mm-Square-Arcade-Game-Machine-Push-Button-LED-illuminated-Blue-MicroSwitch-New/292485342918?hash=item44197c26c6:g:GsQAAOSwhQtaqfX7)
 * $10.00 1x [Arduino Micro](https://www.ebay.com/itm/Micro-Board-for-Arduino-Leonardo-Mini-Controller-5V-16-MHz-ATmega32u4-Module/311838264471?epid=2266061069&hash=item489b024c97:g:LSMAAOSwWxNYtOYB)
 * $7.50 1x [Arduino Micro Breakout](https://www.ebay.com/itm/Screw-Terminal-Breakout-PCB-for-Raspberry-Pi-GPIOs-Arduino-Nano-Micro-more/142737397889?hash=item213bcfd881:m:mwdoB9ogbUTo15wtXr29XkQ)
 * $10.00 4x [100g Basic Limit Switches (Optional but Recommended)](https://www.mouser.com/ProductDetail/Omron-Electronics/D3V-6-1C24-K-6?qs=sGAEpiMZZMumBvQ1hY%2ffBTSaeneFcwBtDuZRREEUu%252bI%3d)
 * $6.00 3x [50g Basic Limit Switches (Optional but Recommended)](https://www.mouser.com/ProductDetail/Omron-Electronics/D3V-01-3C23-K?qs=%2fha2pyFadujjWXGU5Rf3WcnMSR61eELcAh360%2f3s2kY%3d)
 * $7.50 1x [100pc Spade Connector (Optional but Recommended)](https://www.ebay.com/itm/100Pcs-Fully-Insulated-Blue-Female-Electrical-Spade-Crimp-Connector-Terminal-New/182753468067?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2057872.m2749.l2649)
 * $20.00 2x [Optical Rotary Encoders](https://www.ebay.com/itm/Encoder-400P-R-Incremental-Rotary-Encoder-400p-r-AB-phase-encoder-6mm-Shaft/262600476946?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2057872.m2749.l2649)
 * $15.00 2x [6mm D-Shaft Aluminum Knobs](https://www.aliexpress.com/item/Diameter-38MM-Height-30-mm-Stalk-aluminum-knob-Volume-knob/32690174488.html)
 * $10.00 1x 48"x24"x1/4" Medium Density Fiberboard (Try to Source Locally)
 * $20.00 1x [18"x12"x1/4" Clear Acrylic (Optional & Try to Source Locally)](https://www.ebay.com/itm/CLEAR-ACRYLIC-PLEXIGLASS-1-4-X-12-X-24-PLASTIC-SHEET/281826160483?hash=item419e25ef63:g:w0IAAOSw20JZgOdh)
 * $5.00 1x [Micro USB B 2.0 Cable (May be included with Arduino)](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B07232M876/)

## Full Sized Controller (Sanwa):

* 4x [60mm Square Sanwa Buttons]
* 2x [45mm IIDX Sanwa Buttons]
* 1x [33mm Square Sanwa Buttons]* 7x [Lamp Holder]
* 7x [LED Holder]
* $7.50 1x [Arduino Micro Breakout](https://www.ebay.com/itm/Screw-Terminal-Breakout-PCB-for-Raspberry-Pi-GPIOs-Arduino-Nano-Micro-more/142737397889?hash=item213bcfd881:m:mwdoB9ogbUTo15wtXr29XkQ)
* $10.00 4x [100g Basic Limit Switches (Optional but Recommended)](https://www.mouser.com/ProductDetail/Omron-Electronics/D3V-6-1C24-K-6?qs=sGAEpiMZZMumBvQ1hY%2ffBTSaeneFcwBtDuZRREEUu%252bI%3d)
* $6.00 3x [50g Basic Limit Switches (Optional but Recommended)](https://www.mouser.com/ProductDetail/Omron-Electronics/D3V-01-3C23-K?qs=%2fha2pyFadujjWXGU5Rf3WcnMSR61eELcAh360%2f3s2kY%3d)
* $7.50 1x [100pc Spade Connector (Optional but Recommended)](https://www.ebay.com/itm/100Pcs-Fully-Insulated-Blue-Female-Electrical-Spade-Crimp-Connector-Terminal-New/182753468067?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2057872.m2749.l2649)
* $20.00 2x [Optical Rotary Encoders](https://www.ebay.com/itm/Encoder-400P-R-Incremental-Rotary-Encoder-400p-r-AB-phase-encoder-6mm-Shaft/262600476946?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2057872.m2749.l2649)
* $15.00 2x [6mm D-Shaft Aluminum Knobs](https://www.aliexpress.com/item/Diameter-38MM-Height-30-mm-Stalk-aluminum-knob-Volume-knob/32690174488.html)
* 1x 48"x24"x1/4" Medium Density Fiberboard (Try to Source Locally)
* $20.00 1x [18"x12"x1/4" Clear Acrylic (Optional & Try to Source Locally)](https://www.ebay.com/itm/CLEAR-ACRYLIC-PLEXIGLASS-1-4-X-12-X-24-PLASTIC-SHEET/281826160483?hash=item419e25ef63:g:w0IAAOSw20JZgOdh)
* $5.00 1x [Micro USB B 2.0 Cable (May be included with Arduino)](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B07232M876/)

## Possible Part Substitutions:
 * 2x [PEC16 Mechanical Encoder (Replace Optical Encoder)]
 * 4x [0.1uF Capacitors (Required for Mechanical Encoder)]
 * 7x [25g Basic Limit Switch (Use if Keeping Button Return Spring)]

## Choosing Your Limit Switch Weight
Arcade buttons will usually ship as a preassembled unit containing the arcade button, limit switch, LED lamp holder, LED fixture and LED. These arcade buttons typically come with really heavy return springs (100g - 150g) and heavy limit switches (100g - 200g). Using both of the default parts will probably be too heavy to play difficult songs with and I would recommend using either of the three following configurations.

The first recommended configuration is to completely remove the heavy return spring and to use a medium weighted limit switch. This configuration offers a light actuation force and tactile feedback upon actuation. This configuration only requires you to buy new limit switches which should be 100g - 150g for the 60mm buttons, 50g - 75g for the 45mm buttons and 50g for the 33mm buttons. You could try out this configuration with the default limit switches but these no-name Chinese switches often have a high snap-over value which causes the return force to be very weak. I recommend using Omron or Honeywell limit switches instead.

The second configuration is to keep the heavy return spring and use a lightly weighted limit switch. This configuration offers a consistent actuation force throughout the button press but has a somewhat high overall actuation force. This configuration however will be more responsive button return than the previous configuration. Since very light limit switches are very hard to find and are often very fragile, the lightest reliable switch will probably be 25g Omrons.

The third configuration is to replace the return spring with a lighter spring and limit switch. This configuration is a compromise between the previous two configurations offering the best traits of both which is a relatively light actuation force and a responsive feel to the button. This configuration is also the most expensive since you have to buy both return springs and limit switches. Return springs are hard to find and springs from Japan are often expensive with shipping.

## Custom Button Weighting
This chart displays the weight of the individual parts of the button which the switch must act against and the minimum force buffer that you must maintain for correct operation. The actuation force is roughly the summation of the return spring and the actuation force of the limit switch. The minimum actuation force required is a suggestion however choosing a lower actuation force will result in buttons which return slowly creating a sluggish feel.

Official Sound Voltex Arcade machines do not have a universal weighting for the buttons and often vary between arcades.

| Button Size | Plunger Weight | AF* w/Spring | AF* w/Spring & 25g Switch | Minimum Switch AF* Required |
|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
| 60mm Square   | 22g           | 290g          | 330g          | 100g          |
| 45mm Rectangle| 7g            | 150g          | 180g          | 75g           |
| 33mm Square   | 3g            | 150g          | 170g          | 50g           |

AF*: Actuation Force  

# Box Assembly
## Design
For the box design, we will use a layout that was originally sourced from sdvx.pancakeapps.io. Unfortunately, I have only designed boxes for use with laser cutters and if you are building a box without precision equipment, you will have to design your box from scratch.

If you have access to a laser cutter, I have created design files for two types of boxes. The standard design uses 1/4" thick medium density fiberboard for the box and uses finger joints to maintain structural integrity. The other design has a clear acrylic sheet on the top and has a MDF plate underneath it which allows for underglow lighting. This tutorial will uses the standard design without LED lighting.

* Standard Design (GitHub)
* Underglow Design (GitHub)

MDF was used as the main material for the standard design due to its strength, low cost and ease of painting. MDF however is a fairly dense wood and takes many passes with a laser cutter (8 passes in my case) and can be substituted for a different type of wood. Acrylic can also be substituted for MDF however, make sure you do not use polycarbonate as polycarbonate will create toxic gasses when laser cut.

## Painting
Since the standard design uses wood, regular oil based paint can be used. If you are using some type of plastic such as acrylic or polycarbonate, you will need to use a non-oil based paint such as acrylic paint. If oil based paint is used on acrylic or polycarbonate, the paint will dissolve the plastic.
###### Caution: Acrylic paint often contains latex which can cause allergic reactions!!!

## Gluing
Although the design was laser cut with finger joints, due to the variance of the size of the laser between laser cutters, it is unlikely that the panels will friction fit. To hold the panels together, we will glue to the side panels and the bottom panel together. Silicone or epoxy is recommended as it is strong and allows for some adjustment as it cures. Both types of glue will typically take at least 24 hours to cure. Use painters tape or fishing wire to hold the panels together while the glue cures.

To prevent the side panels from angling inward and preventing the top plate from fitting, place the top plate onto the box while the glue is curing. Make sure that there is no glue touching the top plate or you will have to either break the bond later or remake the side panels.

# Electrical Assembly
## Arcade Button Overview
The arcade buttons consists of eight main parts, the housing, plunger, plate mount, fastener, LED lamp, lamp holder, return spring and limit switch. An layout of the different parts can be found below.

<p align="center">
  <img src="/img/Button_Breakdown.jpg" width="75%">
  <br/>
  Overview of Arcade Button Components
</p>

## Arcade Button Return Spring Removal
If you are using a button configuration where the return spring must be removed, you will need to disassemble the arcade button. To disassemble the button, remove the limit switch and LED lamp from the button. Twist the lamp holder counter-clockwise to unlock and pull to remove. To remove the plunger, squeeze both plunger tabs inward and push the plunger out. Once the plunger is removed, you can replace or remove the return spring.

## Switch & LED Lamp Wiring
Arcade buttons usually ship with a lamp holder, LED fixture and LED. The LED will either be white or the same color as the button cap. Most of the LED fixtures and LEDs that ship with the arcade buttons will have a resistor soldered to the LED in the fixture. This allows the LED to be driven directly off 12V without a resistor. Since we will be driving the LED directly off the output pin of an Arduino, the LED will be dimmer than intended. The LEDs chosen for the guide are a flat topped variety which offers the best illumination pattern within the square button and can be driven directly off the 5V output pin without an external resistor. The side of the lamp which has longer leads or more wire wrapped around the bottom post is the positive side of the LED.

<p align="center">
  <img src="/img/LED_Lamp.jpg" width="75%">
  <br/>
  Assembled LED & Holder (left) & Disassembled (right)
</p>

## Wiring
#### Create Limit Switch & LED Signal Wires
For this section, you will need 14 45cm lengths of wire, 14 spade connectors, a wire cutter, wire stripper, crimping tool and soldering iron.

Using your wire stripper, strip off about 5mm of insulation off both ends of each wire. Once all of the wires are stripped, use your soldering iron and tin both ends of the wire. The ends should be coated in a light application of solder and the individual wire strands should not separate.

Once you've tinned both ends of the wire, use a crimping tool to attach one spade connector to each wire. There should only be one spade connector on each length of wire.

#### Create Ground Wire
For the ground wire, we will create a single daisy chained wire (harness) to connect all of the grounds. This allows us to reduce the number of wires in the box by half.

To reduce the length of excess wire, we will measure the length of wire by measuring the space between the buttons. Unlike the signal wires, two wires will have to be soldered together first before the spade connector can be crimped.

One terminal on both the limit switch and the LED lamp holder will connect to ground. The normally closed (NC) pin and the terminal of the LED lamp holder with less plastic.

Each of the soldered wires will need to be crimped. You should need a total of 14 spade connectors for the ground harness.

## Rotary Encoder Wiring
## Arduino Wiring

# Programming
## Installation
## Downloading the Code
