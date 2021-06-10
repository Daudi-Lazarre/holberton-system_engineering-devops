Recreating files.
I'm not getting all of the checks;
I recreated file and assigned user permission with no luck.
Let me check everything else...
I checked the permissions of the 3-listfiles and found out that
the user permission for the user to execute was missing, so I filled it back in..
Time to push everything to github and see how it goes.

Excellent work, Lucas.
The push didn't work and here's why:

Each user's permissions was set to a default.
I had not yet changed the parameters I needed to in order to
make it look like the example on intranet.
This included permitting:
- all users to execute (a+x)
- Tbh, I'm struggling to recall the others at this moment, but I know what I did
and why the check marks were not appearing.

Time to upload. I know this is right, now... >:)

Yeah, so it turns out I wasn't correct. I realize now, thanks to some help from Justin,
that my answer for the question was "wrong".
For task 3, I entered "ls -la" which does list the files...
but the answer its looking for is "ls -l" which is the specific answer
The difference between the two is that ls -l opens the list with the visible files
while ls -la opens the list with all files, including hidden ones

Ironically, the next task had "ls -la", my previous answer from the last task.

Live and learn.

Task 5:
Note to self:
-- Check the damn manual. I figured out the the command I was looking for to add numerical values
to the list is ln -n
-- I found that in the manual

I made an update to the intranet after that and it worked... almost.
I realized that I had to update the permissions; I finished doing that now.
Time to upload. :D
