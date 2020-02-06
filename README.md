# ManagersAndMoreMVP
The simplest, most bare-bones version of a simple, bare-bones way to track which managers are in the office for the day.

Here's the deal: I currently work at a car dealership as a receptionist. I have calendars for when various salespeople are working, but *not* one for the managers. There are 10-12 people that I might take calls for but will need to track if I know they are in that day. There's nothing like getting an angry call from a customer that hasn't received a call back after they left a voicemail at a desk I transferred them to not knowing the person wasn't there that day.

We have a non-tech solution, a simple table on our bulletin board with pushpins next to names of people who are in. However, this takes 10-12 pushpins and makes Swiss cheese of our bulletin board. 

So I thought I would make a thing. A pegboard or pushpin board but on the front desk computer.

My problems:
- I am not part of the IT department
- I am not an admin on the front desk machine 
- I am not able/ allowed to download any programs onto said machine
- My guess is that making something that accesses information outside the company's network would be a violation of our IT policy

So, I could just make a local file, right? In theory, yes. And I have. Using Notepad. And VSCode, while at home. 

To keep security and privacy concerns to a minimum, this is what I have done:
- The names on Github are different than the actual managers (Master Detective Clue FTW)
- The code does not access *anything* outside the local machine:
  - No jQuery or any other libraries
  - No Bootstrap
  - **vanilla JS, CSS Flexbox are all this uses** 


As of 2/6/2020, the minimum viable product has been up and running for some time: There are buttons with each manager's name that change color when clicked and change back when clicked again.

Sometimes, as mission creep sets in, one wants to have a solid record of the basics, the part that just worked. That is what this repository is. The bare minimum that worked. 

In the meantime, and when I am done, all one should need to use this code for themselves is to:
1. Copy code into a Notepad file
2. Change names (and maybe ids) to fit your needs
3. Save file as .htm
4. Open file using Chrome (the only browser I've used so far)

[Or to just see it...](https://carmelvineyard.github.io/ManagersAndMoreMVP/managersAndMoreMVP.htm)

Final note: as of 2/6/2020, I do not have the state of the buttons being saved into local storage, nor do I really plan to. Also, I suspect this readme is now longer than the actual code.


