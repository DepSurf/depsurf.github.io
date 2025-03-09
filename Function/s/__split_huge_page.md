# Function: <code>__split_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580905746,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:1900",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
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
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581039589,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:1818",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
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
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581114787,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:1949",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
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
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581162873,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2269",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
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
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581289182,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2421",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
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
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581436145,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2413",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
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
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581519784,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2436",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581606736,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2494",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606736,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677312,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2499",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677312,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896912,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2409",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896912,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 949
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581943104,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2457",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581943104,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1007
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969088,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2468",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969088,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271744,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2405",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271744,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753888,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2436",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753888,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1940
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583287936,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2521",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583287936,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1568
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583506672,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2514",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583506672,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1526
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583703680,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2850",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703680,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1843
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493123600,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2499",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493123600,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1296
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286601584,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2499",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286601584,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1916
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581646048,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2499",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646048,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581587536,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2499",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587536,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581637360,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2499",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581637360,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
```

```json
{
  "name": "__split_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581703536,
      "name": "__split_huge_page",
      "external": false,
      "loc": "mm/huge_memory.c:2499",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581703536,
      "name": "__split_huge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1166
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
</ul>
</details>
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
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
void __split_huge_page(struct page * page, struct list_head * list, long unsigned int end, long unsigned int flags)
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
