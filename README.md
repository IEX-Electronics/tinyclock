# tinyclock

## What is this?
This tinyclock was designed to be placed on top of my Bambu Lab H2S using power from the USB port. (Yes, I know, it's janky), but since my room doesn't have a clock or other
timekeeping mechanism, and the printer doesn't have one, I thought it would be pretty nifty to have a little no-controls 4-segment display clock (using bluetooth/wifi for initial setup)
to connect to the internet to NTP servers such as time.apple.com, which automatically set date/time based on IP. (No need to reset for daylight savings time). Originally, I also intended
to make a USB to dual USB adapter, but I ran out of budget for tier 4. 

## Concept Sketches
<img width="1920" height="905" alt="スクリーンショット 2026-01-08 20 12 07" src="https://github.com/user-attachments/assets/719bbffd-eb2b-4596-bb60-b4dd04b567bc" />
PCB with resistors added. I don't have any 3D model for seeed studio rp2040 nor the 7-segment display, but this is how it should look, (roughly)

<img width="1792" height="1132" alt="スクリーンショット 2026-01-09 8 27 38" src="https://github.com/user-attachments/assets/b14a576d-0e62-4fec-b7f4-bdc7c44765f7" />
Chassis with connetor body (this makes sure that it can stay upright.


<img width="1822" height="1185" alt="スクリーンショット 2026-01-12 8 17 39" src="https://github.com/user-attachments/assets/1867b762-7604-486e-8371-44fcc636d8e1" />
PCB Layout... It's not the prettiest, but it gets the job done, and is clean (enough)

<img width="1392" height="832" alt="スクリーンショット 2026-01-12 8 18 18" src="https://github.com/user-attachments/assets/dab3ef27-e4f5-4462-8144-351780968c26" />
3D models of the final PCB. I don't really have 3D models available for either the XIAO RP-2040 nor the 7-segment display, but, you get the idea.

## Side Note
Hellos, I don't quite have a great idea for the size of chassis yet, as I don't have 3D models of the components listed above, but once I recieve the components and is able to measure myself, the rest of the process will probably go a lot smoother.
