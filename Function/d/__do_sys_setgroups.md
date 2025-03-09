# Function: <code>__do_sys_setgroups</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579600328,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579637230,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579662045,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579699117,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t * grouplist)
```

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579739744,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739744,
      "name": "__do_sys_setgroups",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t * grouplist)
```

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721152,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721152,
      "name": "__do_sys_setgroups",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t * grouplist)
```

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579728512,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:185",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579728512,
      "name": "__do_sys_setgroups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
long int __do_sys_setgroups(int gidsetsize, gid_t * grouplist)
```

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579808560,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:185",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808560,
      "name": "__do_sys_setgroups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
long int __do_sys_setgroups(int gidsetsize, gid_t * grouplist)
```

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579918928,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:185",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918928,
      "name": "__do_sys_setgroups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
long int __do_sys_setgroups(int gidsetsize, gid_t * grouplist)
```

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073632,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:198",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073632,
      "name": "__do_sys_setgroups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
long int __do_sys_setgroups(int gidsetsize, gid_t * grouplist)
```

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126464,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:198",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126464,
      "name": "__do_sys_setgroups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
long int __do_sys_setgroups(int gidsetsize, gid_t * grouplist)
```

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170816,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:198",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170816,
      "name": "__do_sys_setgroups",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490881760,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__arm64_sys_setgroups"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224897212,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283713992,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271532628,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579675437,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579603773,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579672669,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_setgroups",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579706797,
      "name": "__do_sys_setgroups",
      "external": false,
      "loc": "kernel/groups.c:190",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int __do_sys_setgroups(int gidsetsize, gid_t * grouplist)
```
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
