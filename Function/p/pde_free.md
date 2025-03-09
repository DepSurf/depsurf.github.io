# Function: <code>pde_free</code>

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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582122576,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:36",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122576,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217008,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:36",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217008,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381136,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381136,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480048,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480048,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582780123,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582778656,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582853419,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582851952,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582881535,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880112,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583215151,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213728,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712389,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710832,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584323813,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322160,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584553798,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552112,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584785654,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:proc_register"
      ],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783968,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494101288,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494101288,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227551288,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227551288,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287769456,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287769456,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273586786,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273586786,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448784,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448784,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582385952,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385952,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582439264,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439264,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pde_free(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582519440,
      "name": "pde_free",
      "external": true,
      "loc": "fs/proc/generic.c:37",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_symlink",
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_register",
        "fs/proc/proc_net.c:proc_net_ns_exit",
        "fs/proc/proc_net.c:proc_net_ns_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582519440,
      "name": "pde_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void pde_free(struct proc_dir_entry * pde)
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
