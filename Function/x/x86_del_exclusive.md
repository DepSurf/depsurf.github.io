# Function: <code>x86_del_exclusive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578869877,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:380",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy"
      ],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870096,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870565,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:388",
      "file": "arch/x86/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy"
      ],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868384,
      "name": "x86_del_exclusive.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071578870624,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578870592,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:393",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870592,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578869984,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:394",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578869984,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578870880,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:394",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870880,
      "name": "x86_del_exclusive",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872784,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:398",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578872784,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578872592,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:398",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578872592,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873120,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:398",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873120,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873248,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:399",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873248,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578877440,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:400",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578877440,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873520,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:432",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873520,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578875344,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:458",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578875344,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:458",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592038602,
      "name": "x86_del_exclusive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578877552,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:460",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593804723,
      "name": "x86_del_exclusive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578874832,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:463",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595950756,
      "name": "x86_del_exclusive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578881104,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:463",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596468009,
      "name": "x86_del_exclusive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578879104,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:461",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597363045,
      "name": "x86_del_exclusive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578901408,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873248,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:399",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873248,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578866880,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:399",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866880,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873184,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:399",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873184,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void x86_del_exclusive(unsigned int what)
```

```json
{
  "name": "x86_del_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873536,
      "name": "x86_del_exclusive",
      "external": true,
      "loc": "arch/x86/events/core.c:399",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:hw_perf_lbr_event_destroy",
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/bts.c:bts_event_destroy",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873536,
      "name": "x86_del_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void x86_del_exclusive(unsigned int what)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void x86_del_exclusive(unsigned int what)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void x86_del_exclusive(unsigned int what)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void x86_del_exclusive(unsigned int what)
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
