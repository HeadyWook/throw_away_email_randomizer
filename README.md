# Username and password randomizer
This program creates random usernames and passwords for throwaway email addresses. This spares the mental effort of
the user for making up a username and password. It also prevents the user from leaking personal identified information
by avoiding naming bias, such as using variants of an existing email address. Lastly, this program is run on a local
machine which is more secure than using an online string generator.

The program generates two random sets of strings, the length of which is determined by the user. The character set
includes lower (i.e., abc...xyz) and uppercase (i.e., ABC...XYZ) letters and numbers (i.e., 0-9). The only characters
omitted from the character set are: "0", "O", "l", and "I". This is done to avoid confusion as these characters often
look similar depending on the font. It should also be noted that online string generators do not exclude these
characters.

An example: Bob wishes to remain anonymous but wants to sign up for some service which requires an email address. He
already tried free throwaway email services, such as https://throwawaymail.com/ or https://www.guerrillamail.com/ and
they did not work. Over Tor browser, Bob can create a throwaway email at https://register.cock.li/ using a randomized
username and password generated by this program.

Output example:

Username: o7mB5f2nr3

Password: hTJ6u5rHVg
