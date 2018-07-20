# Polybar Docker Script

This is the most simple script for showing your launched Docker containers

```ini
[module/docker]
type = custom/script
exec = docker ps -q | wc -l
interval = 1
label =  %output%
```
