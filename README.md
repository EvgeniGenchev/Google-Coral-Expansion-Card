# Introduction
The moment I saw the Framework laptop and the expansion card system I knew I have to make something. First I was thinking of making a raspberry pico card, ethernet, LTE or magnet charger, but since all of them were being done by the amazing community and I thought I could not provide anything to the table. 

However, while I was training an ML model on my laptop I was frustrated by how slow it was going. (I have HP Folio 9480m) A friend of mine saw me having a bad time and gave me a Google Coral USB Accelerator which sped up the training process substantially.  After some time I went online to buy one for myself and saw on the website that the Accelerator Module was being sold. 

# Accelerator Module
![image](https://user-images.githubusercontent.com/59848681/168494446-546b87c5-c234-4efc-9edc-0491e97c7c51.png)




The module is a 120-pin LGA chip which scared me at first. 120 small lanes and all the supporting components can't fit into an expansion card, can they? It turns out this chip has 104 pins that are either 3.3V or GND. From the other 16 pins, you can run the module using only 7 pins. So yeah... it's not only doable but with the example schematics provided by Coral and Framework, it is 15 min work. 

# The PCB
I present you the Framework Coral Accelerator Card:


The board is using USB2.0 since it is the easiest to make into a functioning circuit but it has PCIe and USB3.0 possibilities but for that: 
![image](https://user-images.githubusercontent.com/59848681/168494455-5cc0afd3-b682-448e-b470-4b01ccfd2c06.png)

I will contact sales but I do not think they will answer.

# Limitations
- The Chip Shortage == No modules available
- Applied Computer Science Degree == I have basic circuit design skills

NOTE: I do not have a Framework **YET** , but that will not let me being broke student from adding to this amazing product.
 
