# Function: <code>validate_prctl_map_addr</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579577136,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1905",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577136,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603232,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1895",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603232,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579635072,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1911",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635072,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614944,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1912",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614944,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621248,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1929",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621248,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579697552,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1907",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697552,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579790224,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1919",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790224,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937280,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1924",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937280,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986880,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1942",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986880,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026288,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1955",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026288,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490763720,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1895",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490763720,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224808744,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1895",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224808744,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283594048,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1895",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283594048,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271459000,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1895",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271459000,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579579536,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1895",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579536,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579508160,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1895",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508160,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579576816,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1895",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576816,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
```

```json
{
  "name": "validate_prctl_map_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579611120,
      "name": "validate_prctl_map_addr",
      "external": false,
      "loc": "kernel/sys.c:1895",
      "file": "kernel/sys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611120,
      "name": "validate_prctl_map_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int validate_prctl_map_addr(struct prctl_mm_map * prctl_map)
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
