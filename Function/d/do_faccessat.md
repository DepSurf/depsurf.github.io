# Function: <code>do_faccessat</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581556672,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:362",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556672,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581642160,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:351",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581642160,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758880,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:352",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758880,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831088,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:352",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831088,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
long int do_faccessat(int dfd, const char * filename, int mode, int flags)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582051744,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:398",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat2",
        "fs/open.c:__x64_sys_faccessat2",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582051744,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
long int do_faccessat(int dfd, const char * filename, int mode, int flags)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582095136,
      "name": "do_faccessat",
      "external": false,
      "loc": "fs/open.c:398",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat2",
        "fs/open.c:__x64_sys_faccessat2",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095136,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
long int do_faccessat(int dfd, const char * filename, int mode, int flags)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582119776,
      "name": "do_faccessat",
      "external": false,
      "loc": "fs/open.c:399",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat2",
        "fs/open.c:__x64_sys_faccessat2",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582119776,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
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
long int do_faccessat(int dfd, const char * filename, int mode, int flags)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436608,
      "name": "do_faccessat",
      "external": false,
      "loc": "fs/open.c:396",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat2",
        "fs/open.c:__x64_sys_faccessat2",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436608,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
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
long int do_faccessat(int dfd, const char * filename, int mode, int flags)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953440,
      "name": "do_faccessat",
      "external": false,
      "loc": "fs/open.c:420",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat2",
        "fs/open.c:__x64_sys_faccessat2",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953440,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
long int do_faccessat(int dfd, const char * filename, int mode, int flags)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583511088,
      "name": "do_faccessat",
      "external": false,
      "loc": "fs/open.c:420",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat2",
        "fs/open.c:__x64_sys_faccessat2",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583511088,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
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
long int do_faccessat(int dfd, const char * filename, int mode, int flags)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725984,
      "name": "do_faccessat",
      "external": false,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat2",
        "fs/open.c:__x64_sys_faccessat2",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725984,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
long int do_faccessat(int dfd, const char * filename, int mode, int flags)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583927392,
      "name": "do_faccessat",
      "external": false,
      "loc": "fs/open.c:462",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat2",
        "fs/open.c:__x64_sys_faccessat2",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927392,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493294392,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:352",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__arm64_sys_access",
        "fs/open.c:__arm64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493294392,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226897572,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:352",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__se_sys_access",
        "fs/open.c:__se_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226897572,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286832528,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:352",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__se_sys_access",
        "fs/open.c:__se_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286832528,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 888
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273039374,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:352",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__se_sys_access",
        "fs/open.c:__se_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273039374,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799824,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:352",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799824,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581737488,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:352",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581737488,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791136,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:352",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791136,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
long int do_faccessat(int dfd, const char * filename, int mode)
```

```json
{
  "name": "do_faccessat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860272,
      "name": "do_faccessat",
      "external": true,
      "loc": "fs/open.c:352",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "fs/open.c:__ia32_sys_access",
        "fs/open.c:__x64_sys_access",
        "fs/open.c:__ia32_sys_faccessat",
        "fs/open.c:__x64_sys_faccessat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860272,
      "name": "do_faccessat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int do_faccessat(int dfd, const char * filename, int mode)
```
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
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
