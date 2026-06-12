
# June 11 2026

I made the schematic today. It's inspired by LoneOceans, Steve Ward, and some other circuits. Making circuits like these and not just spamming chips like on a devboard is much much harder because you have to use actual logic.
Instead of just having function blocks and adding some decoupling caps to them, each component has a very specific purpose. Like the two clamping diodes on the antenna so that it doesn't go further than 5V.
I started with the main power supply that provides 340VDC, 12VDC, and 5VDC. Which is the logic components and the main power.

<img width="1190" height="499" alt="Screenshot 2026-06-11 at 6 47 15 PM" src="https://github.com/user-attachments/assets/8b06144d-1d1f-421b-b2a2-52b18fdc9e17" />

 
After that, I did the common useful 555 interrupter. The original design used an ATMEGA, but using a microcontroller in Tesla coils doesn't really seem like it provides much of an advantage. It's sensitive, requires programming, and has no real advantage over a 555 other than music I guess>

<img width="658" height="529" alt="Screenshot 2026-06-11 at 6 47 47 PM" src="https://github.com/user-attachments/assets/7b3c5253-ffd3-43d2-9c0f-2520802e098b" />

Finally, I did the main driving circuit. It uses the interrupter to turn it on and off, feedback from the antenna, to drive the half bridge primary,


<img width="1690" height="801" alt="Screenshot 2026-06-11 at 6 48 57 PM" src="https://github.com/user-attachments/assets/f7a662bb-d108-4795-be31-1662fb33ffc9" />

<img width="1481" height="1022" alt="Screenshot 2026-06-11 at 6 49 46 PM" src="https://github.com/user-attachments/assets/d05c749e-4ef1-4731-8f0b-8bd1bcc9d293" />
I then swapped out some stuff for terminals so that it's all easily replaceable and the heavy components aren't on the board itself.
<img width="1521" height="1105" alt="Screenshot 2026-06-11 at 6 53 06 PM" src="https://github.com/user-attachments/assets/f6566289-63db-4912-befc-21caf0db3096" />

Here's what it looks like (now finished)

<img width="1535" height="1065" alt="Screenshot 2026-06-11 at 7 00 14 PM" src="https://github.com/user-attachments/assets/68dd4935-4e35-4410-92ae-b2e1b119e77d" />
