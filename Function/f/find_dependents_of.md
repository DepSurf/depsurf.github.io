# Function: <code>find_dependents_of</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595004941,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:10",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595004941,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595168500,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:10",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595168500,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 38
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
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595411133,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:10",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595411133,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596330624,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:10",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596330624,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602648814,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602648814,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602818771,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602818771,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604613915,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604613915,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604709776,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604709776,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604722176,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604722176,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609068981,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609068981,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612132348,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612132348,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
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
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614272147,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:8",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
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
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615194454,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:8",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604648479,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604648479,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604616389,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604616389,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604726242,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604726242,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```

```json
{
  "name": "find_dependents_of",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604726288,
      "name": "find_dependents_of",
      "external": false,
      "loc": "arch/x86/kernel/pci-iommu_table.c:11",
      "file": "arch/x86/kernel/pci-iommu_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:check_iommu_entries",
        "arch/x86/kernel/pci-iommu_table.c:sort_iommu_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604726288,
      "name": "find_dependents_of",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 41
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
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
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct iommu_table_entry * find_dependents_of(struct iommu_table_entry * start, struct iommu_table_entry * finish, struct iommu_table_entry * q)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
