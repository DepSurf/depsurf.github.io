# Function: <code>lo_rw_aio_do_completion</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585594784,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:466",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585594784,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585838528,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:488",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585838528,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585971504,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:489",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585971504,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586214704,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:489",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214704,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586362752,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:491",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586362752,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587132736,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:504",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587132736,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587217776,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:501",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587217776,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587107360,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:543",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107360,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587683273,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:533",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587679024,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589025344,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:374",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589025344,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590551488,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:374",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590551488,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590879728,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:374",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590879728,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591223632,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:370",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591223632,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499208728,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:491",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499208728,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231739724,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:491",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231739724,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292413488,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:491",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292413488,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276497618,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:491",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276497618,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586124640,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:491",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586124640,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585969248,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:491",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585969248,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586310720,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:491",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586310720,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```

```json
{
  "name": "lo_rw_aio_do_completion",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586422384,
      "name": "lo_rw_aio_do_completion",
      "external": false,
      "loc": "drivers/block/loop.c:491",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_rw_aio",
        "drivers/block/loop.c:lo_rw_aio_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422384,
      "name": "lo_rw_aio_do_completion",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void lo_rw_aio_do_completion(struct loop_cmd * cmd)
```
</details>
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
