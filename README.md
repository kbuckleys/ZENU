A one-stop package management solution for Arch-based platforms and a part of the [ZENWORKS](https://github.com/kbuckleys/zenWORKS) Suite.

ZENU is an extensive Lua script that utilizes [paru](https://github.com/Morganamilo/paru) and [fzf](https://github.com/junegunn/fzf) to deliver a complete, minimal and convenient TUI solution for your package queries, management and updates.

<img width="1000" height="1100" alt="2026-07-13-130522_hyprshot" src="https://github.com/user-attachments/assets/0869944b-b7da-4323-97e2-1a53d97b6bff" />

The script functions are clearly stated in the header, and they should be sufficient for basic operations, such as flagging for bulk syncing, simultaneous adds/removals and filtering. Explained as follows:

- Flag: This function marks a package for syncing, since you can have multiple operations staged in one go.
- Invert: Simply inverts your flags, useful for when you want to sync all available updates except for a few, in which case you select the ones you don't want to sync, then invert your selection.
- Clear: Well this one is pretty clear, eh? Get it? But yes, it will clear all flags.
- Source: A filter that toggles between all packages and only installed/local packages.
- Update/Manage: A toggle switch between the package manager and the update manager.
- Sync: Once you have your desired packages flagged for addition/removal, Sync will take care of the rest with no confirmation prompts except for installing packages. In which case, you'll only be prompted once more as a final confirmation.

> [!CAUTION]
> At least one installed [nerd font](https://www.nerdfonts.com/) is recommended in order to see the Download and Remove indicator glyphs as seen in the preview.
