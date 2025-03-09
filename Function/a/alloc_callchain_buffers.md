# Function: <code>alloc_callchain_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580442832,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:59",
      "file": "kernel/events/callchain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
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
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580517278,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:69",
      "file": "kernel/events/callchain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
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
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580581246,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:69",
      "file": "kernel/events/callchain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
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
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580611858,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:71",
      "file": "kernel/events/callchain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580692674,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:71",
      "file": "kernel/events/callchain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580824654,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:71",
      "file": "kernel/events/callchain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580891406,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:71",
      "file": "kernel/events/callchain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988752,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988752,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042736,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042736,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222256,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222256,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264704,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264704,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283408,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283408,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581527408,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581527408,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875328,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875328,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303088,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303088,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503872,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503872,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582672416,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582672416,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492398172,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226283632,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285659792,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285659792,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272506062,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011584,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011584,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580957712,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580957712,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002784,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002784,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int alloc_callchain_buffers()
```

```json
{
  "name": "alloc_callchain_buffers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063984,
      "name": "alloc_callchain_buffers",
      "external": false,
      "loc": "kernel/events/callchain.c:70",
      "file": "kernel/events/callchain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063984,
      "name": "alloc_callchain_buffers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int alloc_callchain_buffers()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int alloc_callchain_buffers()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int alloc_callchain_buffers()
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
int alloc_callchain_buffers()
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
