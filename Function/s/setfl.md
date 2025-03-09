# Function: <code>setfl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setfl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581069399,
      "name": "setfl",
      "external": false,
      "loc": "fs/fcntl.c:32",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:SyS_fcntl"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229888,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:32",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229888,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307712,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:32",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307712,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357056,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:34",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357056,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498544,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498544,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656624,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656624,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742880,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742880,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860160,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860160,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932512,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932512,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582162512,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162512,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582208960,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208960,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582233744,
      "name": "setfl",
      "external": false,
      "loc": "fs/fcntl.c:36",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233744,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552272,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:36",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552272,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
  "name": "setfl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583081336,
      "name": "setfl",
      "external": false,
      "loc": "fs/fcntl.c:36",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583647728,
      "name": "setfl",
      "external": false,
      "loc": "fs/fcntl.c:36",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647728,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583864912,
      "name": "setfl",
      "external": false,
      "loc": "fs/fcntl.c:37",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864912,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int setfl(int fd, struct file * filp, unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584071936,
      "name": "setfl",
      "external": false,
      "loc": "fs/fcntl.c:37",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071936,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493413896,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493413896,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226998060,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226998060,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286972400,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286972400,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273123406,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__se_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273123406,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901248,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901248,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838848,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838848,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892560,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892560,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int setfl(int fd, struct file * filp, long unsigned int arg)
```

```json
{
  "name": "setfl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581961072,
      "name": "setfl",
      "external": true,
      "loc": "fs/fcntl.c:35",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961072,
      "name": "setfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int setfl(int fd, struct file * filp, long unsigned int arg)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int setfl(int fd, struct file * filp, long unsigned int arg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int setfl(int fd, struct file * filp, long unsigned int arg)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int arg</code> ➡️ <code>unsigned int arg</code>
</li>
</ul>
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
