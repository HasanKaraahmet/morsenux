# morsenux
A simple text-to-Morse Code program for Linux

MorseNux (short for "Morse for Linux") is a lightweight program that turns plain text into both a visual and audible Morse Code. It is essentially just a shell script that should run on even the oldest computer you've got laying around. If it's got a screen you will be able to see the Morse Code and if it's got speakers, you will be able to hear the tone for the Morse Code. That's right, MorseNux utilizes the computer's speakers (it uses sox for that) instead of the buzzer on the mainboard. This is by design so that you can plug the audible signal into your HAM radio transcereiver and actually transmit the Morse Code you generate. Or really, all you need to do is bring your radio's mic near your computer's speakers and you're good to go!

PRE-REQUISITES

If your distro doesn't already have it, you might need to install sox for MorseNux to work on your computer.

sudo apt install sox

CORE CAPABILITIES
1. Turn your text into visual-audible Morse Code (using PC speakers)
2. Translate only based on the INTERNATIONAL MORSE CODE 
3. Understand English letters, numbers, Turkish letters, as well as most punctuation marks
4. Also be able to read text from a user-specified file

FEATURES UNDER DEVELOPMENT
1. Ability to turn audio (waw, mp3) files with Morse Code back into text

ABOUT THE AUTHOR

I'm actually a struggling real estate consultant, not a software developer in any professional capacity. However, I AM a serious hobbyist and licensed Class-A amateur radio operator (HAM) in Turkiye (station callsign: TA1HYK), and I do use Linux every day and fool around with BASH scripting once in a while. MorseNux is the end result of me needing a field-deployable offline solution to quickly and easily transmit Morse Code using nothing more than a laptop/smart phone and one of my handheld walkie talkies. It's meant to be free, easy to use, lightweight and of course open-source. 

THANKS

Thank you for taking the time to read this Read Me file. If you've tried, enjoyed and found MorseNux useful, please do tell your friends about it. If you're feeling extra super-awesome-mega generous, please consider making a small donation to the project. (IBAN: TR39 0006 2000 4620 0006 6627 73)
