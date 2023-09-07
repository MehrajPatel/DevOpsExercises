## Basic Date

### Objectives

1. Write a script that will put the current date in a file called "the_date.txt"

### Solution

```
#!/usr/bin/env bash

echo $(date) > the_date.txt
```
2. Write a script that will put the yesterday's date in a file called "yesterday_date.txt"

### Solution

```
#!/usr/bin/env bash

echo $(date -d "yesterday") > yesterday_date.txt
```
