##Command line instructions

- Command line instruction
	-  A whole comand line instruction that the shell, bash, cmd, powerShell can read it.
	-  exmpl: <span style="color:rgb(255, 192, 0)">git </span><span style="color:rgb(0, 112, 192)">config</span> <span style="color:rgb(255, 255, 0)">--global </span>**user.name** <span style="color:rgb(112, 48, 160)">"username"</span>

- Parts of it
	-  command/program name (utility)
		-  <span style="color:rgb(255, 192, 0)">git</span>  
			-> this is the program
			-> name: command / executable /utility
			-> here: the Git CLI (command-line Interface)
	-  subcommand (basic command)
		-  <span style="color:rgb(0, 112, 192)">config</span>  
			-> this tells the program(GIT) what to do.
			-> name: subcommand
			-> meaninig: "configuration handling"
			-> example; <span style="color:rgb(255, 192, 0)">git </span><span style="color:rgb(0, 112, 192)">config</span> -> "git, work in config mod"
	-  option/flag/switch
		-  <span style="color:rgb(255, 255, 0)">--global </span>
			-> this changes the working mechanics of the command
			-> name: option/flag/switch
			-> type: long-form option (bcous of the "--") -> meaning: global scope
	-  argument (key/target)
		- **user.name**
			-> this is what I set
			-> name: argument -> specificly: configuration key
			-> form: section.name
				- user -> section 
				- email -> key
	-  argument (value)
		- <span style="color:rgb(112, 48, 160)">"username"</span>
			-> this is what I assign to the key
			-> name: value/argument value
			-> string (bcouse there can be special characters)
	
- full structure
	-  <span style="color:rgb(255, 192, 0)">git </span>               -> command (program)
	-  <span style="color:rgb(0, 112, 192)">config</span>         -> subcommand
	-  **--global**      -> option/flag
	-  <span style="color:rgb(255, 255, 0)">user.name</span> -> argument (key)
	-  <span style="color:rgb(112, 48, 160)">"...."</span>              -> argument (value)
					
			
	