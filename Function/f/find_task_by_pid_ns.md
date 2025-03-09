# Function: <code>find_task_by_pid_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579494192,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:452",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_write_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494192,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579508266,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:452",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508176,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579528938,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:452",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528848,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579516460,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:453",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516368,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579542576,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:322",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542464,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579570238,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:334",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570128,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579607422,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:343",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607312,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579631754,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631648,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579657306,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657200,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579689857,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:412",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689664,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579668029,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:413",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667856,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579674845,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:413",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674672,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579752493,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:413",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752320,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579857298,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:413",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857088,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579998466,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:413",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/bpf/helpers.c:bpf_task_from_pid",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998224,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580052962,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:416",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/bpf/helpers.c:bpf_task_from_pid",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052720,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580095426,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:416",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/bpf/helpers.c:bpf_task_from_pid",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/tomoyo/common.c:tomoyo_select_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095184,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490831032,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490830912,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224861772,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224861664,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283665588,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283665392,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271502404,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271502286,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579633626,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633520,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579561946,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561840,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579630890,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630784,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_task_by_pid_ns(pid_t nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_task_by_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664698,
      "name": "find_task_by_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "init/main.c:rest_init",
        "init/main.c:rest_init",
        "kernel/debug/kdb/kdb_main.c:kdb_kill",
        "kernel/debug/kdb/kdb_main.c:kdb_pid",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "fs/proc/base.c:proc_task_readdir",
        "fs/proc/base.c:proc_task_lookup",
        "fs/proc/base.c:proc_pid_lookup",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664592,
      "name": "find_task_by_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
