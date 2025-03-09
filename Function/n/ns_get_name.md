# Function: <code>ns_get_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581213856,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:109",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213856,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378560,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:109",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378560,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456656,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:180",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456656,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581512992,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:193",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    },
    {
      "addr": 18446744071582883563,
      "name": "ns_get_name",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2404",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_readlink"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581512992,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581655184,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:194",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    },
    {
      "addr": 18446744071583043006,
      "name": "ns_get_name",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:2468",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_readlink"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655184,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818544,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:218",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818544,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581905536,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:218",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905536,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031072,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031072,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109008,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109008,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582345808,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:217",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345808,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582397440,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:217",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397440,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582424720,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:217",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582424720,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582747520,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:217",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747520,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583294688,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:217",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294688,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879024,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:217",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879024,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584100784,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:218",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584100784,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316880,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316880,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493648728,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493648728,
      "name": "ns_get_name",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227183648,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227183648,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287240928,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287240928,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273280564,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273280564,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582077744,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077744,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015264,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015264,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582069024,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069024,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int ns_get_name(char * buf, size_t size, struct task_struct * task, const struct proc_ns_operations * ns_ops)
```

```json
{
  "name": "ns_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140784,
      "name": "ns_get_name",
      "external": true,
      "loc": "fs/nsfs.c:215",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_readlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140784,
      "name": "ns_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
