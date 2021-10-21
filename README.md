# PCB track measurement test for perchloride corrosion

I was doing some projects and I needed them to be very small, and for this every millimeter would be able to save, so I decided to look for something on our beloved internet regarding the minimum width of the trails and between the trails that could be worked with relative safety to Corrosion of artisan PCBs with thermoreference method by photographic paper and corrosion by Iron Perchloride, but I didn't find much, let alone with images for my own evaluation, so I decided to do tests myself to take as a parameter for my projects.

I decided to use the Software [KiCad](https://www.kicad.org) to make the PCB project with some parameter items, reaching the result presented in the image below.

![PCB-NEW](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/PCBNew.png)

To make sure there were not too many imperfections on the Plate, I used a steel sponge to sand the surface, then cleaned with toilet paper and isopropyl alcohol.

![PCB-CUT](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/pcb-cut.jpeg)
![PCB-CUT](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/pcb-cut-2.jpeg)

I cut the 130g photo paper with the 1/1 aspect ratio printing done by laser printer, then I hot ironed the paper with the copper side PCB and the printed side together for about 5 minutes with a lot of pressure.

![PHOTOGRAPHIC-PAPER](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/CUT-PHOTOGRAPHIC-PAPER.jpeg)
![THERMAL-TRANSFER](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/THERMAL-TRANSFER-FINISHED.jpeg)

After successful Thermotransfer and high quality, we can start corrosion in iron perchloride. I particularly use my homemade plastic "Ultrasonic Cube", with a mixture of 250gr of perchloride to 500ml of cold water.

![PERCHLORIDE-CORROSION](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/gif.gif)

After 10 minutes of corrosion we have this result, now we can wash and remove the heat transfer paint layer with a steel sponge.
![FINISHED-PERCHLORIDE-CORROSION](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/FINISHED-PERCHLORIDE-CORROSION.jpeg)
![FINISHED-PERCHLORIDE-CORROSION](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/FINISHED-PERCHLORIDE-CORROSION-2.jpeg)
![FINISHED-PERCHLORIDE-CORROSION](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/FINISHED-PERCHLORIDE-CORROSION-3.jpeg)

We have the Result.
we can see that even with the method used we achieved a satisfactory result on tracks up to 0.25 mm, but it would be too risky to use an entire project with this width, as we can see that even at 0.5 mm the track had small flaws, so we can consider feasible to work with 0.75 mm for reasons of guaranteeing functional and relatively thin tracks. in relation to the width between the tracks we got an excellent result in 0.25 mm, but for guarantee reasons I will adopt 0.5 mm as standard.

![results](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/FINISHED-PERCHLORIDE-CORROSION-4.jpeg)
![results](https://github.com/silvajhb/PCBtrackcorrosion/blob/master/HARDWARE/DOCUMENTS/IMAGES/FINISHED-PERCHLORIDE-CORROSION-5.jpeg)

And here I end my analysis on the subject, it is worth mentioning that I will adopt 0.75mm for tracks and 0.5 for spacing, but if necessary I can reduce it to 0.5 and 0.25 respectively, at least using the PCB manufacturing method described above, I know that using phototransfer I can achieve better results, but that's for another time.
