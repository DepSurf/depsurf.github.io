# Function: <code>__apply_to_page_range</code>

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
int __apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data, bool create)
```

```json
{
  "name": "__apply_to_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546176,
      "name": "__apply_to_page_range",
      "external": false,
      "loc": "mm/memory.c:2331",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_existing_page_range",
        "mm/memory.c:apply_to_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546176,
      "name": "__apply_to_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
int __apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data, bool create)
```

```json
{
  "name": "__apply_to_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588240,
      "name": "__apply_to_page_range",
      "external": false,
      "loc": "mm/memory.c:2510",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_existing_page_range",
        "mm/memory.c:apply_to_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588240,
      "name": "__apply_to_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1592
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
int __apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data, bool create)
```

```json
{
  "name": "__apply_to_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581611424,
      "name": "__apply_to_page_range",
      "external": false,
      "loc": "mm/memory.c:2563",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_existing_page_range",
        "mm/memory.c:apply_to_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611424,
      "name": "__apply_to_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data, bool create)
```

```json
{
  "name": "__apply_to_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__apply_to_page_range",
      "external": false,
      "loc": "mm/memory.c:2658",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_existing_page_range",
        "mm/memory.c:apply_to_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878352,
      "name": "__apply_to_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
    },
    {
      "addr": 18446744071592199422,
      "name": "__apply_to_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int __apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data, bool create)
```

```json
{
  "name": "__apply_to_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__apply_to_page_range",
      "external": false,
      "loc": "mm/memory.c:2751",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_existing_page_range",
        "mm/memory.c:apply_to_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582277968,
      "name": "__apply_to_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    },
    {
      "addr": 18446744071593975890,
      "name": "__apply_to_page_range.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data, bool create)
```

```json
{
  "name": "__apply_to_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__apply_to_page_range",
      "external": false,
      "loc": "mm/memory.c:2722",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_existing_page_range",
        "mm/memory.c:apply_to_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582770464,
      "name": "__apply_to_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
    },
    {
      "addr": 18446744071596032084,
      "name": "__apply_to_page_range.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data, bool create)
```

```json
{
  "name": "__apply_to_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__apply_to_page_range",
      "external": false,
      "loc": "mm/memory.c:2722",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_existing_page_range",
        "mm/memory.c:apply_to_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986624,
      "name": "__apply_to_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071596554048,
      "name": "__apply_to_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int __apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data, bool create)
```

```json
{
  "name": "__apply_to_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__apply_to_page_range",
      "external": false,
      "loc": "mm/memory.c:2745",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_existing_page_range",
        "mm/memory.c:apply_to_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583161968,
      "name": "__apply_to_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071597457801,
      "name": "__apply_to_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int __apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data, bool create)
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
