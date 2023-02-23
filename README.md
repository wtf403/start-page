# Minimalistic browser start page

Supervisord config example:
```ini
[program:startpage]
directory=/your/project/dir/path/
command=/usr/bin/python3 -m http.server 80
redirect_stderr=true
```

