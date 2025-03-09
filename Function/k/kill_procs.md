# Function: <code>kill_procs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580953476,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:325",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581102558,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:323",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581177776,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:323",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581224102,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:326",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581354902,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:326",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:359",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500080,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071581509694,
      "name": "kill_procs.cold.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:360",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581585920,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071581595550,
      "name": "kill_procs.cold.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:357",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696768,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071581706613,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:361",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581770208,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071581780053,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:357",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991360,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071582001971,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:381",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041200,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071591337591,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:385",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067664,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071591280291,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:397",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377568,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071592226423,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:393",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure_dev_pagemap",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879296,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071594005822,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583426816,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:424",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unmap_and_kill",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426816,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583647568,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:514",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unmap_and_kill",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647568,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842400,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:510",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unmap_and_kill",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842400,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493231172,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:361",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286742864,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:361",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286742864,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:361",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738944,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071581748789,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:361",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677584,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071581687413,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:361",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730256,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071581740101,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_procs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kill_procs",
      "external": false,
      "loc": "mm/memory-failure.c:361",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798512,
      "name": "kill_procs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071581808357,
      "name": "kill_procs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void kill_procs(struct list_head * to_kill, int forcekill, bool fail, long unsigned int pfn, int flags)
```
</details>
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
