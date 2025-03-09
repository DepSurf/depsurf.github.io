# Function: <code>replace_slot</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583372816,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:1001",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:radix_tree_replace_slot",
        "lib/radix-tree.c:__radix_tree_replace",
        "lib/radix-tree.c:__radix_tree_replace",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372816,
      "name": "replace_slot.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void replace_slot(void * * slot, void * item, struct radix_tree_node * node, int count, int exceptional)
```

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588217712,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:1123",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace",
        "lib/radix-tree.c:__radix_tree_replace",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588217712,
      "name": "replace_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void replace_slot(void * * slot, void * item, struct radix_tree_node * node, int count, int exceptional)
```

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588767680,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:1122",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace",
        "lib/radix-tree.c:__radix_tree_replace",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767680,
      "name": "replace_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void replace_slot(void * * slot, void * item, struct radix_tree_node * node, int count, int exceptional)
```

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589145920,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:1123",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace",
        "lib/radix-tree.c:__radix_tree_replace",
        "lib/radix-tree.c:__radix_tree_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589145920,
      "name": "replace_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589384408,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:845",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589841425,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:832",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590067521,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:832",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585063499,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:824",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_replace_slot"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585212795,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:824",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_replace_slot"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585095427,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:824",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_replace_slot"
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
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585543171,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:824",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_replace_slot"
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
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586698385,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:824",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_replace_slot"
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
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595861857,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:824",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_replace_slot"
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
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596379089,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:823",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_replace_slot"
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
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597274337,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:823",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:radix_tree_replace_slot"
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
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503844916,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:832",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236464436,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:832",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297698496,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:832",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279735464,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:832",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589669777,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:832",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589395601,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:832",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590113153,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:832",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_slot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590163537,
      "name": "replace_slot",
      "external": false,
      "loc": "lib/radix-tree.c:832",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:__radix_tree_delete",
        "lib/radix-tree.c:__radix_tree_replace"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void replace_slot(void * * slot, void * item, struct radix_tree_node * node, int count, int exceptional)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void replace_slot(void * * slot, void * item, struct radix_tree_node * node, int count, int exceptional)
```
</details>
</li>
</ul>
