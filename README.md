# steam
This file represents the steam setup on arch linux.

# step 1
'sudo vim /etc/pacman.conf'     -- This file needs to be opened and for two following lines '#' needs to be removed.
  [multilib]                    -- Uncomment this line 
  Include = /etc/pacman.d/mirrorlist    -- Uncomment this line

# step 2
 'sudo pacman -Sy steam'        -- Install the 'steam'.
 
# step 3
 login into steam and enjoy the game of your choice.
