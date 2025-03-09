# Function: <code>__swap_count</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __swap_count(struct swap_info_struct * si, swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581112720,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1331",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581112720,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int __swap_count(struct swap_info_struct * si, swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248592,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1331",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248592,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int __swap_count(struct swap_info_struct * si, swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332096,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1348",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332096,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581441840,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1448",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581441840,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506064,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1448",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506064,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1485",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581728879,
      "name": "__swap_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581714592,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1503",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591331728,
      "name": "__swap_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581762480,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1502",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591274375,
      "name": "__swap_count.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581789536,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073584,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1471",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073584,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582513040,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1454",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513040,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583032032,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1434",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032032,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240896,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1440",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240896,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475424,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1440",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475424,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492927128,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1448",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492927128,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226715336,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1448",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226715336,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286335664,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1448",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286335664,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272846830,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1448",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272846830,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581474800,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1448",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581474800,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416208,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1448",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416208,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581466112,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1448",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466112,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int __swap_count(swp_entry_t entry)
```

```json
{
  "name": "__swap_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581530832,
      "name": "__swap_count",
      "external": true,
      "loc": "mm/swapfile.c:1448",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/page_io.c:swap_slot_free_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581530832,
      "name": "__swap_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int __swap_count(struct swap_info_struct * si, swp_entry_t entry)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct swap_info_struct * si</code>
</li>
<li>
<b>Param reordered. </b>
<code>si, entry</code> ➡️ <code>entry</code>
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
