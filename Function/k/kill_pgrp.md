# Function: <code>kill_pgrp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432992,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1459",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432992,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579445408,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1459",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445408,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465776,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1465",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465776,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579454304,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1487",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454304,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579482624,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1488",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482624,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499104,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1605",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499104,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532560,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1691",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532560,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555968,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555968,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582112,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1784",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582112,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619360,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1780",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619360,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599696,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1781",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599696,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605200,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1798",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605200,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680480,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1890",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680480,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774912,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1903",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774912,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907264,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1904",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907264,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956992,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1910",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956992,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579996272,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1901",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579996272,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490745584,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1784",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490745584,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224796336,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1784",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224796336,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283570240,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1784",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283570240,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271450628,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1784",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271450628,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558416,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1784",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558416,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487072,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1784",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487072,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555696,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1784",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555696,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int kill_pgrp(struct pid * pid, int sig, int priv)
```

```json
{
  "name": "kill_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588992,
      "name": "kill_pgrp",
      "external": true,
      "loc": "kernel/signal.c:1784",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588992,
      "name": "kill_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
