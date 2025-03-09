# Function: <code>interval_subtree_search</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct memtype * interval_subtree_search(struct memtype * node, u64 start, u64 last)
```

```json
{
  "name": "interval_subtree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437904,
      "name": "interval_subtree_search",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:46",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element",
        "arch/x86/mm/pat/memtype_interval.c:memtype_lookup",
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_conflict",
        "arch/x86/mm/pat/memtype_interval.c:memtype_match",
        "arch/x86/mm/pat/memtype_interval.c:interval_iter_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437904,
      "name": "interval_subtree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct memtype * interval_subtree_search(struct memtype * node, u64 start, u64 last)
```

```json
{
  "name": "interval_subtree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436304,
      "name": "interval_subtree_search",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:46",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element",
        "arch/x86/mm/pat/memtype_interval.c:memtype_lookup",
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_conflict",
        "arch/x86/mm/pat/memtype_interval.c:memtype_match",
        "arch/x86/mm/pat/memtype_interval.c:interval_iter_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436304,
      "name": "interval_subtree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct memtype * interval_subtree_search(struct memtype * node, u64 start, u64 last)
```

```json
{
  "name": "interval_subtree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579439232,
      "name": "interval_subtree_search",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:46",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element",
        "arch/x86/mm/pat/memtype_interval.c:memtype_lookup",
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert",
        "arch/x86/mm/pat/memtype_interval.c:memtype_match",
        "arch/x86/mm/pat/memtype_interval.c:interval_iter_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439232,
      "name": "interval_subtree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct memtype * interval_subtree_search(struct memtype * node, u64 start, u64 last)
```

```json
{
  "name": "interval_subtree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503616,
      "name": "interval_subtree_search",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:46",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element",
        "arch/x86/mm/pat/memtype_interval.c:memtype_lookup",
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert",
        "arch/x86/mm/pat/memtype_interval.c:memtype_match",
        "arch/x86/mm/pat/memtype_interval.c:interval_iter_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503616,
      "name": "interval_subtree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct memtype * interval_subtree_search(struct memtype * node, u64 start, u64 last)
```

```json
{
  "name": "interval_subtree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585568,
      "name": "interval_subtree_search",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:46",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element",
        "arch/x86/mm/pat/memtype_interval.c:memtype_lookup",
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert",
        "arch/x86/mm/pat/memtype_interval.c:memtype_match",
        "arch/x86/mm/pat/memtype_interval.c:interval_iter_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585568,
      "name": "interval_subtree_search",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct memtype * interval_subtree_search(struct memtype * node, u64 start, u64 last)
```

```json
{
  "name": "interval_subtree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579695664,
      "name": "interval_subtree_search",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:46",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element",
        "arch/x86/mm/pat/memtype_interval.c:memtype_lookup",
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert",
        "arch/x86/mm/pat/memtype_interval.c:memtype_match",
        "arch/x86/mm/pat/memtype_interval.c:interval_iter_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695664,
      "name": "interval_subtree_search",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct memtype * interval_subtree_search(struct memtype * node, u64 start, u64 last)
```

```json
{
  "name": "interval_subtree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579709552,
      "name": "interval_subtree_search",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:46",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element",
        "arch/x86/mm/pat/memtype_interval.c:memtype_lookup",
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert",
        "arch/x86/mm/pat/memtype_interval.c:memtype_match",
        "arch/x86/mm/pat/memtype_interval.c:interval_iter_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709552,
      "name": "interval_subtree_search",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct memtype * interval_subtree_search(struct memtype * node, u64 start, u64 last)
```

```json
{
  "name": "interval_subtree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579744256,
      "name": "interval_subtree_search",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype_interval.c:46",
      "file": "arch/x86/mm/pat/memtype_interval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element",
        "arch/x86/mm/pat/memtype_interval.c:memtype_lookup",
        "arch/x86/mm/pat/memtype_interval.c:memtype_check_insert",
        "arch/x86/mm/pat/memtype_interval.c:memtype_match",
        "arch/x86/mm/pat/memtype_interval.c:interval_iter_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579744256,
      "name": "interval_subtree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct memtype * interval_subtree_search(struct memtype * node, u64 start, u64 last)
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
