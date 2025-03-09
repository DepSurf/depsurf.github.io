# Function: <code>pcpu_chunk_populated</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580619970,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:770",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_balance_workfn"
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
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580724505,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:765",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
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
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580790329,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:765",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822320,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:756",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822320,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end, bool for_alloc)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580910016,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1229",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910016,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end, bool for_alloc)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045872,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1226",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045872,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end, bool for_alloc)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123536,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1235",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123536,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188464,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1472",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188464,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246912,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1472",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246912,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435936,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1444",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435936,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581479056,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1481",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479056,
      "name": "pcpu_chunk_populated",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504096,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1482",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504096,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1523",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765200,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071592194007,
      "name": "pcpu_chunk_populated.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1523",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149360,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071593970572,
      "name": "pcpu_chunk_populated.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1520",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582627712,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071596027948,
      "name": "pcpu_chunk_populated.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1520",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836576,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071596550345,
      "name": "pcpu_chunk_populated.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1520",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_populated",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011520,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071597454010,
      "name": "pcpu_chunk_populated.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492647200,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1472",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492647200,
      "name": "pcpu_chunk_populated",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226487580,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1472",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226487580,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285963552,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1472",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285963552,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272661730,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1472",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272661730,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215760,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1472",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215760,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162464,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1472",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162464,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581206960,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1472",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206960,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```

```json
{
  "name": "pcpu_chunk_populated",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581270320,
      "name": "pcpu_chunk_populated",
      "external": false,
      "loc": "mm/percpu.c:1472",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270320,
      "name": "pcpu_chunk_populated",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void pcpu_chunk_populated(struct pcpu_chunk * chunk, int page_start, int page_end)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool for_alloc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool for_alloc</code>
</li>
</ul>
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
