# Function: <code>do_sched_yield</code>

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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626480,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:4958",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__x64_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626480,
      "name": "do_sched_yield",
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664016,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:4943",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__x64_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664016,
      "name": "do_sched_yield",
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579692704,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5396",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__x64_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692704,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733088,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5587",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__x64_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733088,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769584,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5820",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__do_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769584,
      "name": "do_sched_yield",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758224,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:6636",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__do_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758224,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765376,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:6937",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__do_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765376,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:8130",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__do_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855744,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071592107341,
      "name": "do_sched_yield.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:8238",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__do_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971792,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071593875081,
      "name": "do_sched_yield.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:8422",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__do_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131792,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071595977467,
      "name": "do_sched_yield.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:8531",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__do_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193872,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071596495307,
      "name": "do_sched_yield.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:8535",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__do_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580241488,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071597392153,
      "name": "do_sched_yield.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490913432,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5587",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__arm64_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490913432,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224928756,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5587",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224928756,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283758032,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5587",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283758032,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271551452,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5587",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271551452,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709744,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5587",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__x64_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709744,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637600,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5587",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__x64_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637600,
      "name": "do_sched_yield",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699216,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5587",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__x64_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699216,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void do_sched_yield()
```

```json
{
  "name": "do_sched_yield",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579740288,
      "name": "do_sched_yield",
      "external": false,
      "loc": "kernel/sched/core.c:5587",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:yield",
        "kernel/sched/core.c:__x64_sys_sched_yield"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740288,
      "name": "do_sched_yield",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void do_sched_yield()
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
