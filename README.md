small-photo-contest
===================

Script created to help organize a small "between friends" photo contest.


The contestants were also the jury. 
The photos had to be anonymous so the votes could be as unbiased as possible.
Noone wated to be organizer because everyone wanted to participate in the contest and therefor noone wanted to be
in the position to know the photos before the voting.
The photo submission should be simple and there was very little spare time to code something fantastic.

This was my fast (couple of hours coding) solution.

- Created a gmail account
- Created a script to check the gmail account for new messages
- Contestants should send their photographs to this email address
- The script reads the email:
  - extracts attachment into an randomly named file
  - contestant name, email address and randomly assigned number is stored in one "contestants" file
  - contestant number and photo file name is stored in another "photos" file


Organizer should / must only check the "photos" file after the voting.
Organizer can read the "contestants" file without knowing the photos.


