# Function: <code>get_hwpoison_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580948112,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:881",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948112,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581097824,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:873",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097824,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581173056,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:871",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173056,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220992,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:894",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220992,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351680,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:894",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351680,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:927",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509621,
      "name": "get_hwpoison_page.cold.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581499904,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:929",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595477,
      "name": "get_hwpoison_page.cold.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581585744,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:926",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707052,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581697984,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:930",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780488,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581771424,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:928",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:get_any_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002252,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581991744,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582051464,
      "name": "get_hwpoison_page",
      "external": false,
      "loc": "mm/memory-failure.c:1037",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int get_hwpoison_page(struct page * p, long unsigned int flags)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074048,
      "name": "get_hwpoison_page",
      "external": false,
      "loc": "mm/memory-failure.c:1101",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074048,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int get_hwpoison_page(struct page * p, long unsigned int flags)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582382224,
      "name": "get_hwpoison_page",
      "external": false,
      "loc": "mm/memory-failure.c:1245",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382224,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int get_hwpoison_page(struct page * p, long unsigned int flags)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": false,
      "loc": "mm/memory-failure.c:1330",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582890000,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071594006244,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int get_hwpoison_page(struct page * p, long unsigned int flags)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": false,
      "loc": "mm/memory-failure.c:1396",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583434560,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071596049301,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int get_hwpoison_page(struct page * p, long unsigned int flags)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": false,
      "loc": "mm/memory-failure.c:1529",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583656176,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    },
    {
      "addr": 18446744071596571825,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int get_hwpoison_page(struct page * p, long unsigned int flags)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": false,
      "loc": "mm/memory-failure.c:1540",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850512,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071597476344,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493229168,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:930",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493229168,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286742496,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:930",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286742496,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:930",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749224,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581740160,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:930",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687848,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581678800,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:930",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740536,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581731472,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int get_hwpoison_page(struct page * page)
```

```json
{
  "name": "get_hwpoison_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_hwpoison_page",
      "external": true,
      "loc": "mm/memory-failure.c:930",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808792,
      "name": "get_hwpoison_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581799760,
      "name": "get_hwpoison_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int get_hwpoison_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int get_hwpoison_page(struct page * p, long unsigned int flags)
```
</details>
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
int get_hwpoison_page(struct page * page)
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
int get_hwpoison_page(struct page * page)
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
