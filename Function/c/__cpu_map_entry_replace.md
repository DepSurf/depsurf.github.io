# Function: <code>__cpu_map_entry_replace</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __cpu_map_entry_replace(struct bpf_cpu_map * cmap, u32 key_cpu, struct bpf_cpu_map_entry * rcpu)
```

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580614832,
      "name": "__cpu_map_entry_replace",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:441",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614832,
      "name": "__cpu_map_entry_replace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580722080,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:404",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722080,
      "name": "__cpu_map_entry_replace.isra.10",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580802240,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:404",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802240,
      "name": "__cpu_map_entry_replace.isra.11",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580890000,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:442",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890000,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580942640,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:442",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942640,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581108035,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:410",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105664,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581136403,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:509",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581133664,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581156419,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:467",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153616,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581391651,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:528",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390352,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581717484,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:531",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714320,
      "name": "__cpu_map_entry_replace.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124140,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:530",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120848,
      "name": "__cpu_map_entry_replace.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582320412,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:541",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317488,
      "name": "__cpu_map_entry_replace.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582478723,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:498",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492284512,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:442",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492284512,
      "name": "__cpu_map_entry_replace.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void __cpu_map_entry_replace(struct bpf_cpu_map * cmap, u32 key_cpu, struct bpf_cpu_map_entry * rcpu)
```

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226172352,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:442",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226172352,
      "name": "__cpu_map_entry_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285517760,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:442",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285517760,
      "name": "__cpu_map_entry_replace.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272418158,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:442",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272418158,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580911440,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:442",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580911440,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580857504,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:442",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857504,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580902688,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:442",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902688,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580961440,
      "name": "__cpu_map_entry_replace",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:442",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961440,
      "name": "__cpu_map_entry_replace.isra.0",
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void __cpu_map_entry_replace(struct bpf_cpu_map * cmap, u32 key_cpu, struct bpf_cpu_map_entry * rcpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void __cpu_map_entry_replace(struct bpf_cpu_map * cmap, u32 key_cpu, struct bpf_cpu_map_entry * rcpu)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __cpu_map_entry_replace(struct bpf_cpu_map * cmap, u32 key_cpu, struct bpf_cpu_map_entry * rcpu)
```
</details>
</li>
</ul>
