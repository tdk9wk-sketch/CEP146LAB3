4. a) Not at all
   b) Kept only one copy of each text
   c) It would be longer, higher chance of same words reused
   d) Would have to return to the separate, before changed files

5. a) we can store different versions using a difference file. Changes between different versions of a file would only contain what changed
  given the file
   roses are red
  it would be this if red was deleted
   \-red
   b) track the name of the person who changed it using their file names.
   c) Send a message referring to the changes that are the same between lines, asking for a change. Showing both lines and asking what to change it to
   d) Using numbers, but when two people edit the same thing, it switches to decimals e. 1.1 + 1.2
   e) Requirement to add an explanation about the change
   f) They would have to use a branched/ancestry system that tracks what came from where.

Explanation:
   Upon file upload, it checks for wether or not there are changes.
   It then tracks what the changes are onto a txt document.
   Then it tracks the names of who changed it.
   Commits the changes to a new version

   After multiple versions have been uploaded, It performs the second part
   It checks each line of each new version
   if they have no similarities then its good to go
   If there are similarities, it requests a fix from both editors and waits for a new change.

Wrap up question:
   The most frustrating part about the cooperation was, while there were little issues with combining the lines, there wasn't a solid way we could turn the lines    into something that worked together efficiently. It's all combined effectively, but it isn't a poem.

   Our system solves the combining of the lines most efficiently, because we keep anything that is not original text, but we don't when they overlap

   If ten people tried to collaborate this way, they would very often overlap text, thus giving them errors

   Our design handles someone deleting an edited file, but unfortunately does not with the original file. With our design, the original file is expected to be 
   uploaded, yet copyable.
