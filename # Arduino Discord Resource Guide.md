# Arduino Discord Resource Guide

## 1. Arduino and Electronics Basics
- Resources, tutorials, and wikis for Arduino           // TODO : Add links

- Pseudocode examples                                   // TODO make video exampleand link it here
- Soldering example                                     // TODO make video exampleand link it here
- Reading compiler error messages                       // TODO remove possable
- Power ratings for LEDs                                // TODO Gather images of led's
- Basic electronics tutorials                           // TODO remove maybe

## 2. Troubleshooting and Best Practices
- How to ask questions effectively                      // TODO mae an example of how to ask a question
- Tips for getting help quickly                         // TODO same as above.
- Common Arduino clone issues                           // TODO Link to this info.
- Guidelines for using simulators                       // TODO Review
- Bootloader information and risks                      // TODO Review

## 3. Community Guidelines and Etiquette
- Helping channels guide                                // TODO show how to use help channels
- Academic integrity policy                             // TODO Why we do not help with graded work.
- Code formatting in Discord

## 4. Tools and Resources
- Arduino simulators (Wokwi, Tinkercad, etc.)           // TODO links added
- Free lesson books for Arduino Mega and Uno boards     // TODO links added
- Serial terminal alternatives for Chromebooks          // TODO add links

## 5. Advanced Topics
- Multitasking in Arduino                               // TODO Video on how to use millis
- Flowchart basics                                      // TODO make video on how to use flowcharts

## 6. Safety and Cautions
- Warnings about nine-volt batteries                    // TODO Link video
- Cautions about using ChatGPT for Arduino projects     // TODO post cautions

## 7. Product Information
- Comparisons between Arduino clones and originals      // TODO how to identify an arduino
- Official Arduino store information                    // TODO add links to arduino resorces.




Resources, tutorials, and more for this server. 

 
Maderdash
We can't paste this image from the Clipboard, but you can save it to your computer and insert it from there.
OP — 02/01/2024 8:16 AM 

Topics: 

Why nine-volt batteries should not be used? Nine Volt Battery's 

A wiki made by discord helpers, full of useful tutorials. Wiki For Arduino server 

How to organize your instructions to start coding? Pseudocode example 

Example of proper soldering for through hole components. Soldering example 

Some quick tips how to read a compiler error message: 

blue: file paths of files that the compiler thinks are involved in the error. Note that there are multiple files, but the actual mistake might be only in one. If you're a beginner, it's most likely that the mistake is in the .ino file that you're writing. 

green: line number and character in the number where the compiler noticed the error. 

purple: snipped off code where the compiler noticed the error. 

Note: 

The actual mistake can often be in the line above where the compiler noticed it. 

Yellow: Error message of the compiler. Note that the message can sometimes be very cryptic or even a bit misleading. If you don't understand the message, then look in the few lines above the error for missing (){};  

Pro Tips: 

Look for missing (or too many) (){};, 

Use the auto formatting feature of the Arduino IDE. (CTRL+T). If the indentation looks weird, then there probably is something weird/wrong.  
 

Are Arduino clones as good as the original ones? 

Many cheap Arduino clones use a different microcontroller than the original, which can cause compatibility and driver issues. https://www.youtube.com/watch?v=eeQJDV\_e1Vg 

Common Arduino clone issues are:: 

Poor or cheaper Build quality :This means that the clone board may start falling apart or get bricked randomly after few months of use, while in the other hand Arduino official products are built to last and have numerous protection against static shocks etc… 

Wrong Microcontrollers : 

You have to install the correct drivers, prepare yourself for some failing codes even tho they are correct, over current and over voltage thresholds aren't the same as the official products.  

Not beginner-friendly : 

Poor quality boards can be especially problematic for those just starting out with Arduino and programming. Inexperienced programmers, would assume that any issues are due to their own mistakes, rather than an issue that's inherent to the board itself. Such failure could even short-circuit one's pursuit of electronics before it even gets charged up (pardon the puns).  

How to NOT have these issues? 

Make sure you buy Arduino's from :  

Official Europe Africa, America, Asia, Oceania Official Arduino Store 

Arduino Pro : 

If you experience any problem with the Pro Category Arduino's please contact Arduino Pro. 

(One exception is Ruggeduino made by company Rugged Circuits, technically it is Arduino clone, but uses proper microcontroller and has a lot of protection features that not even original Arduino boards have) 

 
 
Maderdash
We can't paste this image from the Clipboard, but you can save it to your computer and insert it from there.
OP — 02/01/2024 8:16 AM 

