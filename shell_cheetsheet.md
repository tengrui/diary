1. Find a way to confirm 'yes' for interactive program.
   Sometimes, we use -y option for yes confirm, but some tools do not have such option.
   Then we can use "echo "yes" | foo" command to do so.
   And a better way is to use "yes | foo" command.
   Of cause, a complex way is to use "expect" tool.

