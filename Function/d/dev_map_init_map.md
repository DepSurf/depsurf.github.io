# Function: <code>dev_map_init_map</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580940826,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100256,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:109",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100256,
      "name": "dev_map_init_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581128301,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:109",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581149045,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:109",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581382480,
      "name": "dev_map_init_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071592187365,
      "name": "dev_map_init_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:111",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705536,
      "name": "dev_map_init_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071593961993,
      "name": "dev_map_init_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:111",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112000,
      "name": "dev_map_init_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071596022442,
      "name": "dev_map_init_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:111",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308096,
      "name": "dev_map_init_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071596544318,
      "name": "dev_map_init_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469152,
      "name": "dev_map_init_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071597447581,
      "name": "dev_map_init_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492279960,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492279960,
      "name": "dev_map_init_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226169140,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226169140,
      "name": "dev_map_init_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285513904,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272416072,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272416072,
      "name": "dev_map_init_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580909626,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580855690,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580900874,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_map_init_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580959594,
      "name": "dev_map_init_map",
      "external": false,
      "loc": "kernel/bpf/devmap.c:110",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int dev_map_init_map(struct bpf_dtab * dtab, union bpf_attr * attr)
```
</details>
</li>
</ul>
