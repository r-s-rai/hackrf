# Exploiting the Key Authentication Systems of Modern Vehicles
Final project for CSE569 Spring 2021 - Washington University in St. Louis  
This repository contains GNU Radio files for the Record and Replay attacks.

# Collaborators
1. Rohan Rai
2. Tiezheng Shao
3. Jeong Min Lim

# Instructions for Replay Attacks
0. Connect HackRF One device to the system. 
1. Run `hackrf_info` to confirm that the HackRF One is correctly loaded.
2. Run `gnuradio-companion` to launch GNU Radio Companion application.
3. Open `capture.grc`and change the `File Sink` node to the desired directory.
4. After running `capture.grc`, point the key fob towards the HackRF One antenna and press the button's signals that you wish to record. Then stop running `capture.grc`.
5. After capturing the data, open `replay.grc` and change `File Source` node to point to the captured data. After running `replay.grc`, your HackRF One will start broadcasting the captured key fob signal.  



