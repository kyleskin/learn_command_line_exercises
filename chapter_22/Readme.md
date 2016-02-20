#Chapter 21: EXPORT - Changing Environment Variables
`export` is used to change a variable in your environment

##Do More
###Take and list out all the environment variables you've found and then go look up what they are online

`rvm_bin_path`: Defines the bin path for RVM
`TERM_PROGRAM`: Shows which program is being used for the terminal
`GEM_HOME`: Shows path and version of gems and ruby
`SHELL`: Describes the shell that will be used
`TERM`: Specifies the type of terminal to emulate when running the shell
`CLICOLOR`: Defines color codes to be used
`IRBRC`
`TMPDIR`
`Apple_PubSub_Socket_Render`
`OLDPWD`
`MY_RUBY_HOME`
`USER`
`_system_type`
`rvm_path`
`SSH_AUTH_SOCK`
`__CF_USER_TEXT_ENCODING`
`rvm_prefix`
`PATH`
`PWD`
`LANG`
`ITERM_PROFILE`
`_system_arch`
`XPC_FLAGS`
`_system_version`
`XPC_SERVICE_NAME`
`rvm_version`
`SHLVL`
`COLORFGBG`
`HOME`
`ITERM_SESSION_ID`
`LOGNAME`
`GEM_PATH`
`RUBY_VERSION`: the version of Ruby being run
`_system_name`: 
`BASH_FUNC_parse_git_pair%%`
`BASH_FUNC_parse_git_branch%%`
`_`


###Read the man page for env again. What else can it do?

##Alternative English Questions
###1. Can you set the debug environment variable to true?
```
(master) Kyle Skinner
Kyle:learn_command_line_exercises $ export DEBUG="true"

(master) Kyle Skinner
Kyle:learn_command_line_exercises $ echo $DEBUG
true
```

###2. Can you remove the debug environment variable?
```
(master) Kyle Skinner
Kyle:learn_command_line_exercises $ unset DEBUG

(master) Kyle Skinner
Kyle:learn_command_line_exercises $ echo $DEBUG
```

