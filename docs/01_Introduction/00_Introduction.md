# UDOO X86 II
**UDOO X86 II** is the New PC: the most powerful maker board ever and an Arduino&trade; Leonardo-compatible platform, all embedded on the same board.

On UDOO X86 you can run all the software available for the PC world, from gaming to video streaming, from graphical editors to professional development platforms, plus all the software for the Arduino&trade; Leonardo world, including all the sketches, libraries and the official Arduino&trade; Leonardo IDE.

UDOO X86 embeds two processors:
* a Quad Core 64-bit new-generation x86 [**Braswell**](https://ark.intel.com/compare/91831,91830) 14nm processors, designed for the PC domain (The N-Series Intel® Pentium® / Celeron® and x5-Series Atom family of System-on-Chips (SoCs) formerly coded as Braswell is a series of Quad Core SoCs with 64-bit instruction set and very low TDP.)
* the [**Microchip ATmega32U4**](https://www.microchip.com/wwwproducts/en/ATmega32u4) 8-bit AVR microcontroller, the same of *Arduino&reg; Leonardo*.

While the X86 Braswell processor can run all the Windows, Linux, Android X86 64bit Distros you want to use as desktop PC, the ATmega32U4 allows easy access to a Arduino&trade; Leonardo environment.

Download the [**User Manual**](http://download.udoo.org/files/UDOO_X86/Doc/UDOO_X86II_MANUAL_Rel.2.0.pdf) to have more complete explanation of the UDOO X86 hardware.  

Visit the [**Get Started X86**](https://www.udoo.org/get-started-x86/) section of the UDOO website to find video tutorials of how to start use the UDOO X86 board.

<p style="background-color: rgba(255, 170, 50, 0.3);padding: 20px;border-left: 5px solid orange; border-radius: 4px; color:rgb(45, 45, 45);">
This is the documentation for the second revision of the UDOO X86 - <b>UDOO X86 II</b> - board with Arduino Leonardo-compatible microcontroller (ATmega32U4).<br>
If you have the first UDOO X86 revision in your hands, please consult the <a href="https://www.udoo.org/docs-x86"><b>UDOO X86 doc at this page</b></a>. Check how to <a href="../Hardware_Reference/Recognize_the_UDOO_X86_revision.html"><b>recognize the UDOO X86 revision</b></a>.  
</p>

<p style="background-color: rgba(255, 170, 50, 0.3);padding: 20px;border-left: 5px solid orange; border-radius: 4px; color:rgb(45, 45, 45);">
If you have any <b>trouble</b> uploading the <b>Arduino sketch</b> running Linux, check the <i>Linux Known issue - Sketch upload</i> section in the <a href="../Arduino_Leonardo-compatible(ATmega32U4)/Getting_Started_with_Arduino_Leonardo.html"><b>Getting Started with Arduino Leonardo</b></a> page.
</p>

<hr/>

<span class="label label-warning">Heads up!</span> In order to prevent damages to your board, remember to:

* Never provide more than 5V in input to the GPIOs of the Arduino Leonardo-compatible(Atmel&reg; ATmega32U4), and never provide more than 1.8V in input to the GPIOs of the Braswell processor.
* Never keep the board in touch with metal objects or surfaces while it is powered up
* Power the board with a stabilized power supply (DC-jack with a standard 5.5mm/2.1mm barrel jack, internal positive, Voltage 12V ± 5%, at least 3A).
* Do not use a *NON*-standard USB 3.0 peripheral. If you use a non-standard USB 3.0 peripheral with an external power plug, this could send back the power source to the UDOO X86 board with the risk of damage.


## Lineup
UDOO X86 retail line up consists of [two models](!Hardware_Reference/Board_versions).

<img src="../img/x86_lineup.png" alt="UDOO versions" class="img-responsive" >


## Technical specifications

<img src="../img/x86ii_ultra_top_rotate.png" alt="UDOO Boards" class="img-responsive pull-right" height="441px" width="350px"  style="margin-bottom:20px; margin-left:30px;">

* Processor:
  * CPU Intel&reg; Pentium N3710 up to 2.56 Ghz (ULTRA version)
  * CPU Intel&reg; Celeron N3160 up to 2.24 Ghz (ADVANCED PLUS)
* GPU:
  * Intel&reg; HD Graphics 405 up to 700 MHz 16 execution units (ULTRA version)
  * Intel&reg; HD Graphics 400 up to 640 MHz 12 execution units (ADVANCED PLUS)
* RAM:
  * 8 GB DDR3L Dual Channel (ULTRA version)
  * 4 GB DDR3L Dual Channel (ADVANCED PLUS)
* Microchip ATmega32U4 8-bit AVR RISC-based microcontroller.
* Video interfaces:
  * 1x HDMI 1.4 (CEC)
  * 2x Mini DisplayPort ++ (mDP++)
* Storage:
  * 32GB eMMC soldered on-board (Advanced Plus and Ultra only)
  * 1x M.2 Key B 2260 slot for SATA SSD modules** / PCIe (2x) modules
  * 1x SATA III 6Gb/s connector
  * 1x MicroSD slot
* Networking:
  * 1x Gigabit Ethernet LAN interface
  * 1x M.2 Key E slot for optional Wireless(WiFi+BT) Module
* Audio interfaces:
  * HD Audio Codec ALC283CG
  * Microphone + Headphone Combo Connector (TRRS)
  * Pre-amplified stereo speaker output
  * S/PDIF output*
* 3x USB 3.0 type-A sockets
* 2x HSUART ports*
* 2x I2C interface*
* 1x SDIO interface*
* 1x LPC interface*
* 12V (± 5%) DC Power Jack (standard 5.5mm/2.1mm barrel jack: internal positive), at least 3A.
* RTC Battery Connector + RTC Coin Battery
* Bi-color Power Status LED
* 1x Sensor Snap-In I2C connector (UDOO Bricks)
* Arduino&trade; Leonardo-Compatible through the standard Arduino&trade; Pins layout and compatible with Arduino&trade; shields.

&#42;Available on Pin Header
&#42;&#42;Not compatible with NVMe modules

Visit the [official accessories](!Hardware_&_Accessories/Official_Accessories) sections.

## Community
* Official web site [www.udoo.org](https://www.udoo.org)
* Official forum [www.udoo.org/forum](https://www.udoo.org/forum/index.php)

### Forums
The official UDOO forums can be found at [www.udoo.org/forum](https://www.udoo.org/forum)

The forum search facility has been tweaked to allow more general searching.
**Please** do a search before making a post as the issue may already have been raised and answered.

### IRC channel
There is an (unofficial) UDOO discussion channel on IRC. Using the IRC client of your choice, use server information: `irc.freenode.net`. Room name is `#udoo`.


### Social networks
 * [Facebook fan page](http://www.facebook.com/udooboard)
 * [Twitter](http://twitter.com/UDOO_Board)
 * [Google+](https://plus.google.com/u/0/110742692974455430878/posts)
 * [YouTube](http://www.youtube.com/channel/UCXv5UyGn5jArK8xOAmuSeHg)


<!-- Google Code -->
<script type="text/javascript">
var google_conversion_id = 983836026;
var google_custom_params = window.google_tag_params;
var google_remarketing_only = true;
</script>
</noscript>
