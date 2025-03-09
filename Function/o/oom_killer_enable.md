# Function: <code>oom_killer_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486576,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:481",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486576,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580570256,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:730",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580570256,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580637903,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:689",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_killer_disable"
      ],
      "caller_func": [
        "kernel/power/process.c:thaw_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637632,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580669969,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:692",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_killer_disable"
      ],
      "caller_func": [
        "kernel/power/process.c:thaw_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669696,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580755025,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:716",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_killer_disable"
      ],
      "caller_func": [
        "kernel/power/process.c:thaw_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754752,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893060,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:718",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893060,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580966688,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:726",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966688,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581061900,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:736",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061900,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117673,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:736",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117673,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581301415,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:738",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301415,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591325209,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:740",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591325209,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591267248,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:739",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591267248,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592191009,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:740",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592191009,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593966389,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:797",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593966389,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582405720,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:796",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_killer_disable"
      ],
      "caller_func": [
        "kernel/power/process.c:thaw_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582405376,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582611736,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:796",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_killer_disable"
      ],
      "caller_func": [
        "kernel/power/process.c:thaw_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611392,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582783304,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:793",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_killer_disable"
      ],
      "caller_func": [
        "kernel/power/process.c:thaw_processes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782960,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492486488,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:736",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492486488,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226359628,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:736",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226359628,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285772584,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:736",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285772584,
      "name": "oom_killer_enable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272550800,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:736",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272550800,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086521,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:736",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086521,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033705,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:736",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033705,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077721,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:736",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077721,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void oom_killer_enable()
```

```json
{
  "name": "oom_killer_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139598,
      "name": "oom_killer_enable",
      "external": true,
      "loc": "mm/oom_kill.c:736",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "mm/oom_kill.c:oom_killer_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139598,
      "name": "oom_killer_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
