# Function: <code>tty_get_pgrp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954400,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2507",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954400,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584286384,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2514",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286384,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584468480,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_io.c:2514",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468480,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584599280,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:397",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584599280,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585011616,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011616,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245776,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245776,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585365184,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585365184,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585579360,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585579360,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585720272,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720272,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586453599,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl"
      ],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586449952,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586564432,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:404",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586564432,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586449376,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:414",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586449376,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586976320,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:416",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586976320,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588273152,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:416",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588273152,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688208,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:416",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688208,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589992848,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:416",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589992848,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590331376,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:421",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590331376,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498412512,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498412512,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231084112,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231084112,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291597072,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291597072,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276069972,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276069972,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585481296,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481296,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585351216,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585351216,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585670672,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670672,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct pid * tty_get_pgrp(struct tty_struct * tty)
```

```json
{
  "name": "tty_get_pgrp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585778800,
      "name": "tty_get_pgrp",
      "external": true,
      "loc": "drivers/tty/tty_jobctrl.c:398",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/array.c:do_task_stat",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778800,
      "name": "tty_get_pgrp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
