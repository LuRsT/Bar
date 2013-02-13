Bar
===

Bar, a command to display a bar

Use this command to generate graph bars to display in the console or tmux of your choosing.

example:

    bar --command "acpi" --regex "([0-9]{1,3})\%"

This will display something like this (in green):

    [100%] ▇

if you want it to appear in your tmux, just put the flag --tmux in it:

    bar --command "acpi" --regex "([0-9]{1,3})\%" --tmux
    #[fg=green][100%] ▇#[default]

I will appear the same as the above if you're in tmux :)

I provide some examples (\*.sh) like the one above for you to try and create your own ( and please pull request the new ones so we can all enjoy them ).
