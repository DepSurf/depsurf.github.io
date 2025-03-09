# Function: <code>tty_paranoia_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583961408,
      "name": "tty_paranoia_check",
      "external": true,
      "loc": "drivers/tty/tty_io.c:259",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961408,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584288464,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:259",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288464,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584470560,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:259",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470560,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584556304,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:260",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556304,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584966800,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:261",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584966800,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:261",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585200320,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585214570,
      "name": "tty_paranoia_check.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585333514,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319024,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585333514,
      "name": "tty_paranoia_check.cold.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585546294,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585531840,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585546294,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585687206,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672720,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585687206,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586410282,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:263",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_poll"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586399424,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586415670,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586523082,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:260",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_poll"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586514448,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071591457529,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586406410,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:261",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_poll"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586399376,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071591399267,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586933194,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:260",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_poll"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926064,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071592445676,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588231716,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:259",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:tty_poll"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588215920,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071594313703,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589639512,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:258",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589943242,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:259",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590281770,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:259",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/tty_io.c:tty_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498343952,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498343952,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231035944,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231035944,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291528352,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291528352,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276026980,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276026980,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585448230,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433744,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585448230,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585318262,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585303792,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585318262,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585637606,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623120,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585637606,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```

```json
{
  "name": "tty_paranoia_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585745806,
      "name": "tty_paranoia_check",
      "external": false,
      "loc": "drivers/tty/tty_io.c:262",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_compat_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:tty_poll",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/tty_io.c:tty_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731440,
      "name": "tty_paranoia_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585745806,
      "name": "tty_paranoia_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int tty_paranoia_check(struct tty_struct * tty, struct inode * inode, const char * routine)
```
</details>
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
