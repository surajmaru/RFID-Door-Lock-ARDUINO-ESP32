🔒 DIY RFID Door Lock with Arduino

Hey there! 👋
This is a simple project I made — a door lock system controlled by a 775 DC motor. The motor moves a locking and unlocking mechanism built with a nut and bolt, and everything is powered and controlled with some common parts.

⚙️ What I Used

Arduino Uno (or any compatible board)

RFID RC522 reader + tag

L298N motor driver

775 DC motor (for locking/unlocking)

12V power supply

Buck converter (or just a 5V power supply for the Arduino)

🔑 How It Works

Power up the circuit with 12V.

Scan the RFID tag on the reader.

If the tag is authorized, the Arduino drives the motor via the L298N to unlock the door.

After a short delay, it locks back automatically.

📝 Code

The code is already included in this repo. Just upload it to your Arduino, connect the components as shown in the wiring, and you’re good to go.

🎥 Demo

I’ve uploaded a video of it working on my YouTube channel — feel free to check it out! 🙂

video link:- https://youtu.be/faMSqsNvVmI?si=7vEHjDrN1rKO-4Bw
