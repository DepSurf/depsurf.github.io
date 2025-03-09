# Function: <code>__do_compat_sys_newfstatat</code>

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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581598288,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:645",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581598288,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684272,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:648",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684272,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802464,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:650",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802464,
      "name": "__do_compat_sys_newfstatat",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875056,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:650",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875056,
      "name": "__do_compat_sys_newfstatat",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582100848,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:677",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100848,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147584,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:665",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147584,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582172432,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:683",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172432,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582489728,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:701",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x64_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489728,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583012640,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:723",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012640,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583575856,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:740",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575856,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583791952,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:753",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583791952,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583998032,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:775",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998032,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493346648,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:650",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__arm64_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493346648,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581843792,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:650",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843792,
      "name": "__do_compat_sys_newfstatat",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781456,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:650",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781456,
      "name": "__do_compat_sys_newfstatat",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835104,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:650",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835104,
      "name": "__do_compat_sys_newfstatat",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```

```json
{
  "name": "__do_compat_sys_newfstatat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581904496,
      "name": "__do_compat_sys_newfstatat",
      "external": false,
      "loc": "fs/stat.c:650",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__x32_compat_sys_newfstatat",
        "fs/stat.c:__ia32_compat_sys_newfstatat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904496,
      "name": "__do_compat_sys_newfstatat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char * filename, struct compat_stat * statbuf, int flag)
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
