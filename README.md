# Customise-Mac-OS-X
Hey folks, DO you use mac ?? Yeah ? Great !!! 
Lets make it more beautiful 

1. Get rid-off boring terminal and lets go for iTerm
	 Download the iTerm terminal from https://www.iterm2.com/
	 
2. To install applications from command line you will need a brew package manager available for mac os x.
   steps to install home-brew
   - Open your iTerm (command+space then type iterm )
   - Type following command on iTerm window 
   - ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
   - There you go !!!
   - Now you can install any app from command line e.g brew cask install google-chrome 
   
3. Lets make your Iterm more beautiful
   Lets use a zsh configurations to make iterm cool.
   steps to install oh-my-zsh
   - Open your iTerm.
   - Type the following command on iTerm window.
   - sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
   - Congo !! now yor are zsh user.
   
4. Lets customise your zsh profile 
  - Now type the following command.
  - vi ~/.zshrc
  - You will see zsh configuration file in your vim.
  - At the top of the file you can see ZSH_THEME="robbyrussell"
  - 'robbyrussell' is a deault theme and you can change the theme as you wish.
  - e.g keeping it as 'ZSH_THEME=random' will generate a new random theme each time you open up your iTerm.
  - Type the command : source ~/.zshrc ( basically this command loads your all zsh profile enviorment variables and settings)
  - For more help go to : https://github.com/robbyrussell/oh-my-zsh
  
5. Some more terminal(iTerm) shortcuts:
   - Typing the 'command+D' will split yout terminal into the 2 vertical sections. This helps you when you want more than one    sessions for working.
   - Typing 'command+shift+D' will split the window horizontally.
   - You can also set the aliases for your frequently used command by typing the command : alias new_name='command_name'
   - e.g alias ex = 'exit' and now again load your settings by typing the command: source ~/.zshrc 
   - From next time onwards whenever you wish to exit from iterm, you can simply type 'ex'
  
6. Fun part ;)
   - Try command: say "hello" (Your mac will speak out whatever you have specified :D)
   - Lets put this in your zshrc file and load zshrc file and Let mac welcomes you whenever you start your laptop or terminal 
  
   