How to get your question answered quickly? 

Help me, my robot does not work. << This is a POOR question. 

 

What robot? 

What is not working? 

What board are you using? 

Was the bot ever working? 

What have you tried? 

What knowledge do you have? 

What would it look like if it "Worked"? 

VS  

I need help, I have this robot kit (link here), and it has never worked. I have gotten to upload code to the Arduino UNO rev3, as I made the blink sketch work. Furthermore, I think the code is not the issue, as it seems to be getting the signals from the remote (Link to the product). Here is a list of all of my parts (link link link) and this is not my first project, but it is the first time I have used servos/motors, so I may have something incorrect there. Also, here is my current wiring diagram (IMG/link). If anyone can assist me, I am going to have lunch and I will be back in 30 minutes or so, I have allotted 4 hours tonight to spend on debugging this. Thank you in advance. 

Can you see the difference in asking a question? 

 

 

PenPengu 🌺🌈
We can't paste this image from the Clipboard, but you can save it to your computer and insert it from there.
 — 02/02/2024 4:28 PM 

Please use the code formatting feature of discord to make your code, compiler error messages, etc way easier to read! ```ino yourCodeHere(); ``` turns into  

yourCodeHere(); 

(edited) 

February 3, 2024 

 

 

FlattestDisc108 | MBWN — 02/06/2024 3:44 PM 

[Helping Channels Guide] 

In any helping channel, people here are ready to share their expertise to make your projects right and running. Please be respecful to others and show common sense. And please do not cross-post as this breaks ⁠code-of-conduct. Mods don't take rule breaking lightly.  

⁠general-help  

is a channel dedicated to general purpose help, like quick questions, error discussion etc... 

⁠official-product-help/⁠official-product-help  

are channels dedicated to serious Arduino Inquiry, these channel often has Arduino Official Support Team responding to you. 

⁠hardware-help/⁠hardware-help  

are channels dedicated to hardwares and hardware only, like sensor recommendation, or is the soldering right and so on. 

⁠coding-help/⁠coding-help  

are channels dedicated to coding and coding only, like code checks, coding help as the channel name implies and so on. 

⁠esp-help  

is a channel dedicated to esp and esp only, esp discussion, wifi etc there. 

⁠pcb-help  

is a channel dedicated to pcb (printed circuit board) and pcb only, that channel has multiple people sharing their expertise to help you make your pcb right. 

⁠sensors-help  

is a channel dedicated to sensors and sensors only, this implies that any sensor related issue must go there (not code related). 

⁠robotics-help  

is a channel dedicated to full project helping, your project has a problem that has a bunch of components ? ask there for someone to help you. 

⁠i2c-serial-help  

is a channel dedicated to I²C related issues, I²C interface issues and so on. 

⁠adafruit-help  

is a channel dedicated to adafruit issues only, like having a problem with your pi pico and so on. 

Thank you for taking your time reading this. Have a good day. (edited) 

 

 

A friendly reminder about our community guidelines regarding schoolwork: 

We do not offer direct assistance with homework, graded work, or any academic projects directly related to tests or coursework.  

Here's why: 

Academic Integrity: We prioritize a responsible learning environment. Direct answers could compromise your understanding and violate academic integrity policies. 

Skill Development: Struggling is part of the learning process! Working through challenges independently builds critical thinking, problem-solving, and research skills for the long run. 

Community Focus: Our server thrives on collaboration and support for active user projects. Think passion projects, personal creations, where you genuinely seek feedback and ideas. This fosters a more engaging and meaningful experience for everyone. 

Remember, we're always happy to help with: 

Personal projects: Bring on the passion! We love to see your creative endeavors and offer feedback or resources. 

General questions: Ask away! We're here to help where we can. 

Guidance & resources: We can point you in the right direction to enhance your learning. 

Just keep in mind the spirit of our community: learning, growing, and supporting each other's creative journeys.  

P.S. Unsure if your project aligns with these guidelines? Open a modmail, and we'll be happy to answer if it is, or not.! 

 

 

PenPengu 🌺🌈
 — 02/07/2024 10:51 AM 

Simulators 

Simulators are great because you can quickly try out things without having hardware. And if you have an issue, just share the link on this server and people can easily help you with code and wiring. Because you could use literally hundreds of thousands of parts with Arduino, don't expect any simulator to have a complete parts library. They all only have a few parts that are very popular with typical Arduino beginner projects.  

