# Function: <code>return_unused_surplus_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580791568,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1730",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791568,
      "name": "return_unused_surplus_pages.part.43",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915725,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1758",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915040,
      "name": "return_unused_surplus_pages.part.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981168,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1789",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981168,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028416,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1769",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028416,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581138224,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1775",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581138224,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278608,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1791",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278608,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581364880,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1791",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364880,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581472528,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1834",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472528,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581536784,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1914",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581536784,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581748528,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2160",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748528,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797024,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2110",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797024,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581823792,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2052",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823792,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112560,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2312",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112560,
      "name": "return_unused_surplus_pages",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551920,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2424",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551920,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073968,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2609",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073968,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583282608,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2638",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282608,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583514992,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2736",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_reserve_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583514992,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492972200,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1914",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492972200,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286387520,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1914",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286387520,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272881104,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1914",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272881104,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505520,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1914",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505520,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581447824,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1914",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581447824,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581496832,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1914",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496832,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```

```json
{
  "name": "return_unused_surplus_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564224,
      "name": "return_unused_surplus_pages",
      "external": false,
      "loc": "mm/hugetlb.c:1914",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:hugetlb_acct_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564224,
      "name": "return_unused_surplus_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void return_unused_surplus_pages(struct hstate * h, long unsigned int unused_resv_pages)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
