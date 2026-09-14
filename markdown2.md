# Creating & Checking a Hash

A hash is a irreversible string of characters that are put in a unique order and way as a digital fingerprint for files on a device. Once a single word, letter, or character is change within that file, the has changes to a different has then before. This is a great basic way to check for the integrity of a file to make sure nothing was tampered with while on a device or system. 
#
Microsoft Windows uses "SHA256" as a secured and widely used algorithm that outputs 256-bit string of characters by default. We first want to grab the hash of the file and make sure to make note of it. you can do this by doing these steps below..

* Find or create the file that you are wanting to target so you can get the hash from it. Make sure to make note of the files name, extinction, and the file path starting from the `C:` drive all the way to the file you are wanting to grab a hash for. Make sure to save that file, You will need to put this in the command that is going to be ran.
  
*  Open PowerShell as an administrator and type `"Get-FileHash "C:\ path to your file with the extinction"`, check example below..
      * <img width="450" height="25" alt="Screenshot 2026-09-13 233613" src="https://github.com/user-attachments/assets/88c6cf49-397a-4f5a-858a-1ba70626fa59" />
      
* Click enter, and the command will output a "SHA256" hash with the path showing next to it on the right side.
#
Make sure to make note of the hash that you get so when you check it again you will know if the file has been tampered with or not. Hashes can be very long and it may be hard to see, you can try different hashing tools online to verify hashes and make sure that they match. Below I provided a site I have been using for a while to verify hashes.
https://onlinehashtool.com/compare-hash/</a>.
