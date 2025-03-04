# Changelog

### master

### v1.1.0, 04.03.2025
- Added a check for the presence of the DISPLAY variable at the beginning of the script
- All variables are enclosed in quotation marks
- Added the-r flag to the read command
- Improved checking for zsh and the renew_tmux_env function
- The case construct is used instead of multiple if/elifs for greater readability.
- Separate vi and vim processing (xrestore for vi only)
- Improved handling of variables in the loop (separate pane and cmd)
- Safer handling of paths and variables
- Fixed duplicate export DISPLAY command for bash/zsh
- Added comments to improve understanding of the code
