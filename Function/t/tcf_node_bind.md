# Function: <code>tcf_node_bind</code>

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
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587745440,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1650",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587745440,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588084288,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1788",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588084288,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588263696,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1885",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263696,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588652758,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1898",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652720,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071588663064,
      "name": "tcf_node_bind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588875088,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1899",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588875088,
      "name": "tcf_node_bind",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589758592,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1909",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589758592,
      "name": "tcf_node_bind",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589793168,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1910",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589793168,
      "name": "tcf_node_bind",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589697248,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1911",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589697248,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1912",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590455184,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    },
    {
      "addr": 18446744071592709950,
      "name": "tcf_node_bind.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1903",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592061648,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071594596340,
      "name": "tcf_node_bind.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593881466,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1921",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593881408,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071596332740,
      "name": "tcf_node_bind.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594251898,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1995",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594251840,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071596861525,
      "name": "tcf_node_bind.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595049258,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:2052",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595049200,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071597786611,
      "name": "tcf_node_bind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502464568,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1899",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502464568,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235179328,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1899",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235179328,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296018432,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1899",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296018432,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278648268,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1899",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278648268,
      "name": "tcf_node_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588481472,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1899",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588481472,
      "name": "tcf_node_bind",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588193472,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1899",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588193472,
      "name": "tcf_node_bind",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588813648,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1899",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588813648,
      "name": "tcf_node_bind",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
```

```json
{
  "name": "tcf_node_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588954288,
      "name": "tcf_node_bind",
      "external": false,
      "loc": "net/sched/sch_api.c:1899",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588954288,
      "name": "tcf_node_bind",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int tcf_node_bind(struct tcf_proto * tp, void * n, struct tcf_walker * arg)
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
