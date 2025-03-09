# Function: <code>calc_checksum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580834238,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:829",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
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
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580960550,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:817",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028688,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:828",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028688,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074704,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:985",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074704,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581185872,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:985",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185872,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330656,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1008",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330656,
      "name": "calc_checksum",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414672,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1009",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414672,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581527312,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581527312,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581592192,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592192,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581806864,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806864,
      "name": "calc_checksum",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581854400,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1024",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581854400,
      "name": "calc_checksum",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885088,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1022",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885088,
      "name": "calc_checksum",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180672,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1018",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180672,
      "name": "calc_checksum",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582639152,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1031",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639152,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583161168,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1035",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583161168,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583376816,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1079",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376816,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621958920,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1269",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493032088,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493032088,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226748672,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_do_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226748672,
      "name": "calc_checksum",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286463568,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286463568,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272905714,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_do_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272905714,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581560928,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560928,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502576,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502576,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581552240,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552240,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
u32 calc_checksum(struct page * page)
```

```json
{
  "name": "calc_checksum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581617376,
      "name": "calc_checksum",
      "external": false,
      "loc": "mm/ksm.c:1023",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581617376,
      "name": "calc_checksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
u32 calc_checksum(struct page * page)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
u32 calc_checksum(struct page * page)
```
</details>
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
