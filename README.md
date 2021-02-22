# BETA!! Big Wheel Matthew's Edition (Not Finished Yet)
 3D-printed video control surface, and all credits go to Zack for inspiration and source files

Slapped together in a weekend by Zack Freedman of Voidstar Lab for [a YouTube video! Check it out!](https://www.youtube.com/watch?v=72a85tWOJVY)

Materials:
- 1x each of:
    - Big Ass-Wheel.stl
    - Main Frame.stl
	- Top Frame.stl
	- Bottom Plate.stl
    - Wheel Insert.stl
- Bunch of theese:
	- 3x Encoder Knob.stl (if you want to use mine ones)
	- 4x Encoder Nut.stl (if your encider module doesn't have one)
	
- 12x 8mm M3 screws
- 1x M3 nut
- 14x Cherry MX-compatible keyswitches
- 14x keycaps for keyswitches
- 14x rectifier diodes, such as the 1N4004
- 4x encoder modules
- 4-6x rubber/felt feet
- 1x Arduino Pro Micro clone like [this one](https://aliexpress.ru/item/1005001543169595.html?aff_fsk=_d6jWDbY&aff_platform=link-c-tool&sk=_d6jWDbY&aff_trace_key=b2942241c57e4d388145fced90f38cdd-1613820055888-02820-_d6jWDbY&dp=5f953218c74146cb8d9bcf39&terminal_id=1e685d41c3784538965a17753d13913d)
- Lots of wire and heatshrink (as usual)

Instructions:
1. [Watch video](https://www.youtube.com/watch?v=72a85tWOJVY) to see construction overview
2. Fabricate 3D-printed parts
3. Screw Top Frame to Main Frame using 6x 8mm M3 screws
4. Snap keyswitches and encoders into your whole frame: keys snap in from top and good to go, encoder modules go from bottom and need to be secured with a nut from top (make sure that encoder pin got in its place).
5. Using wiring diagram, build switch matrix. Take care to route wires away from surface that contacts Support Waffle.
6. Connect switch matrix and encoders to Teensy. Take care to leave extra wire!
7. Slide Teensy into its rails. It should fit snugly - if it's loose, add a bit of electrical tape to tighten things up.
8. Connect to computer, load firmware, and test
9. Using a soldering iron, apply heat-set inserts to the bosses on the Body.
10. Mount Waffle and Baseplate combo to the Body using the screws.
11. Apply rubber feet to Baseplate.
12. Slip nut into slot on Big Ass-Wheel and insert screw through side of wheel.
13. Mount Big Ass-Wheel on center encoder and tighten screw. It should turn smoothly but not wobble.
14. Glue Wheel Insert onto Big Ass-Wheel.
15. Mount remaining encoder knobs and keycaps.
16. If desired, modify firmware to bind your preferred commands to the controls.
17. Let Zack know you built the project!