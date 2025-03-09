# Function: <code>do_eventfd</code>

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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581920880,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:383",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581920880,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005248,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:383",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005248,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141856,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:391",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141856,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582219056,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:406",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219056,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582455456,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:404",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455456,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512224,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:407",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512224,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582540000,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:407",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540000,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582856112,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:405",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582856112,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583418752,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:405",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418752,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584006240,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:414",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006240,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584231968,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:389",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584231968,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584446752,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:377",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446752,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493784496,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:406",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__arm64_sys_eventfd",
        "fs/eventfd.c:__arm64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493784496,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227298872,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:406",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__se_sys_eventfd",
        "fs/eventfd.c:__se_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227298872,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287397952,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:406",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__se_sys_eventfd",
        "fs/eventfd.c:__se_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287397952,
      "name": "do_eventfd",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273376994,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:406",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__se_sys_eventfd",
        "fs/eventfd.c:__se_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273376994,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582187792,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:406",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582187792,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125360,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:406",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125360,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582178272,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:406",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178272,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int do_eventfd(unsigned int count, int flags)
```

```json
{
  "name": "do_eventfd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582255552,
      "name": "do_eventfd",
      "external": false,
      "loc": "fs/eventfd.c:406",
      "file": "fs/eventfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventfd.c:__ia32_sys_eventfd",
        "fs/eventfd.c:__x64_sys_eventfd",
        "fs/eventfd.c:__ia32_sys_eventfd2",
        "fs/eventfd.c:__x64_sys_eventfd2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255552,
      "name": "do_eventfd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int do_eventfd(unsigned int count, int flags)
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
