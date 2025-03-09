# Function: <code>memory_failure_hugetlb</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581226333,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1048",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581357231,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1048",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581505970,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1081",
      "file": "mm/memory-failure.c",
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
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581591568,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1083",
      "file": "mm/memory-failure.c",
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
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581703551,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1080",
      "file": "mm/memory-failure.c",
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
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581778451,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1084",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int memory_failure_hugetlb(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1107",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995920,
      "name": "memory_failure_hugetlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    },
    {
      "addr": 18446744071582002541,
      "name": "memory_failure_hugetlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int memory_failure_hugetlb(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1217",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045168,
      "name": "memory_failure_hugetlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071591338225,
      "name": "memory_failure_hugetlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int memory_failure_hugetlb(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1277",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074176,
      "name": "memory_failure_hugetlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
    },
    {
      "addr": 18446744071591281043,
      "name": "memory_failure_hugetlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
int memory_failure_hugetlb(long unsigned int pfn, int flags)
```

```json
{
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1419",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385840,
      "name": "memory_failure_hugetlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071592227265,
      "name": "memory_failure_hugetlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493233764,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1084",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286756672,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1084",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581747187,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1084",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581685811,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1084",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581738499,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1084",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
  "name": "memory_failure_hugetlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581806749,
      "name": "memory_failure_hugetlb",
      "external": false,
      "loc": "mm/memory-failure.c:1084",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int memory_failure_hugetlb(long unsigned int pfn, int flags)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int memory_failure_hugetlb(long unsigned int pfn, int flags)
```
</details>
</li>
</ul>
