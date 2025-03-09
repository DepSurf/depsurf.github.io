# Function: <code>do_fcntl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581068968,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:243",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581231160,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:247",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581308968,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:247",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358720,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:324",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:compat_SyS_fcntl",
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358720,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500256,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:compat_SyS_fcntl",
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500256,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657088,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657088,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1373
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581743344,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743344,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860624,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1358
    },
    {
      "addr": 18446744071581864726,
      "name": "do_fcntl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932976,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932976,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1370
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582163024,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582163024,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1233
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209472,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209472,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234240,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:330",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582234240,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1416
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552816,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:334",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552816,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1430
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583081120,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:314",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583081120,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1589
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583648752,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:315",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583648752,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1342
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583865920,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:316",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583865920,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1334
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072960,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:316",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072960,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1348
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493415568,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__arm64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493415568,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2104
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226999364,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__se_sys_fcntl64",
        "fs/fcntl.c:__se_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226999364,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1952
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286974784,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__se_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286974784,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273123992,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:__se_sys_fcntl"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901712,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901712,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1370
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839312,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839312,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1370
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581893024,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893024,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1370
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```

```json
{
  "name": "do_fcntl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962576,
      "name": "do_fcntl",
      "external": false,
      "loc": "fs/fcntl.c:325",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962576,
      "name": "do_fcntl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1395
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file * filp)
```
</details>
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
