# Function: <code>bpf_clear_redirect_map</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588147408,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3453",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588147408,
      "name": "bpf_clear_redirect_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588466656,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3586",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588466656,
      "name": "bpf_clear_redirect_map",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588672224,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3592",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588672224,
      "name": "bpf_clear_redirect_map",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589537520,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3556",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589537520,
      "name": "bpf_clear_redirect_map",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546688,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3963",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "net/xdp/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546688,
      "name": "bpf_clear_redirect_map",
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590179344,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3922",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590179344,
      "name": "bpf_clear_redirect_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591741776,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:4142",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591741776,
      "name": "bpf_clear_redirect_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593531232,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:4156",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593531232,
      "name": "bpf_clear_redirect_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593998896,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:4210",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593998896,
      "name": "bpf_clear_redirect_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594783216,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:4289",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594783216,
      "name": "bpf_clear_redirect_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502224880,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3592",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502224880,
      "name": "bpf_clear_redirect_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234970764,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3592",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234970764,
      "name": "bpf_clear_redirect_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295712480,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3592",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295712480,
      "name": "bpf_clear_redirect_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278469510,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3592",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278469510,
      "name": "bpf_clear_redirect_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588278960,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3592",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588278960,
      "name": "bpf_clear_redirect_map",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587991776,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3592",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587991776,
      "name": "bpf_clear_redirect_map",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588610784,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3592",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588610784,
      "name": "bpf_clear_redirect_map",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```

```json
{
  "name": "bpf_clear_redirect_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588748464,
      "name": "bpf_clear_redirect_map",
      "external": true,
      "loc": "net/core/filter.c:3592",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/xskmap.c:xsk_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748464,
      "name": "bpf_clear_redirect_map",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void bpf_clear_redirect_map(struct bpf_map * map)
```
</details>
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
