COPYING INFORMATION FOR THIS FILE

README.txt - the README file for the Dr. Theobold text adventure game
Copyright (C) 2017  Christopher Howard

You may redistribute and/or modify this file under the terms of the
GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any
later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

ABOUT THIS GAME

`Dr. Theobold' is a text adventure game, which means that you play the
game in a terminal, and that you play by reading text in the terminal
and enter commands on the keyboard.

Commands need to be kept as simple as possible to be recognized. E.g.,
you would enter `put water in bottle' and not `put the water in the
bottle'.

Use the `help' command to see a list of available commands. The list
might not cover every possible command that can be used.

The game begins outside the front door of Dr. Theobold's house. The
door is locked, so you must figure out how to get in.

Depending on your PicoLisp installation settings, you may have access
to command history with either vi-like or emacs-like keyboard
shortcuts.

DEPENDENCIES

Developed with PicoLisp interpreter version 16.12. Available under the
MIT/X11 License from <http://software-lab.de/down.html>.

STARTING THE GAME

After installing the picolisp interpreter, CD into the program
directory and run

$ pil dr-theobold.l -start-game +
