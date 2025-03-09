# Function: <code>shmem_radix_tree_replace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int shmem_radix_tree_replace(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_radix_tree_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580581248,
      "name": "shmem_radix_tree_replace",
      "external": false,
      "loc": "mm/shmem.c:259",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_add_to_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581248,
      "name": "shmem_radix_tree_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int shmem_radix_tree_replace(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_radix_tree_replace",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580672512,
      "name": "shmem_radix_tree_replace",
      "external": false,
      "loc": "mm/shmem.c:304",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672512,
      "name": "shmem_radix_tree_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int shmem_radix_tree_replace(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_radix_tree_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580734752,
      "name": "shmem_radix_tree_replace",
      "external": false,
      "loc": "mm/shmem.c:300",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580734752,
      "name": "shmem_radix_tree_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int shmem_radix_tree_replace(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_radix_tree_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771392,
      "name": "shmem_radix_tree_replace",
      "external": false,
      "loc": "mm/shmem.c:316",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771392,
      "name": "shmem_radix_tree_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int shmem_radix_tree_replace(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_radix_tree_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858720,
      "name": "shmem_radix_tree_replace",
      "external": false,
      "loc": "mm/shmem.c:330",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858720,
      "name": "shmem_radix_tree_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int shmem_radix_tree_replace(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_radix_tree_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995824,
      "name": "shmem_radix_tree_replace",
      "external": false,
      "loc": "mm/shmem.c:330",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_add_to_page_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995824,
      "name": "shmem_radix_tree_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
int shmem_radix_tree_replace(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```
</details>
</li>
</ul>
