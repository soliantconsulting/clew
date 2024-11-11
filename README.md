# clew

clew is a means to easily implement robust error trapping and handling in FileMaker solutions. It uses a suite of custom functions that also capture a trace of script calls and errors, and state information for each script in the call stack


# Releases

Grab the latest version of clew from https://github.com/soliantconsulting/clew/releases


# Acknowledgements

Marcelo Piñeyro, the main developer of the clew technique, wishes to acknowledge the following people for their contributions to clew:

- Andrew "Kaz" McLamore, for sharing with us his implementation of capturing errors in FileMaker as json objects, and using the single-pass loop technique as a pseudo "try" block
- Ken Worthley, for his insights into the original implementation of clew, and for writing the function that is now called error.InSubscriptRethrow
- Anders Monsen, for coming up with the name "clew", and being one of the early adopters of the technique
- My various other Soliant colleagues, whom provided valuable insights and feedback which helped clew be what it is today