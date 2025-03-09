# Function: <code>dax_load_hole</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581328039,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:256",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:__dax_fault"
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581498834,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:561",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault"
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581582099,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:542",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581644159,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:861",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581790195,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:873",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581964649,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1120",
      "file": "fs/dax.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582046673,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1024",
      "file": "fs/dax.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582210849,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1029",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582291745,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1030",
      "file": "fs/dax.c",
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
vm_fault_t dax_load_hole(struct xa_state * xas, struct address_space * mapping, void * * entry, struct vm_fault * vmf)
```

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582570304,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1024",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570304,
      "name": "dax_load_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
vm_fault_t dax_load_hole(struct xa_state * xas, struct address_space * mapping, void * * entry, struct vm_fault * vmf)
```

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641872,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1040",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641872,
      "name": "dax_load_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582676840,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1052",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583000823,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1052",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_iter"
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583469906,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:969",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_iter"
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584062183,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1173",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_iter"
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584288631,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1200",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_iter"
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584505431,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1186",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_iter"
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493867320,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1030",
      "file": "fs/dax.c",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287497556,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1030",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273431798,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1030",
      "file": "fs/dax.c",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582260481,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1030",
      "file": "fs/dax.c",
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582197423,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1030",
      "file": "fs/dax.c",
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582250961,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1030",
      "file": "fs/dax.c",
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
  "name": "dax_load_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582331293,
      "name": "dax_load_hole",
      "external": false,
      "loc": "fs/dax.c:1030",
      "file": "fs/dax.c",
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
vm_fault_t dax_load_hole(struct xa_state * xas, struct address_space * mapping, void * * entry, struct vm_fault * vmf)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
vm_fault_t dax_load_hole(struct xa_state * xas, struct address_space * mapping, void * * entry, struct vm_fault * vmf)
```
</details>
</li>
</ul>
