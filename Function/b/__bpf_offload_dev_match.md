# Function: <code>__bpf_offload_dev_match</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580807728,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:510",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807728,
      "name": "__bpf_offload_dev_match.isra.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580896240,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580896240,
      "name": "__bpf_offload_dev_match.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580949504,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949504,
      "name": "__bpf_offload_dev_match.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110384,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110384,
      "name": "__bpf_offload_dev_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141776,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141776,
      "name": "__bpf_offload_dev_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581158592,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158592,
      "name": "__bpf_offload_dev_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581396478,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396432,
      "name": "__bpf_offload_dev_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071592187489,
      "name": "__bpf_offload_dev_match.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581720094,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581720048,
      "name": "__bpf_offload_dev_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071593962117,
      "name": "__bpf_offload_dev_match.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582126974,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:543",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126928,
      "name": "__bpf_offload_dev_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071596022554,
      "name": "__bpf_offload_dev_match.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582322654,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:684",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322608,
      "name": "__bpf_offload_dev_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071596544390,
      "name": "__bpf_offload_dev_match.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582483518,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:694",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483472,
      "name": "__bpf_offload_dev_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071597447653,
      "name": "__bpf_offload_dev_match.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492296032,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492296032,
      "name": "__bpf_offload_dev_match.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226178996,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226178996,
      "name": "__bpf_offload_dev_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285531280,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285531280,
      "name": "__bpf_offload_dev_match.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272426868,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272426868,
      "name": "__bpf_offload_dev_match.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580918304,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918304,
      "name": "__bpf_offload_dev_match.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580864368,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864368,
      "name": "__bpf_offload_dev_match.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580909552,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909552,
      "name": "__bpf_offload_dev_match.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_offload_dev_match",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580969376,
      "name": "__bpf_offload_dev_match",
      "external": false,
      "loc": "kernel/bpf/offload.c:546",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_prog_map_match",
        "kernel/bpf/offload.c:bpf_offload_dev_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969376,
      "name": "__bpf_offload_dev_match.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 762
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog * prog, struct net_device * netdev)
```
</details>
</li>
</ul>
