# COMMAND BASICS

## 1. The Prompt
- When we open the terminal, we see a prompt like: ***colt@linux:~$***
- It shows the shell is ready for input.
- Type commands and press **Enter**.
- If we type something invalid: ***colt@linux:~$ jakshdbd*** <br>
Result: ***command not found***

### TIPS 
- Use ← and → to move cursor left or right.
- Press ↑ to see previously entered commands.

## 2. Our First Command
- *Date* shows current date and time. <br>
***colt@linux:~$ date Tue 06 Oct 2021 11:11:06 AM PDT***
- *ncal*: shows calendar ("new cal"). <br>
***colt@linux:~$ ncal***

## 3. Case Matters!
- Commands are case sensetive
- *date* **≠** *Date*
- ***colt@linux:~$ Date*** <br>
  Result: ***command not found***

## 4. Command Structure
**command -option argument**
- Options(starts with -) modify behavior
- Arguments are the value or items the command acts on

## 5. Arguments
- echo: prints argument back(echoes)
- ***colt@linux:~$ echo mwahahahaha*** <br>
  Result: ***mwahahahaha***
- Pattern to remember: **command argument**
- *ncal* with arguments. <br>
  ***colt@linux:~$ ncal 1957*** → year <br>
  ***colt@linux:~$ ncal july 1957*** → month + year
- *sort* uses filename as argumet <br>
  ***colt@linux:~$ sort color.txt*** <br>
  Result: blue <br>
          green <br>
          indigo <br>
          orange <br>
          red <br>
          voilet <br>
          yellow<br>
- sort every element into alphabatical order

## 6. Options
- Options starts with a dash(-)
- They cahnge how a command works.
- Example: *ncal -j* (calendar with Julian day), *sort -r color.txt* (Sorts the lines of a text file in Reverse order)

## 7. ncal common options
- -h turn off highlighting of today's date
- -b bold the calendar
- -B turn off bold
- -M use Monday as first day of week
- -j use Julian days (days numbered from Jan 1)
- -3 show previous, current & next month
  #### Note:
  Case matters for options too! <br>
  *-B* **≠** *-b*
