# EC601 A2 (Team 18)

## Assignment 1: Changes to httpstat [Option 1]

## Members
**angrySloth357**: Shreeya Khadka  
**squirrelbomb**: Tianzhi Wu  
**RunzhouHan**: Runzhou Han

## Summary
Changed the original httpstat program which gives statistics of a web-page connection via:

1. Adding option to print average statistics for a user defined number of web-connections to one website.
2. Changing the display font color.
3. Adding new display template. 

## Old Usage

Command:
```bash
python httpstat.py <url> <options>
```

Example:
```bash
python httpstat.py https://google.com
```

**Old Example Output:**

![screenshot](day0.png)

## New Usage

Command:
```bash
python httpstat.py <url> <N> <options>
```

Example:
```bash
python httpstat https://google.com 5
```

## New Template

New template shows the statistics in different lines and there is indentation in each line.

## New Font Color

Convert print color of output of 'check curl args','print stderr' and 'parse output' these three parts from yellow to red, and output of 'body' part from blue to green. 


**New Example Output**
![screenshot](day1.png)
