# Function: <code>need_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580602655,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1424",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_shepherd"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703088,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1712",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703088,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768928,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1636",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768928,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580805072,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1640",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805072,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580894080,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1857",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894080,
      "name": "need_update",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030064,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1814",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030064,
      "name": "need_update",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581107616,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1816",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107616,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172416,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1812",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172416,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581230416,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1831",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230416,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581417808,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1840",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417808,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581460896,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1883",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581460896,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581481728,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1924",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481728,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736768,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1926",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736768,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582118112,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1955",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118112,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582592016,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1950",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592016,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582799440,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1960",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799440,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974032,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1964",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974032,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492620000,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1831",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492620000,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226470608,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1831",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226470608,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285939264,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1831",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285939264,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272645298,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1831",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272645298,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581199264,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1831",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199264,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146016,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1831",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146016,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581190464,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1831",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190464,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool need_update(int cpu)
```

```json
{
  "name": "need_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581253760,
      "name": "need_update",
      "external": false,
      "loc": "mm/vmstat.c:1831",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:quiet_vmstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253760,
      "name": "need_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool need_update(int cpu)
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
