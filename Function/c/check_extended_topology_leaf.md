# Function: <code>check_extended_topology_leaf</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129024,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129024,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579130896,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579130896,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579147163,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146800,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579144219,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143856,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579150571,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579150208,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579179019,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178656,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579225248,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225248,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579283504,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283504,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290016,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290016,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579319785,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
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
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579131280,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579131280,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579062625,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579130832,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579130832,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int check_extended_topology_leaf(int leaf)
```

```json
{
  "name": "check_extended_topology_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579135952,
      "name": "check_extended_topology_leaf",
      "external": false,
      "loc": "arch/x86/kernel/cpu/topology.c:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135952,
      "name": "check_extended_topology_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int check_extended_topology_leaf(int leaf)
```
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int check_extended_topology_leaf(int leaf)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int check_extended_topology_leaf(int leaf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int check_extended_topology_leaf(int leaf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int check_extended_topology_leaf(int leaf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int check_extended_topology_leaf(int leaf)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int check_extended_topology_leaf(int leaf)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
