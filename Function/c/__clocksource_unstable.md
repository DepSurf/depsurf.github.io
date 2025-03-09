# Function: <code>__clocksource_unstable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579861730,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:139",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
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
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579891026,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:139",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
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
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579902914,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:140",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579911408,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:140",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911408,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579956592,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:140",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956592,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580004176,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:159",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004176,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050832,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:145",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050832,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580094400,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:145",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094400,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580143360,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:145",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143360,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204000,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:145",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204000,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580188736,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:145",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188736,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580192560,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:152",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192560,
      "name": "__clocksource_unstable",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580339184,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:160",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580339184,
      "name": "__clocksource_unstable",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580552128,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:166",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580552128,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580810192,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:166",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810192,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580893392,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:169",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893392,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580983824,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:171",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983824,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112560,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:145",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112560,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580057872,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:145",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057872,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103632,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:145",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103632,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __clocksource_unstable(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_unstable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580155376,
      "name": "__clocksource_unstable",
      "external": false,
      "loc": "kernel/time/clocksource.c:145",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_mark_unstable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155376,
      "name": "__clocksource_unstable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __clocksource_unstable(struct clocksource * cs)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __clocksource_unstable(struct clocksource * cs)
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
