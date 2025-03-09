# Function: <code>grab_mapping_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581497831,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:410",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * grab_mapping_entry(struct address_space * mapping, long unsigned int index, long unsigned int size_flag)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580704,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:312",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580704,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
void * grab_mapping_entry(struct address_space * mapping, long unsigned int index, long unsigned int size_flag)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581641664,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:324",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581641664,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
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
void * grab_mapping_entry(struct address_space * mapping, long unsigned int index, long unsigned int size_flag)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787120,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:327",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787120,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
void * grab_mapping_entry(struct address_space * mapping, long unsigned int index, long unsigned int size_flag)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960704,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:500",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960704,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, long unsigned int size_flag)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582043248,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:470",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582043248,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582208768,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:475",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208768,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582289648,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:476",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289648,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573168,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:476",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573168,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582644672,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:476",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582644672,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582674864,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:487",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582674864,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002224,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:487",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002224,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583470272,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:487",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583470272,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062800,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:587",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062800,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289232,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:587",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289232,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584506032,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:573",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584506032,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493865684,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:476",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287494848,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:476",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287494848,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273430422,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:476",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582258384,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:476",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258384,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582195344,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:476",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582195344,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248864,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:476",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248864,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```

```json
{
  "name": "grab_mapping_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582321216,
      "name": "grab_mapping_entry",
      "external": false,
      "loc": "fs/dax.c:476",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582321216,
      "name": "grab_mapping_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void * grab_mapping_entry(struct address_space * mapping, long unsigned int index, long unsigned int size_flag)
```
</details>
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
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xa_state * xas</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, index, size_flag</code> ➡️ <code>xas, mapping, size_flag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int size_flag</code>
</li>
</ul>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * grab_mapping_entry(struct xa_state * xas, struct address_space * mapping, unsigned int order)
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
