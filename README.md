A one-stop package management solution for Arch-based platforms and a part of the [ZENWORKS](https://github.com/kbuckleys/ZENWORKS) Suite.

<b>ZENU</b> is an extensive Lua script that utilizes [paru](https://github.com/Morganamilo/paru) and [fzf](https://github.com/junegunn/fzf) to deliver a complete, minimal and convenient TUI solution for your Arch package queries, management and updates. The script will also automatically check whether fzf and paru are installed, if not; fzf will be installed automatically and then you'll be prompted with a choice between paru and paru-git, which ZENU will also install for you. In other words, you just make the script executable and run it. No need to worry about dependencies.

<img width="1000" height="1100" alt="2026-07-13-130522_hyprshot" src="https://github.com/user-attachments/assets/0869944b-b7da-4323-97e2-1a53d97b6bff" />

The script almost does it all, from flagging for bulk syncing, simultaneous additions/removals to filtering and bulk/selective updating. Explained as follows:

- <b>Flag:</b> This function marks a package for syncing, since you can have multiple operations staged in one go.
  
- <b>Invert:</b> Simply inverts your flags, useful for when you want to sync all available updates except for a few, in which case you select the ones you don't want to sync, then invert your selection.
  
- <b>Clear:</b> Well this one is pretty clear, eh? Get it? But yes, it will clear all flags.
  
- <b>Source:</b> A filter that toggles between all packages and only installed/local packages.
  
- <b>Update/Manage:</b> A toggle switch between the package manager and the update manager.
  
- <b>Sync:</b> Once you have your desired packages flagged for addition/removal, Sync will take care of the rest with no confirmation prompts except for installing packages. In which case, you'll only be prompted once more as a final confirmation.

> [!NOTE]
> At least one installed [nerd font](https://www.nerdfonts.com/) is recommended in order to see the Download and Remove indicator glyphs as seen in the preview. Otherwise -while it won't break the script- you will, however, see artifacts in the glyphs' stead. I did not wish to automatically install a nerd font given the obvious intrusion, since this should be purely the user's choice. 
