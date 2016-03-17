     _________                      __   ___________           .__          
    \_   ___ \_______ __ __  ____ |  | _\__    ___/___   ____ |  |   ______
    /    \  \/\_  __ \  |  \/    \|  |/ / |    | /  _ \ /  _ \|  |  /  ___/
    \     \____|  | \/  |  /   |  \    <  |    |(  <_> |  <_> )  |__\___ \ 
     \______  /|__|  |____/|___|  /__|_ \ |____| \____/ \____/|____/____  >
            \/                  \/     \/                               \/ 

A bunch of useful Linux scripts. I have quite a few more that I'll be adding after I do a little cleanup of the code. These are scripts that could be useful in a server environment.

   * watchFreeSpace
      DESCRIPTION: Allows one to watch the fluctuation of free space on a system. Flags are not yet supported. What you don't see in the example is that the output is colorized, so imagine green lines when space has been freed and red for used space.

      EXAMPLE:
         [xtoff@crunk CrunkTools]$ ./watchFreeSpace 
         Delay between polls is 10. We're watching /home
         8163 MB free, 93%
         No changes        8163 MB free, 93%
         - 83 MB has been used      8080 MB free, 93%
         - 83 MB has been used      7997 MB free, 93%
         + 166 MB has been freed    8163 MB free, 93%
         No changes        8163 MB free, 93%
         No changes        8163 MB free, 93% 
