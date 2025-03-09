# Function: <code>hib_submit_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int hib_submit_io(int rw, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707680,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:253",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:swap_read_page",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707680,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579727488,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:264",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swap_read_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727488,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579754992,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:264",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swap_read_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754992,
      "name": "hib_submit_io",
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751136,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:264",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751136,
      "name": "hib_submit_io",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784496,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:265",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784496,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:265",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818576,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071579825435,
      "name": "hib_submit_io.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:265",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865280,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071579872171,
      "name": "hib_submit_io.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:263",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899824,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071579906644,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:263",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950048,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071579956900,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:263",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:get_swap_reader",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:mark_swapfiles",
        "kernel/power/swap.c:mark_swapfiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995136,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071580002550,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:270",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:get_swap_reader",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:mark_swapfiles",
        "kernel/power/swap.c:mark_swapfiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977424,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071591297002,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:270",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:mark_swapfiles",
        "kernel/power/swap.c:mark_swapfiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979408,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    },
    {
      "addr": 18446744071591239671,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:270",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:mark_swapfiles",
        "kernel/power/swap.c:mark_swapfiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110640,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    },
    {
      "addr": 18446744071592127658,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:272",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:mark_swapfiles",
        "kernel/power/swap.c:mark_swapfiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580250592,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071593898208,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int hib_submit_io(blk_opf_t opf, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580450592,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:272",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:mark_swapfiles",
        "kernel/power/swap.c:mark_swapfiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450592,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int hib_submit_io(blk_opf_t opf, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580520624,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:272",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:mark_swapfiles",
        "kernel/power/swap.c:mark_swapfiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520624,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int hib_submit_io(blk_opf_t opf, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580582160,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:272",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:mark_swapfiles",
        "kernel/power/swap.c:mark_swapfiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580582160,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225160636,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:263",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225160636,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:324",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917840,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071579925381,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:263",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857056,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071579863908,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:263",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910320,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071579917172,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```

```json
{
  "name": "hib_submit_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hib_submit_io",
      "external": false,
      "loc": "kernel/power/swap.c:263",
      "file": "kernel/power/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_unmark",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swsusp_read",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:swsusp_write",
        "kernel/power/swap.c:write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956384,
      "name": "hib_submit_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071579963220,
      "name": "hib_submit_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, page_off, addr, hb</code> ➡️ <code>op, op_flags, page_off, addr, hb</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, op_flags, page_off, addr, hb</code> ➡️ <code>opf, page_off, addr, hb</code>
</li>
</ul>
</details>
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
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int hib_submit_io(int op, int op_flags, long unsigned int page_off, void * addr, struct hib_bio_batch * hb)
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
