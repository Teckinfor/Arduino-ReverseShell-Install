For the moment, Windows Defender has patch this attack.
You can test this one desactivating manually Windows Defender.
I'm working to desactivate Windows Defender thanks the Arduino.
Thank you for waiting.

# What you need ?

- An arduino leonardo (or arduino pro micro)
- A computer with Windows 10 configured for an azerty keyboard for France

# HOW TO USE

1. Change the IP address in the script
2. Install the script on your Arduino Leonardo
3. Install NetCat on you computer if it's not already installed on your computer. (https://github.com/atomicobject/psinfo/tree/master/tools/nc111nt)
4. Run CMD with administrator's privilege and go to the NetCat's folder
5. Write "nc -lvnp 13337" ("13337" is the port; you can change this one for other but you'll need to change the port in the script too)
6. Run you Arduino Leonardo on the computer of your victim (it could be the same computer of the "hacker")

# Terms of use

- This script was created for educational purposes only.
- It is used to demonstrate the danger of leaving your PC on, when not in use.
- Hacking is illegal and I am in no way responsible for your actions.
- THANK YOU

~~~
Created by Teckinfor
24/02/2020
https://github.com/Teckinfor/Attack_Arduino_Leonardo-ReverseShell_Install
~~~
