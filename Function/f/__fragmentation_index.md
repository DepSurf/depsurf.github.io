# Function: <code>__fragmentation_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580601393,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:668",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580703841,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:869",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580769617,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:869",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580805777,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:869",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893280,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1053",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893280,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028896,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1053",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028896,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106432,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1053",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106432,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581171616,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171616,
      "name": "__fragmentation_index",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229616,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229616,
      "name": "__fragmentation_index",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416960,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416960,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581460064,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1076",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581460064,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480896,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1088",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480896,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1094",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735664,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071592192750,
      "name": "__fragmentation_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1100",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116960,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071593968652,
      "name": "__fragmentation_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1087",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582590576,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071596027548,
      "name": "__fragmentation_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582802898,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1088",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print"
      ],
      "caller_func": [
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582797936,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071596549945,
      "name": "__fragmentation_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582977490,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1091",
      "file": "mm/vmstat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print"
      ],
      "caller_func": [
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972560,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071597453610,
      "name": "__fragmentation_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492619856,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492619856,
      "name": "__fragmentation_index",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226475020,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226475020,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285938096,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285938096,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272645188,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272645188,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198464,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198464,
      "name": "__fragmentation_index",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145216,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145216,
      "name": "__fragmentation_index",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189664,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189664,
      "name": "__fragmentation_index",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```

```json
{
  "name": "__fragmentation_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252992,
      "name": "__fragmentation_index",
      "external": false,
      "loc": "mm/vmstat.c:1054",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:fragmentation_index"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252992,
      "name": "__fragmentation_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __fragmentation_index(unsigned int order, struct contig_page_info * info)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
