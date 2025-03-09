# Function: <code>dax_insert_pfn_mkwrite</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581784372,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1522",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581958324,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1745",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582050640,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1650",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582208164,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1666",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582289028,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1670",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault * vmf, pfn_t pfn, unsigned int order)
```

```json
{
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582576336,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1660",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582576336,
      "name": "dax_insert_pfn_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault * vmf, pfn_t pfn, unsigned int order)
```

```json
{
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582647696,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1675",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582647696,
      "name": "dax_insert_pfn_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault * vmf, pfn_t pfn, unsigned int order)
```

```json
{
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582674128,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1687",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582674128,
      "name": "dax_insert_pfn_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
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
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault * vmf, pfn_t pfn, unsigned int order)
```

```json
{
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1659",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001472,
      "name": "dax_insert_pfn_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446744071592239188,
      "name": "dax_insert_pfn_mkwrite.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault * vmf, pfn_t pfn, unsigned int order)
```

```json
{
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1619",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583471440,
      "name": "dax_insert_pfn_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
    },
    {
      "addr": 18446744071594017430,
      "name": "dax_insert_pfn_mkwrite.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault * vmf, pfn_t pfn, unsigned int order)
```

```json
{
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1903",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584064800,
      "name": "dax_insert_pfn_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
    },
    {
      "addr": 18446744071596057005,
      "name": "dax_insert_pfn_mkwrite.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault * vmf, pfn_t pfn, unsigned int order)
```

```json
{
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1945",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291216,
      "name": "dax_insert_pfn_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
    },
    {
      "addr": 18446744071596581266,
      "name": "dax_insert_pfn_mkwrite.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault * vmf, pfn_t pfn, unsigned int order)
```

```json
{
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1929",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_finish_sync_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584508016,
      "name": "dax_insert_pfn_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
    },
    {
      "addr": 18446744071597485111,
      "name": "dax_insert_pfn_mkwrite.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493863212,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1670",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287493912,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1670",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273429628,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1670",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582257764,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1670",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582194740,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1670",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582248244,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1670",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
  "name": "dax_insert_pfn_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582322966,
      "name": "dax_insert_pfn_mkwrite",
      "external": false,
      "loc": "fs/dax.c:1670",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_finish_sync_fault"
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
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault * vmf, pfn_t pfn, unsigned int order)
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
