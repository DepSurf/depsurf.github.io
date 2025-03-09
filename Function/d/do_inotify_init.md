# Function: <code>do_inotify_init</code>

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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887920,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:656",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887920,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581972880,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:664",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972880,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582106352,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:654",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106352,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582183616,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:663",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582183616,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582422181,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:663",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:__do_sys_inotify_init"
      ],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421856,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582476165,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:670",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:__do_sys_inotify_init"
      ],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582475840,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502432,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:669",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__do_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502432,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817488,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:674",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__do_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817488,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583373216,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:695",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__do_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583373216,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583958176,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:695",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__do_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958176,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181584,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:695",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__do_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181584,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584395584,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:694",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__do_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395584,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493743304,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:663",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493743304,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227266432,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:663",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227266432,
      "name": "do_inotify_init",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287355024,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:663",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287355024,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273350418,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:663",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273350418,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152352,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:663",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152352,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582089792,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:663",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089792,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142832,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:663",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142832,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int do_inotify_init(int flags)
```

```json
{
  "name": "do_inotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217488,
      "name": "do_inotify_init",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:663",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init",
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_init1",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_init1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217488,
      "name": "do_inotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int do_inotify_init(int flags)
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
