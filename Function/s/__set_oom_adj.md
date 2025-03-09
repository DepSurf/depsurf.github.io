# Function: <code>__set_oom_adj</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636960,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1044",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636960,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 949
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
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725312,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1062",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725312,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 949
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
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777584,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1036",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777584,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926992,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1036",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926992,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 905
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1004",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582113104,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
    },
    {
      "addr": 18446744071582121536,
      "name": "__set_oom_adj.cold.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1024",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208336,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
    },
    {
      "addr": 18446744071582216096,
      "name": "__set_oom_adj.cold.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1037",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370976,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071582380246,
      "name": "__set_oom_adj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1037",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471184,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071582479158,
      "name": "__set_oom_adj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1047",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582768784,
      "name": "__set_oom_adj.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 871
    },
    {
      "addr": 18446744071582777489,
      "name": "__set_oom_adj.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1058",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582841824,
      "name": "__set_oom_adj.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
    },
    {
      "addr": 18446744071591345353,
      "name": "__set_oom_adj.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1057",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870208,
      "name": "__set_oom_adj.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
    },
    {
      "addr": 18446744071591288024,
      "name": "__set_oom_adj.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1061",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203824,
      "name": "__set_oom_adj.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
    },
    {
      "addr": 18446744071592247514,
      "name": "__set_oom_adj.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1060",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583700016,
      "name": "__set_oom_adj.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071594028162,
      "name": "__set_oom_adj.isra.0.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1061",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584310352,
      "name": "__set_oom_adj.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
    },
    {
      "addr": 18446744071596063538,
      "name": "__set_oom_adj.isra.0.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1061",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540176,
      "name": "__set_oom_adj.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1018
    },
    {
      "addr": 18446744071596587444,
      "name": "__set_oom_adj.isra.0.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1061",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584772048,
      "name": "__set_oom_adj.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1018
    },
    {
      "addr": 18446744071597493293,
      "name": "__set_oom_adj.isra.0.cold",
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
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494085528,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1037",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494085528,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
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
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227541448,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1037",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227541448,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
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
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287753360,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1037",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287753360,
      "name": "__set_oom_adj",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273576518,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1037",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273576518,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1037",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439920,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071582447894,
      "name": "__set_oom_adj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1037",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377088,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071582385062,
      "name": "__set_oom_adj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1037",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430400,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071582438374,
      "name": "__set_oom_adj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```

```json
{
  "name": "__set_oom_adj",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_oom_adj",
      "external": false,
      "loc": "fs/proc/base.c:1037",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "fs/proc/base.c:oom_adj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582510096,
      "name": "__set_oom_adj",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
    },
    {
      "addr": 18446744071582518540,
      "name": "__set_oom_adj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __set_oom_adj(struct file * file, int oom_adj, bool legacy)
```
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
