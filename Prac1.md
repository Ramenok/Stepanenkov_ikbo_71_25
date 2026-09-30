### 1 Task: ###
grep -o '^[^:]*' /etc/passwd | sort 
### 2 Task: ###
cat /etc/protocols | grep -v '^#' | sort -nr | head -n 5 | awk '{print $1, $2}'