https://wokwi.com/ Great for code. Included debugger. But no analog simulation. Buttons, LEDs, potentiometers all work as expected. But even something simple like a voltage divider with 2 resistors doesn't work. Also, Wokwi allows you to do things that would cause damage in real life like using LEDs without resistor or powering 100 stepper motors from USB. 

https://www.tinkercad.com/ Actually simulates analog. (or somewhat? I'm not sure.) 

https://www.circuito.io/ haven't tested it. Looks like it's got a lot of components 

https://www.falstad.com/circuit/circuitjs.html Nothing Arduino. But way more advanced simulation for electronic circuits 

(I'm sure someone else can write this list better. Feel free to add suggestions) (edited) 

 

1 

February 10, 2024 

 

 

 

FlattestDisc108 | MBWN — 02/10/2024 5:15 AM 

Power Ratings For most LEDs, please note that tolerance and anything extra is not detailed here, this image is just a reference for you to know their power ratings. (edited) 

 

 

1 

February 13, 2024 

 

 

PenPengu 🌺🌈 — 02/13/2024 7:50 AM 

https://support.arduino.cc/hc/en-us/articles/4402764401554-If-your-sketch-doesn-t-compile 

 

 

FlattestDisc108 | MBWN — 02/13/2024 3:03 PM 

[Burning a bootloader ?] 

What's a bootloader ? What is burning a bootloader ? and what are the risks ? In this quick guide, i'll explain Everything.  

What is a bootloader ? 

A bootloader is a piece of software that comes included in any MCU. 

It ensure or guarantees the good functioning of a board. 

And also is the software that allows you to upload any arduino code safely with no problem. 

What is burning a bootloader ? 

Burning a bootloader is a process which consists of erasing a bootloader from an MCU or anything like that and re-installing it. 

You have to do certain steps in order to proceed into burning one. Check this page to know more 

What are the risks of it ? 

Burning a bootloader should not be taken as a joke or lightly, it's a very serious case. 

Burning a bootloader comes with a lot of risks : 1. Doing any errors in the wiring will brick the boards. 2. Do not copy codes from others to burn bootloaders, only use the recommended one by arduino. 

Burning a bootloader should be and always be the last resort to a software issue in the arduino boards. 

 

 

Maderdash
We can't paste this image from the Clipboard, but you can save it to your computer and insert it from there.
OP — 02/17/2024 12:41 AM 

Here are free lesion books by elgoo for the Mega board and the Uno board. uno board mega board If you want to learn, then work you way thought the lesions in the books and every 9-10 lesion, go and redo every lesion at the same time [example lessons 1-9 all working and coded together at the same tim] This will teach you how to hand code, and how to incorporate multiple working sketches together at the same time. Be sure to understan you NEED TO HAND code all of this. Do NOT COPPY PAST wen your merging all of the codes together at the same time. after yo have this done then move on to the next 9-10 lesion, then repeat over again. 

 

 

PenPengu 🌺🌈
 — 03/02/2024 5:35 AM 

 

[5:35 AM] 

 

 

5 

 

1 

 

1 

 

1 

March 9, 2024 

 

Maderdash
OP — 03/09/2024 12:11 AM 

 

 

2 

 

3 

April 2, 2024 

 

PenPengu 🌺🌈
 — 04/02/2024 7:26 AM 

 

 

7 

May 3, 2024 

 

FlattestDisc108 | MBWN — 05/03/2024 6:18 AM 

Please, don't use chat-gpt, it's bad to the point where even rules say don't use it... 

 

5 

May 15, 2024 

 

PenPengu 🌺🌈
 — 05/15/2024 8:44 AM 

https://learn.adafruit.com/multi-tasking-the-arduino-part-1?view=all#overview 

Adafruit Learning System 

Multi-tasking the Arduino - Part 1 

Make your Arduino walk and chew gum at the same time. 

 

 

1 

May 27, 2024 

 

PenPengu 🌺🌈
 — 05/27/2024 7:18 AM 

https://serialterminal.com/ for chromebookers (similar role to the Serial Monitor in the Arduino IDE) https://duino.app/#/ (edited) 

June 7, 2024 

 

Maderdash
OP — 06/07/2024 6:06 PM 

flow chart basics. and a challange. https://www.youtube.com/watch?v=SWRDqTx8d4k 

YouTube 

Robot Riedinger 

Introduction to Creating Flowcharts 

 

June 15, 2024 

 

PenPengu 🌺🌈
 — 06/15/2024 7:44 AM 

@Limba  

If someone has asked old style tutorials of basic electronics I have usually given this site https://www.electronics-tutorials.ws/ 

 