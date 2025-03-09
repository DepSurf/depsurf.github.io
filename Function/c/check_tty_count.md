# Function: <code>check_tty_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954864,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:280",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:tty_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954864,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584286656,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:278",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:__tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286656,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584468752,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:278",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:__tty_hangup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468752,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584553248,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:279",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553248,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964224,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:280",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964224,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:280",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204880,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585215002,
      "name": "check_tty_count.cold.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323264,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585333966,
      "name": "check_tty_count.cold.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585535152,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585546704,
      "name": "check_tty_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676032,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585687613,
      "name": "check_tty_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:282",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404448,
      "name": "check_tty_count.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071586416211,
      "name": "check_tty_count.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:279",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586519568,
      "name": "check_tty_count.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071591457782,
      "name": "check_tty_count.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:280",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586405872,
      "name": "check_tty_count.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071591399813,
      "name": "check_tty_count.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:279",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586932656,
      "name": "check_tty_count.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071592446242,
      "name": "check_tty_count.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:278",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219952,
      "name": "check_tty_count.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071594313781,
      "name": "check_tty_count.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589630864,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:272",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589630864,
      "name": "check_tty_count.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589934528,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:273",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589934528,
      "name": "check_tty_count.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590273088,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:273",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590273088,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498351000,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498351000,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231032240,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231032240,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291522384,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291522384,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276031718,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276031718,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437056,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585448637,
      "name": "check_tty_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585307104,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585318669,
      "name": "check_tty_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585626432,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071585638013,
      "name": "check_tty_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int check_tty_count(struct tty_struct * tty, const char * routine)
```

```json
{
  "name": "check_tty_count",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_tty_count",
      "external": false,
      "loc": "drivers/tty/tty_io.c:281",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585727888,
      "name": "check_tty_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071585745734,
      "name": "check_tty_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int check_tty_count(struct tty_struct * tty, const char * routine)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void check_tty_count(struct tty_struct * tty, const char * routine)
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
