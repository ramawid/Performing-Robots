# Performing-Robots

## 17 September 2024
Character Description: Detective Hawk likes to pretend he knows what he is doing, clearly being inspired by watching too much Sherlock Holmes. He usually thinks out loud by talking to his sock puppet ‘Mr. Wright’. He finds clues by sheer luck and makes incorrect assumptions all the time even when it's obvious to the audience. When he interviews the suspects, he asks irrelevant questions. He is just lucky that they slip up.

Detective Hawk rocks a trench coat, mustache, and fedora. He also has a sock puppet sidekick on his hand that he talks to.

![detective_hawk](https://github.com/user-attachments/assets/ab8920c7-f0b4-4344-a60e-056e1bbcd83c)

Construction Considerations: The sock puppet on his hand should be able to move to simulate talking. The detective's mouth should also be able to move. I think it would be possible using a motor that moves back and forth for the sock puppet. We are currently unsure about how to make the mouth move for the detective.

### 23 September 2024

Rama and I met up in the IM Lab to work on building the base of our robot. We started first by using a ruler and pencil to find the middle of board. ![IMG_4399](https://github.com/user-attachments/assets/8ec5b4ab-6df1-49ff-89f5-e132e0c16d1b)

Then we installed the metal brackets to the motors by following the examples that the other students made. The wheels were also easy to instal to the motor using nuts and bolts from the lab.
![B5BE15A0-204E-409E-9F8F-BD47DE67FB6D](https://github.com/user-attachments/assets/70db8943-af7e-499c-96f9-4f495d43b24b)

Next we started drilling holes into the wooden board to give space for the nuts and bolts. We found this kind of challenging and ran into some small complications (the drill bit snapped in half), but we were able to successfully get it done.
![IMG_4401](https://github.com/user-attachments/assets/39e64f4c-785c-48ee-a3bf-3d8b4b6236c8)

Lastly, we installed the motors with the wheels onto the wooden board with M4 nuts and bolts.![IMG_4403](https://github.com/user-attachments/assets/f9d5e252-15f3-4112-b50e-fe5b5c665feb)

## October 1 2024
In last Thursday's class, my partner and I focused on refining the wheel setup for our project. Initially, we had two larger wheels attached, and during this session, we worked on adding two smaller wheels. It’s crucial to maintain a bit of wobble in the board to prevent it from getting stuck during the performance. However, the smaller wheels were too short, so we decided to cut small wooden spacers to fit between the wheels and the board, raising the wheels to the right height.[

![Workshop Scene](https://github.com/ramawid/Performing-Robots/blob/c12ca7215de2147678c8d2976de3ab1deb2c4c76/IMG_1971.jpg)

Unfortunately, we miscalculated the length of the wooden spacers, and the board ended up sitting evenly on all four wheels, which eliminated the necessary wobble. To fix this, we removed one of the wheels and replaced the wooden spacer with a smaller piece, creating the imbalance we need.

![Workshop Scene 2](https://github.com/ramawid/Performing-Robots/blob/c12ca7215de2147678c8d2976de3ab1deb2c4c76/IMG_1972.jpg)

Throughout the process, we used screws to attach everything securely, making pilot and through holes where needed. Looking ahead, our plan for the next class is to add the wires and start the soldering process.

## October 3 2024
Questions : How do we define a human? Is it a soul? A body? Can it be recreated? What is the one essential differernce between a human and a robot? Why can a robot never become a human? Is it due to the lack of soul?

## October 24 2024

 Hat Movement:
The detective’s hat is designed to move up and down using a small servo motor. This feature triggers when the robot says certain phrases, adding an animated effect that brings the character to life.

 Eyeball Animation:
The detective’s eyes, equipped with Neopixel LEDs, not only move around but also look down at the puppet when it speaks. This gives the impression of real interaction between the detective and its puppet companion.

 LED Eye Emotions: 
The LEDs in the detective’s eyes change colors to express different emotions. For example, the eyes might glow red when the detective is serious or blue when in deep thought, providing an additional layer of emotional depth.

 Puppet Jaw Movement: 
A motor in the puppet’s jaw opens and closes its mouth, synchronized with its speech, as if it’s genuinely engaging in conversation with the detective.

![IMG_3399](https://github.com/user-attachments/assets/a6b42a00-b827-4451-9a23-b817c3b2f074)
![IMG_3398](https://github.com/user-attachments/assets/9823448a-0926-441e-a2c7-900c1d5cd3dd)


## October 29 2024

Today, we focused on completing the framework of the robot, assembling all the key components to support the sock puppet arm. Next, we attempted to design a mechanism for moving the jaw to simulate speech using a servo motor. However, we encountered a problem—the servo motor we attached to the wooden pieces with hot glue turned out to be faulty. Our next step will be to carefully remove the hot glue and replace it with a functional motor.

![IMG_3398](https://github.com/ramawid/Performing-Robots/blob/dbb0c351a0aeee96c6fcf14583423fe4a1022113/WhatsApp%20Image%202024-11-19%20at%2001.27.35.jpeg)

## October 31 2024

Today, we discovered that the sock puppet's jaw didn't open as wide as we intended. To address this, we began prototyping with cardboard to determine the adjusted length needed for the jaw mechanism and experimented with different angles. Our professor suggested using aluminum to improve durability, which we plan to explore further. Additionally, my partner noticed that part of our Arduino shield had melted and spent time repairing it.

## November 5 2024

Today, we finalized our puppet by fabricating the pieces out of aluminum. The first piece rotates with the servo motor, the second serves as a bridge between the top and bottom wooden pieces. We also attached the arm to the skeleton and programmed its movements. It was fascinating to see how simple code adjustments, such as changing speed or repetitions, could completely transform the puppet's behavior and the way we perceive it.

![IMG_3398](https://github.com/ramawid/Performing-Robots/blob/dbb0c351a0aeee96c6fcf14583423fe4a1022113/WhatsApp%20Image%202024-11-19%20at%2001.28.02.jpeg)

## November 7 2024

Today, we began prototyping the moving stomach element. We’re still figuring out how to configure the servo to push the panel up and down while ensuring it remains stable enough to support the pillow. After exploring several materials, we’ve decided to stick with aluminum, as we did for the puppet mechanism, due to its durability and reliability.

## November 12 2024

Today, we completed the prototype for the stomach movement mechanism and obtained the correct measurements. We also started cutting the aluminum and applied the two nuts trick that our professor taught us to ensure smooth rotations between the joints. When we tried adding the panel, we realized there wasn’t enough reinforcement, so we may need to rethink the positioning of the pillow.

![IMG_3398](https://github.com/ramawid/Performing-Robots/blob/dbb0c351a0aeee96c6fcf14583423fe4a1022113/WhatsApp%20Image%202024-11-19%20at%2001.28.35.jpeg)

## November 14 2024

Today, we readjusted our previous work by moving the servo to the side inside, as our professor suggested for better stability. We also upgraded to a larger servo motor since the smaller one was too weak. After attaching all the pieces together, we’re now planning how to secure everything to the skeleton to ensure stability during the next class.

<img src="https://github.com/ramawid/Performing-Robots/blob/dbb0c351a0aeee96c6fcf14583423fe4a1022113/WhatsApp%20Image%202024-11-19%20at%2001.29.16.jpeg" width="480" height="274" />

<img src="https://github.com/ramawid/Performing-Robots/blob/d1a21b646e358abc553b58785d164f4ec34a91fd/WhatsApp%20Image%202024-11-18%20at%2014.28.11.jpeg" width="480" height="274" />

## November 19 2024
Good news! Hind was able to finish the stomach of our detective. I think we spent alot of time on all these complex mechanisms when we could've simplified it and saved lots of time. Initially we had three joints trying to push the pillow up and down. Now we have a wood panel attached to the servo inside the pillow mimicking and up and down movement of a stomach when laughing. I also started prototyping the eyes. My goal is to have two stryofoam eyeballs that move left and right while also keeping the mechanism fairly simple because that's what's been working best recently.

## November 21 2024
Eyeballs are done!

<img src="https://media.giphy.com/media/7JpxzxNRTytGuXqbr4/giphy.gif" width="480" height="274" />

I made this setup using a single servo motor to move two styrofoam eyeballs in sync. The eyeballs are attached to wooden sticks, connected by an acrylic rod that’s hooked up to the servo. When the servo moves, it tilts the rod, making the eyes shift side to side. It’s a simple and fun design, perfect for interactive projects or just messing around with animatronics!



