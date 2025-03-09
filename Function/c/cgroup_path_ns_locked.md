# Function: <code>cgroup_path_ns_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579972432,
      "name": "cgroup_path_ns_locked",
      "external": false,
      "loc": "kernel/cgroup.c:2276",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_path_ns",
        "kernel/cgroup.c:task_cgroup_path",
        "kernel/cgroup.c:cgroup_release_agent",
        "kernel/cgroup.c:proc_cgroup_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972432,
      "name": "cgroup_path_ns_locked.isra.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002800,
      "name": "cgroup_path_ns_locked",
      "external": false,
      "loc": "kernel/cgroup.c:2318",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_release_agent",
        "kernel/cgroup.c:proc_cgroup_show",
        "kernel/cgroup.c:task_cgroup_path",
        "kernel/cgroup.c:cgroup_path_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002800,
      "name": "cgroup_path_ns_locked.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580034400,
      "name": "cgroup_path_ns_locked",
      "external": false,
      "loc": "kernel/cgroup.c:2328",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_release_agent",
        "kernel/cgroup.c:proc_cgroup_show",
        "kernel/cgroup.c:task_cgroup_path",
        "kernel/cgroup.c:cgroup_path_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034400,
      "name": "cgroup_path_ns_locked.isra.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580042800,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1916",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042800,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580092336,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2094",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092336,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580151440,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2112",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580151440,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580199088,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2153",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199088,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580246064,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2289",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246064,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294288,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2290",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294288,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580382570,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2217",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365408,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580369482,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2213",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580352352,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580372506,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2226",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355472,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580533127,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2281",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512688,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580730484,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2285",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709344,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581006276,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2346",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_path_ns"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982784,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581094886,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2354",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_path_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070704,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168176,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2363",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_path_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168176,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491544528,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2290",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491544528,
      "name": "cgroup_path_ns_locked",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225509420,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2290",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225509420,
      "name": "cgroup_path_ns_locked",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284515056,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2290",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284515056,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271960176,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2290",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271960176,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263088,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2290",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263088,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580210592,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2290",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210592,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580254336,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2290",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580254336,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_path_ns_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580307680,
      "name": "cgroup_path_ns_locked",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2290",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307680,
      "name": "cgroup_path_ns_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int cgroup_path_ns_locked(struct cgroup * cgrp, char * buf, size_t buflen, struct cgroup_namespace * ns)
```
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
