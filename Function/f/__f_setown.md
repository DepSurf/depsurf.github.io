# Function: <code>__f_setown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581068208,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:101",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:f_setown",
        "fs/fcntl.c:SyS_fcntl"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068208,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581231960,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:105",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:SyS_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230400,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581309765,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:105",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:SyS_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308208,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581359298,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:107",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357584,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581500834,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499936,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581657388,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656432,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581743644,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742688,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581861518,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581859968,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581934097,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932320,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582163814,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162320,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582210262,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208752,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582235334,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:106",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233536,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582553924,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:109",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552064,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583082218,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:105",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583080272,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583649730,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:106",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647440,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583866891,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:107",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864624,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584073945,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:107",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071664,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493416480,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493413648,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227000476,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226998616,
      "name": "__f_setown",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286976108,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286973296,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273124446,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:__se_sys_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273122864,
      "name": "__f_setown",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581902833,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901056,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581840433,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838032,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581894145,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892368,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __f_setown(struct file * filp, struct pid * pid, enum pid_type type, int force)
```

```json
{
  "name": "__f_setown",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581963706,
      "name": "__f_setown",
      "external": true,
      "loc": "fs/fcntl.c:108",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_setown"
      ],
      "caller_func": [
        "fs/notify/dnotify/dnotify.c:fcntl_dirnotify",
        "fs/locks.c:lease_setup",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/net/tun.c:tun_chr_fasync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961600,
      "name": "__f_setown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
