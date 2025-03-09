# Function: <code>getrusage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int getrusage(struct task_struct * p, int who, struct rusage * ru)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458048,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1631",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/sys.c:SyS_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458048,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int getrusage(struct task_struct * p, int who, struct rusage * ru)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471264,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1631",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/sys.c:SyS_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471264,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int getrusage(struct task_struct * p, int who, struct rusage * ru)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491664,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1632",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/sys.c:SyS_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491664,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479760,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1668",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/sys.c:C_SYSC_getrusage",
        "kernel/sys.c:SYSC_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479760,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1082
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507632,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1675",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/sys.c:C_SYSC_getrusage",
        "kernel/sys.c:SYSC_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507632,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1082
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533008,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1729",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533008,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1097
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569120,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1730",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569120,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1097
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592512,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1730",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592512,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618560,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1720",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618560,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579649088,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1736",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649088,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629632,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1737",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629632,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579636336,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1754",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636336,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712864,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1763",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712864,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814416,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1775",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814416,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1105
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579950512,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1780",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950512,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1105
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000320,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1798",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000320,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1063
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039728,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1798",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039728,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1187
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490784912,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1720",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490784912,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224821168,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1720",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__se_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224821168,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1056
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283609760,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1720",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283609760,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1156
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271468008,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1720",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271468008,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594864,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1720",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594864,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523504,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1720",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523504,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592144,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1720",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592144,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
void getrusage(struct task_struct * p, int who, struct rusage * r)
```

```json
{
  "name": "getrusage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625808,
      "name": "getrusage",
      "external": true,
      "loc": "kernel/sys.c:1720",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/sys.c:__do_compat_sys_getrusage",
        "kernel/sys.c:__do_sys_getrusage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625808,
      "name": "getrusage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rusage * r</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rusage * ru</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
