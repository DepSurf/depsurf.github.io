# Function: <code>unuse_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613520,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:51",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580762160,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1301",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762160,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1902
    },
    {
      "addr": 18446744071580613520,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580717248,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:51",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580884576,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1291",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884576,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2053
    },
    {
      "addr": 18446744071580717248,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580783008,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:51",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580952656,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1312",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952656,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2065
    },
    {
      "addr": 18446744071580783008,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819376,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580997936,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1744",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997936,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1879
    },
    {
      "addr": 18446744071580819376,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909392,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581108960,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1956",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108960,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2223
    },
    {
      "addr": 18446744071580909392,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045248,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581246896,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1956",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246896,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581045248,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581122912,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581330432,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1928",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330432,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581122912,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581187696,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ]
    },
    {
      "addr": 18446744071581448033,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2067",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187696,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581246144,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ]
    },
    {
      "addr": 18446744071581512257,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2067",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246144,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unuse_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581721631,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2097",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int unuse_mm(struct mm_struct * mm, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768624,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2113",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768624,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unuse_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581797035,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2114",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unuse_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582081414,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2101",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unuse_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582520089,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1990",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unuse_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583038297,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1990",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unuse_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583246825,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1981",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unuse_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583481353,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:1989",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492645960,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ]
    },
    {
      "addr": 18446603336492934708,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2067",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492645960,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226487132,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ]
    },
    {
      "addr": 3226719352,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2067",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226719352,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
    },
    {
      "addr": 3226487132,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285962880,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ]
    },
    {
      "addr": 13835058055286344952,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2067",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285962880,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272660498,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ]
    },
    {
      "addr": 18446743936272852976,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2067",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272660498,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581214992,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ]
    },
    {
      "addr": 18446744071581480993,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2067",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214992,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581161696,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ]
    },
    {
      "addr": 18446744071581423327,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2067",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581161696,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581206192,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ]
    },
    {
      "addr": 18446744071581472305,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2067",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206192,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void unuse_mm(struct mm_struct * mm)
```

```json
{
  "name": "unuse_mm",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581269552,
      "name": "unuse_mm",
      "external": true,
      "loc": "mm/mmu_context.c:53",
      "file": "mm/mmu_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ]
    },
    {
      "addr": 18446744071581537132,
      "name": "unuse_mm",
      "external": false,
      "loc": "mm/swapfile.c:2067",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269552,
      "name": "unuse_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void unuse_mm(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int unuse_mm(struct mm_struct * mm, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int unuse_mm(struct mm_struct * mm, unsigned int type, bool frontswap, long unsigned int * fs_pages_to_unuse)
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
