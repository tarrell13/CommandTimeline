# CommandTimeline
CommandTimeline is designed for pentesters to log all commands run on your Linux testing platform. While you can use any version of Linux with CommandTimeline, the preferred platform is Kali Linux. All development and testing is done against Kali Linux.

## Commands to setup logging
* File to edit: .bashrc
  * `HISTSIZE=3000`
  * `HISTFILESIZE=5000`
  * `export HISTTIMEFORMAT="%F %T "`
  * `export HISTIGNORE="histor*:clear:exit"`
  * `export PROMPT_COMMAND='history -a'`
* File to edit: .bash_logout
  * `history -w`
* Run from Terminal
  * `export HISTTIMEFORMAT="%F %T "`
  * `history -w`
  * `reboot`
