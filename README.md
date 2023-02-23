# Minimalistic browser start page

![Screenshot](./start-page.png)

[Supervisord](https://github.com/Supervisor/supervisor) config example:
```ini
[program:startpage]
directory=/your/project/dir/path/
command=/usr/bin/python3 -m http.server 80
redirect_stderr=true
```

