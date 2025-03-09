# Function: <code>undo_dev_pagemap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308928,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "arch/x86/mm/gup.c:68",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308928,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579324160,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "arch/x86/mm/gup.c:68",
      "file": "arch/x86/mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324160,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580871808,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1268",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__gup_device_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580871808,
      "name": "undo_dev_pagemap",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963168,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1357",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__gup_device_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963168,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098144,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1361",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__gup_device_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098144,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581177872,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1386",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177872,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247792,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1792",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247792,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306368,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1795",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306368,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void undo_dev_pagemap(int * nr, int nr_start, unsigned int flags, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498224,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:2203",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498224,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void undo_dev_pagemap(int * nr, int nr_start, unsigned int flags, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581539104,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1981",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539104,
      "name": "undo_dev_pagemap",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void undo_dev_pagemap(int * nr, int nr_start, unsigned int flags, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581561872,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:2047",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561872,
      "name": "undo_dev_pagemap",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void undo_dev_pagemap(int * nr, int nr_start, unsigned int flags, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826496,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:2135",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826496,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void undo_dev_pagemap(int * nr, int nr_start, unsigned int flags, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218464,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:2265",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218464,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
void undo_dev_pagemap(int * nr, int nr_start, unsigned int flags, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582707584,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:2293",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582707584,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
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
void undo_dev_pagemap(int * nr, int nr_start, unsigned int flags, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922080,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:2514",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922080,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
void undo_dev_pagemap(int * nr, int nr_start, unsigned int flags, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096192,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:2532",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096192,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492715480,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1795",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492715480,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286053344,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1795",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286053344,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275216,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1795",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275216,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581221696,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1795",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581221696,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266416,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1795",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266416,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
```

```json
{
  "name": "undo_dev_pagemap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330272,
      "name": "undo_dev_pagemap",
      "external": false,
      "loc": "mm/gup.c:1795",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330272,
      "name": "undo_dev_pagemap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
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
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>nr, nr_start, pages</code> ➡️ <code>nr, nr_start, flags, pages</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
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
void undo_dev_pagemap(int * nr, int nr_start, struct page * * pages)
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
