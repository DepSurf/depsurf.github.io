# Function: <code>__do_compat_sys_newlstat</code>

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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581598112,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:632",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581598112,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684096,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:635",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684096,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802272,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:637",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802272,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874864,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:637",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874864,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582100672,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:664",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100672,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147232,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:652",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147232,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582172080,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:670",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172080,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582489376,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:688",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x64_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489376,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583012224,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:710",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012224,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583575360,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:727",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575360,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583791456,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:740",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583791456,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996912,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:762",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996912,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493346488,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:637",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__arm64_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493346488,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286892928,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:637",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__se_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286892928,
      "name": "__do_compat_sys_newlstat",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581843600,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:637",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843600,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781264,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:637",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781264,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834912,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:637",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834912,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
```

```json
{
  "name": "__do_compat_sys_newlstat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581904304,
      "name": "__do_compat_sys_newlstat",
      "external": false,
      "loc": "fs/stat.c:637",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newlstat",
        "fs/stat.c:__ia32_compat_sys_newlstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904304,
      "name": "__do_compat_sys_newlstat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
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
long int __do_compat_sys_newlstat(const char * filename, struct compat_stat * statbuf)
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
