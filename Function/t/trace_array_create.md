# Function: <code>trace_array_create</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": true,
      "loc": "kernel/trace/trace.c:8319",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580556239,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580553872,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 655
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": true,
      "loc": "kernel/trace/trace.c:8370",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603813,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580601552,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": false,
      "loc": "kernel/trace/trace.c:8602",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_get_by_name",
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675712,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446744071580701903,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": false,
      "loc": "kernel/trace/trace.c:8694",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_get_by_name",
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666624,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
    },
    {
      "addr": 18446744071591319563,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": false,
      "loc": "kernel/trace/trace.c:9032",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_get_by_name",
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580665344,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
    },
    {
      "addr": 18446744071591261881,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": false,
      "loc": "kernel/trace/trace.c:9196",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_get_by_name",
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840032,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071592169969,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": false,
      "loc": "kernel/trace/trace.c:9229",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_get_by_name",
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069280,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
    },
    {
      "addr": 18446744071593943714,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581374992,
      "name": "trace_array_create",
      "external": false,
      "loc": "kernel/trace/trace.c:9320",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_get_by_name",
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374992,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581469600,
      "name": "trace_array_create",
      "external": false,
      "loc": "kernel/trace/trace.c:9479",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_get_by_name",
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469600,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
  "name": "trace_array_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581577651,
      "name": "trace_array_create",
      "external": false,
      "loc": "kernel/trace/trace.c:9738",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:instance_mkdir"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491900160,
      "name": "trace_array_create",
      "external": true,
      "loc": "kernel/trace/trace.c:8370",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491900160,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225842592,
      "name": "trace_array_create",
      "external": true,
      "loc": "kernel/trace/trace.c:8370",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225842592,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284987184,
      "name": "trace_array_create",
      "external": true,
      "loc": "kernel/trace/trace.c:8370",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284987184,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1224
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272188308,
      "name": "trace_array_create",
      "external": true,
      "loc": "kernel/trace/trace.c:8370",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272188308,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": true,
      "loc": "kernel/trace/trace.c:8370",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572613,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580570352,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": true,
      "loc": "kernel/trace/trace.c:8370",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519253,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580517024,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": true,
      "loc": "kernel/trace/trace.c:8370",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580563861,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580561600,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
struct trace_array * trace_array_create(const char * name)
```

```json
{
  "name": "trace_array_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_array_create",
      "external": true,
      "loc": "kernel/trace/trace.c:8370",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:instance_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620581,
      "name": "trace_array_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580618320,
      "name": "trace_array_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct trace_array * trace_array_create(const char * name)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct trace_array * trace_array_create(const char * name)
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
