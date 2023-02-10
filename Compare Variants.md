# Compare between two protein structure
## Set up
#### First, click on open to get the pdb files on your computer
![Screenshot 2023-02-10 at 11 28 29](https://user-images.githubusercontent.com/112228504/218186012-aedbc34e-1b5f-4a10-9948-dc6489d8e709.png)

#### Then you will get a protein structure like this (the example structure is the orginial COVID-19 protein structure)
![Screenshot 2023-02-10 at 11 29 01](https://user-images.githubusercontent.com/112228504/218186685-2dbde655-ff00-4024-8fc1-96e60df15661.png)

#### Follow the same step, you can open another pdb file to compare. <br>
#### Remember! sometimes the protein structure may appear not in the same place, you need to zoom out to find the structure. <br>
*Quick Note: For Mac user, press option to drag the whole picture to move in 2D space. Just moving the mouse can only move the structure in 3D space* 
![Screenshot 2023-02-10 at 12 03 19](https://user-images.githubusercontent.com/112228504/218187629-6469db8c-2234-485f-a436-d1db5ecda1c4.png)

#### Now, the two strucutres are far apart from each other, how can we compare them?
#### We just go to Tools -> Structure Comparision -> MatchMaker, then we choose the reference structure and the structure we want to match, click apply.
![Screenshot 2023-02-10 at 12 15 33](https://user-images.githubusercontent.com/112228504/218189127-d0eacc52-74e6-4c50-ac77-82f158ce5ee6.png)

#### We have this matched structure to compare.
![Screenshot 2023-02-10 at 12 22 35](https://user-images.githubusercontent.com/112228504/218190410-8e0dffb1-2039-42ef-bbf0-c3b4b1687d27.png)

#### For your conveinence, it's optional for you to hide some proteins you don't need. Select the chain, then Actions -> Ribbon -> Hide, to get the proteins back, you go to select the chain you want. then Actions -> Ribbon -> Hide.
![Screenshot 2023-02-10 at 12 48 48](https://user-images.githubusercontent.com/112228504/218194940-eb40d897-b14b-4fc7-8d12-3fb6553e8f3b.png)
![Screenshot 2023-02-10 at 12 48 57](https://user-images.githubusercontent.com/112228504/218195041-b36f6ad7-bdee-447e-af27-c37bf8aa80fd.png)
![Screenshot 2023-02-10 at 12 53 56](https://user-images.githubusercontent.com/112228504/218195462-4168d16c-40c0-497a-94f0-5f68286ff95a.png)

## Sequence
#### To show the sequence of these proteins we want, we go to Tools -> Sequence -> Sequence, it will show you all the chains of sequence we have. Now, it's time for you to make the choice of which sequence you want. 
![Screenshot 2023-02-10 at 12 57 40](https://user-images.githubusercontent.com/112228504/218197916-f0f8aa69-91e4-41df-84bf-5b1787f1df70.png)
#### For example, we need to compare COVID-19 orginal and the Alpha variant in this case. After, we hid the ACE2 in the protein structure, we can move the mouse on one of the chain, it will show you the existed chains on Chimera and you can open the sequence of these chains.
![Screenshot 2023-02-10 at 13 11 54](https://user-images.githubusercontent.com/112228504/218198548-eb2615a2-770b-4d1e-8665-313647f64726.png)
![Screenshot 2023-02-10 at 13 12 05](https://user-images.githubusercontent.com/112228504/218198563-95b6d9ea-c1d0-4189-b10f-9e7c8438beb0.png)
#### Now, we can see the Sequence!!!
![Screenshot 2023-02-10 at 13 15 36](https://user-images.githubusercontent.com/112228504/218198879-50d43c1a-d714-4381-98a1-d2e14f036637.png)
#### After the sequence is showed, you can just read the sequence and compare them one by one, if you find some differences between them, select that sequence, go to Actions -> Color (Choose whatever color you want, but since you are comparing, choose some contrasting colors.)
![Screenshot 2023-02-10 at 13 21 58](https://user-images.githubusercontent.com/112228504/218200480-470dc26d-a2a2-4cbf-872e-febe9d92eb52.png)


## Find interface
#### The purpose for finding interface is to let us easily confirm the region we want to compare the variants.
#### Same thing, go to Tools -> Structure Analysis -> Find Clashes/Contacts
![Screenshot 2023-02-10 at 12 29 13](https://user-images.githubusercontent.com/112228504/218191491-ace3fba1-5869-42d7-a236-fa4d9c397fa8.png)

#### Select -> Chain, can help you to designate the first 
