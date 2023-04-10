## Beforehand
### Before calculate the protein electrostatic potential, remember to trim your pdb file to a relatively small file to save time.
### After you have your file ready, go to this [website](https://server.poissonboltzmann.org/pdb2pqr).
<img width="1390" alt="Screenshot 2023-04-09 at 17 15 05" src="https://user-images.githubusercontent.com/112228504/230803245-5f35c7c6-f6af-449a-9196-1165482eca6e.png">

### Upload the pdb file and click start job

<img width="1118" alt="Screenshot 2023-04-09 at 17 20 39" src="https://user-images.githubusercontent.com/112228504/230803511-edc3237d-6968-4eb5-aba3-bcb9dc3e9bc7.png">

### Click Next: Use results with APBS
<img width="1200" alt="Screenshot 2023-04-09 at 17 23 24" src="https://user-images.githubusercontent.com/112228504/230803664-275c3957-4e23-40c0-9231-ed799390514c.png">

### Start job
<img width="1147" alt="Screenshot 2023-04-09 at 17 24 32" src="https://user-images.githubusercontent.com/112228504/230803726-6d675374-9228-4089-bef2-4299d7af94df.png">

### After it's finished, look at the APBS output file, then download the suffix of "pot.dx" file, this is the electrostatic potential map we want.
<img width="1149" alt="Screenshot 2023-04-09 at 17 25 33" src="https://user-images.githubusercontent.com/112228504/230803770-b38473de-f5f9-4fa1-aae8-3ffd293b92bd.png">

## Continue on ChimeraX
### Open the pdb file in ChimeraX, then load the electrostatic potential map we just got: 
### Click "Open" in ChimeraX, then select the map
<img width="904" alt="Screenshot 2023-04-09 at 17 32 45" src="https://user-images.githubusercontent.com/112228504/230804140-91302316-829a-4300-9666-9aaa1ab12347.png">

### Then we will have this matched graph, they should be matched together. If not, check the video in the end.
<img width="763" alt="Screenshot 2023-04-09 at 17 35 27" src="https://user-images.githubusercontent.com/112228504/230804266-5c1c1843-9d8c-4339-ad59-4ffd175e29f6.png">

### Go to "Molecule Display", then click "Show" in "Surfaces"
<img width="888" alt="Screenshot 2023-04-09 at 17 37 04" src="https://user-images.githubusercontent.com/112228504/230804348-51449202-fbce-407b-81cc-d41d8abea5a0.png">

### Go to "Tools" -> "Volume Data" -> "Surface Color", then you should be able to see the panel of "Surface Color"
<img width="1483" alt="Screenshot 2023-04-09 at 17 38 20" src="https://user-images.githubusercontent.com/112228504/230804414-149b7e3c-b0fb-4841-b189-c9df66a7d006.png">

### Since we already loaded the electrostatic potential map, we can choose "Color surface" by "electrostatic potential" instead of "radius" in the bottom right corneer
<img width="573" alt="Screenshot 2023-04-09 at 17 40 04" src="https://user-images.githubusercontent.com/112228504/230804510-149c914a-e163-4ba6-9cb9-d3093aa004bc.png">

### Then we can see the loaded map is here, and you can set up the range of your red, white, blue color here in the panel 
<img width="573" alt="Screenshot 2023-04-09 at 17 42 51" src="https://user-images.githubusercontent.com/112228504/230804682-c7c57281-323e-4005-a900-92c27bebcda5.png">

### Remember to use command to color white the chain if its surface color is not originially white
### Now you can adjust the color of your electrostatic potential by adjusting the number of range in Red, White, Blue. Common range(-10, 0, 10), (-10, -3, 5)
### The color range goes opposite, if you input 5 for your blue color, it will be deep blue; if you enter 10, it will be light blue.
<img width="1380" alt="Screenshot 2023-04-09 at 17 49 13" src="https://user-images.githubusercontent.com/112228504/230805071-798e9cf2-2ada-4740-b168-dbdf3752f6e1.png">

### Lastly, don't forget to save your session

<br>

## Appendix
### Userful [video](https://www.youtube.com/watch?v=FEIJ0lmybXo).
