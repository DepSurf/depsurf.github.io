# Function: <code>cgroup_sk_alloc_disable</code>

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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030736,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup.c:6275",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030736,
      "name": "cgroup_sk_alloc_disable",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064912,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup.c:6304",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064912,
      "name": "cgroup_sk_alloc_disable",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060240,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:5124",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060240,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111008,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:5791",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111008,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:5829",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170968,
      "name": "cgroup_sk_alloc_disable.cold.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580170208,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:5932",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218856,
      "name": "cgroup_sk_alloc_disable.cold.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580218112,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6351",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267805,
      "name": "cgroup_sk_alloc_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580266816,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6366",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315974,
      "name": "cgroup_sk_alloc_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580315120,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6426",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387442,
      "name": "cgroup_sk_alloc_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580386528,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315267,
      "name": "cgroup_sk_alloc_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580373536,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257451,
      "name": "cgroup_sk_alloc_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580376448,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491568192,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6366",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491568192,
      "name": "cgroup_sk_alloc_disable",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225532796,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6366",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225532796,
      "name": "cgroup_sk_alloc_disable",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284547552,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6366",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284547552,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271981492,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6366",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271981492,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6366",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284774,
      "name": "cgroup_sk_alloc_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580283920,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6366",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232182,
      "name": "cgroup_sk_alloc_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580231328,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6366",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276022,
      "name": "cgroup_sk_alloc_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580275168,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void cgroup_sk_alloc_disable()
```

```json
{
  "name": "cgroup_sk_alloc_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_sk_alloc_disable",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6366",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netprio_cgroup.c:write_priomap",
        "net/core/netclassid_cgroup.c:write_classid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329834,
      "name": "cgroup_sk_alloc_disable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580328752,
      "name": "cgroup_sk_alloc_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void cgroup_sk_alloc_disable()
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void cgroup_sk_alloc_disable()
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
