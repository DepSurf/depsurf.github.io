# Function: <code>__bpf_map_offload_destroy</code>

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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726704,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:336",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_notification",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726704,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580807024,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:375",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807024,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895456,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071580901206,
      "name": "__bpf_map_offload_destroy.cold",
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580948704,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948704,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581109440,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109440,
      "name": "__bpf_map_offload_destroy",
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140992,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140992,
      "name": "__bpf_map_offload_destroy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157808,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157808,
      "name": "__bpf_map_offload_destroy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581398416,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581722825,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582128997,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:408",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582328840,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:135",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_map_offload_map_free",
        "kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582489832,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:136",
      "file": "kernel/bpf/offload.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_map_offload_map_free",
        "kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492292752,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492292752,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226178280,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226178280,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285527040,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285527040,
      "name": "__bpf_map_offload_destroy",
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272424148,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272424148,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917504,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917504,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580863568,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580863568,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908752,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908752,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```

```json
{
  "name": "__bpf_map_offload_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580967504,
      "name": "__bpf_map_offload_destroy",
      "external": false,
      "loc": "kernel/bpf/offload.c:411",
      "file": "kernel/bpf/offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_map_offload_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967504,
      "name": "__bpf_map_offload_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map * offmap)
```
</details>
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
