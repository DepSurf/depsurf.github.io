# Function: <code>__xsk_map_flush</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726192,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:141",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726192,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806336,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:142",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806336,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580894752,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:140",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894752,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580947904,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:192",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947904,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __xsk_map_flush()
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591068032,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "net/xdp/xsk.c:241",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068032,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void __xsk_map_flush()
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591132848,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "net/xdp/xsk.c:285",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591132848,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void __xsk_map_flush()
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591063696,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "net/xdp/xsk.c:300",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591063696,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void __xsk_map_flush()
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591906576,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "net/xdp/xsk.c:300",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591906576,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void __xsk_map_flush()
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593627104,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "net/xdp/xsk.c:285",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593627104,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void __xsk_map_flush()
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595557008,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "net/xdp/xsk.c:285",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595557008,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void __xsk_map_flush()
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596065328,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "net/xdp/xsk.c:286",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596065328,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void __xsk_map_flush()
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596933136,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "net/xdp/xsk.c:388",
      "file": "net/xdp/xsk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596933136,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492291432,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:192",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492291432,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226177316,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:192",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226177316,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285525504,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:192",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285525504,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272423242,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:192",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272423242,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916704,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:192",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916704,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862768,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:192",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862768,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907952,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:192",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907952,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __xsk_map_flush(struct bpf_map * map)
```

```json
{
  "name": "__xsk_map_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580966704,
      "name": "__xsk_map_flush",
      "external": true,
      "loc": "kernel/bpf/xskmap.c:192",
      "file": "kernel/bpf/xskmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:xdp_do_flush_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966704,
      "name": "__xsk_map_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __xsk_map_flush(struct bpf_map * map)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct bpf_map * map</code>
</li>
</ul>
</details>
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
