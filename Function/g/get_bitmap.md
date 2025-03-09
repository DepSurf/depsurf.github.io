# Function: <code>get_bitmap</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int get_bitmap(long unsigned int * mask, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "get_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149344,
      "name": "get_bitmap",
      "external": false,
      "loc": "mm/mempolicy.c:1355",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:get_nodes",
        "mm/mempolicy.c:get_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149344,
      "name": "get_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_bitmap(long unsigned int * mask, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "get_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582605653,
      "name": "get_bitmap",
      "external": false,
      "loc": "mm/mempolicy.c:1348",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:get_nodes"
      ],
      "caller_func": [
        "mm/mempolicy.c:get_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601312,
      "name": "get_bitmap",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_bitmap(long unsigned int * mask, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "get_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583128533,
      "name": "get_bitmap",
      "external": false,
      "loc": "mm/mempolicy.c:1363",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:get_nodes"
      ],
      "caller_func": [
        "mm/mempolicy.c:get_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124096,
      "name": "get_bitmap",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_bitmap(long unsigned int * mask, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "get_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583338549,
      "name": "get_bitmap",
      "external": false,
      "loc": "mm/mempolicy.c:1380",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:get_nodes"
      ],
      "caller_func": [
        "mm/mempolicy.c:get_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334464,
      "name": "get_bitmap",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int get_bitmap(long unsigned int * mask, const long unsigned int * nmask, long unsigned int maxnode)
```

```json
{
  "name": "get_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583574533,
      "name": "get_bitmap",
      "external": false,
      "loc": "mm/mempolicy.c:1364",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:get_nodes"
      ],
      "caller_func": [
        "mm/mempolicy.c:get_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570496,
      "name": "get_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int get_bitmap(long unsigned int * mask, const long unsigned int * nmask, long unsigned int maxnode)
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
