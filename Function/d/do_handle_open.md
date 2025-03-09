# Function: <code>do_handle_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401632,
      "name": "do_handle_open",
      "external": true,
      "loc": "fs/fhandle.c:214",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_SyS_open_by_handle_at",
        "fs/fhandle.c:SyS_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401632,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 718
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581579856,
      "name": "do_handle_open",
      "external": true,
      "loc": "fs/fhandle.c:214",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_SyS_open_by_handle_at",
        "fs/fhandle.c:SyS_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579856,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664784,
      "name": "do_handle_open",
      "external": true,
      "loc": "fs/fhandle.c:214",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_SyS_open_by_handle_at",
        "fs/fhandle.c:SyS_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664784,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581719200,
      "name": "do_handle_open",
      "external": true,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:compat_SyS_open_by_handle_at",
        "fs/fhandle.c:SyS_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719200,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581864336,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:216",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:compat_SyS_open_by_handle_at",
        "fs/fhandle.c:SyS_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864336,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582045088,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045088,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134160,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134160,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296480,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296480,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582395296,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582395296,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582681408,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582681408,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751888,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751888,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582780912,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780912,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583108784,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x64_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108784,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583590512,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583590512,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584195024,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584195024,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584422096,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:222",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422096,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643680,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:218",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643680,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493995016,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__arm64_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__arm64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493995016,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227459912,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:__se_sys_open_by_handle_at"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287642336,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__se_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__se_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287642336,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273511498,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fhandle.c:__se_sys_open_by_handle_at"
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582364032,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364032,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301728,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301728,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582354512,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354512,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
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
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```

```json
{
  "name": "do_handle_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434128,
      "name": "do_handle_open",
      "external": false,
      "loc": "fs/fhandle.c:215",
      "file": "fs/fhandle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fhandle.c:__x32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_compat_sys_open_by_handle_at",
        "fs/fhandle.c:__ia32_sys_open_by_handle_at",
        "fs/fhandle.c:__x64_sys_open_by_handle_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434128,
      "name": "do_handle_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 794
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle * ufh, int open_flag)
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
