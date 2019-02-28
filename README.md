# DTWSpells-TaliaKrause

#goal
my goal for this was to create two different outputs for different "spells" or hand movements. i wanted two images to be output from the different spells made

#approached problem

for this project you simply need two microbits, one plugged into the computer and one can be wireless plugged into a battery pack or connecting to a longer mini usb corb. this second microbit wil be the one that is actually doing the casting of the spells and the first microbit will be on the receiving end of things.
i simply used the microsoft make code in order for the microbits to be connected to eachother and wekinator to train and for the output simply took the DTW trigger text output from the wekinator examples package and teaching examples.

from there i didnt change much except for when it was outputting the hue color in the primary code i added 3 images in the data folder and made if statements for the different images and set those for each of the inputs. the third is if i were to make another gesture(it goes to voldemort image)

i found that when i was training the model more training examples ended up not doing much for the favor of the outcome, sticking with less than 10 training examples proved to be the best outcome. 

for the actual "spell" motions it became difficult when the spells had the same p=mtions or anywhere similar. i realized position also takes a place in the inputs and when i went behind my head and back that created a distinguished spell and made it easier to to differ between the two spells.
i also found that a bit of a lower threshold was able to detect but not detect to harshly and accept everthing.

i want to be able to produce a sound from the receiving microbit and produce a different noise for each picture(lower sound for dumbledore higher pitch for dobby)



https://youtu.be/hVaUdA6It1w

