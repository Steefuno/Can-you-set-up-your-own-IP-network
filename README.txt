Rithvik Aleshetty - rra76
Steven Nguyen - shn27

1. Briefly discuss how you implemented each functionality: setting up
   interfaces, setting up default routes, and setting up
   per-destination routes.

   We used the commands ip addr on each host to set up the ip address and device interface.
   The default routes were set by using ip route add default and the per destination routes
   were set similarly but without the default. The help commands were used to find out the format.

2. Are there known issues or functions that aren't working currently in your
   attached code? If so, explain.

   The current commands.txt works however, there was an error in which for the last 4 commands using 
   "r1 ip route add h3 dev r1-eth3" resulted in an error which said something like "expecting a prefix inet instead
   of h1". After resetting virtualbox and all the settings, it worked fine.


3. What problems did you face developing code for this project?

   The problems faced were mostly in the setup. One of the group members had a difficult time
   setting up the virtualbox and the settings. There was trouble sending the file over using the scp command.
   I eventually was able to get it to work using piazza, but I also realized i could've used git to get the file as well.
   Another problem was getting traceroute installed since the command was not recognized.

4. What did you learn by working on this project?

   We learned how to work with a virtual machine and virtualbox. We have also
   learned about how netowrk topology files were used to emulate a the architecture
   of a network. Linux commands and commands like traceroute and ping were also learned.