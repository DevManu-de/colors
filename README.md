# colors
contains various color that can be used in a terminal emulator but not with ncurses

## Description

The colors are formatted in `[COLORNAME_WHERE]`

Example `BLACK_FG` sets black as foreground color

Example `BLACK_BRIGHT_FG` sets black bright as foreground color

Example `BLACK_BG` sets black as background color

Example `BLACK_BRIGHT_BG` sets black bright as background color


One exception is the COLOR RESET this resets the color to standard
`RESET_COLOR`
or
`COLOR_RESET`

## Usage

`puts(RED_FG "Hallo Welt" RESET_COLOR);`
or
`printf(RED_FG "%s" RESET_COLOR, <string>);`
or
`printf("%s%s%s", BLUE_BG, <string>, RESET_COLOR);`
