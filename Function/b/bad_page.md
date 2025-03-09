# Function: <code>bad_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580491072,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:400",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pages_prepare",
        "mm/page_alloc.c:free_pages_prepare",
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": [
        "mm/page_alloc.c:free_pages_prepare",
        "mm/page_alloc.c:free_pages_prepare",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580491072,
      "name": "bad_page.part.68",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580574608,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:508",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580574608,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641040,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:513",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641040,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580673488,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:529",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673488,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758848,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:544",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758848,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:505",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894864,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071580920882,
      "name": "bad_page.cold.113",
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:550",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969664,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071580996726,
      "name": "bad_page.cold.117",
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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:612",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387520,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581415791,
      "name": "bad_page.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:599",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448464,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581476831,
      "name": "bad_page.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void bad_page(struct page * page, const char * reason)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:598",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:check_free_page_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653888,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071581681809,
      "name": "bad_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void bad_page(struct page * page, const char * reason)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:598",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:check_free_page_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581701440,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071591328648,
      "name": "bad_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void bad_page(struct page * page, const char * reason)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:620",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:check_free_page_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581722848,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071591270759,
      "name": "bad_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void bad_page(struct page * page, const char * reason)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:621",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:check_free_page_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995584,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071592202362,
      "name": "bad_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void bad_page(struct page * page, const char * reason)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:611",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_pages",
        "mm/page_alloc.c:check_free_page_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419040,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071593979628,
      "name": "bad_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void bad_page(struct page * page, const char * reason)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582925680,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:668",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_pages",
        "mm/page_alloc.c:free_page_is_bad_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582925680,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
void bad_page(struct page * page, const char * reason)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583141888,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:502",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__rmqueue_pcplist",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_page_is_bad_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583141888,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
void bad_page(struct page * page, const char * reason)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583325136,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:483",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:__rmqueue_pcplist",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_tail_page_prepare",
        "mm/page_alloc.c:free_page_is_bad_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325136,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492854872,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:599",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492854872,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226655136,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:599",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226655136,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286243536,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:599",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286243536,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272801944,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:599",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272801944,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:599",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417312,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581445679,
      "name": "bad_page.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:599",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359824,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581388047,
      "name": "bad_page.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:599",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408512,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581436879,
      "name": "bad_page.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```

```json
{
  "name": "bad_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bad_page",
      "external": false,
      "loc": "mm/page_alloc.c:599",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:check_new_page_bad",
        "mm/page_alloc.c:free_pages_check_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472608,
      "name": "bad_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581501375,
      "name": "bad_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void bad_page(struct page * page, const char * reason, long unsigned int bad_flags)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int bad_flags</code>
</li>
</ul>
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
