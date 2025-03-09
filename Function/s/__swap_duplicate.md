# Function: <code>__swap_duplicate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760928,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:2629",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swap_shmem_alloc",
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760928,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883328,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:2615",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883328,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951408,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:2627",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951408,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580997392,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3106",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997392,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103824,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3355",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103824,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3379",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581244464,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    },
    {
      "addr": 18446744071581263612,
      "name": "__swap_duplicate.cold.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3357",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328016,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071581346780,
      "name": "__swap_duplicate.cold.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581439008,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3369",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439008,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503232,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3377",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503232,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581711968,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3431",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711968,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759872,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3452",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759872,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786864,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3423",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786864,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070848,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3424",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070848,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582510704,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3280",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582510704,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583029696,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3282",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583029696,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233168,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3273",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233168,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583468256,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3271",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468256,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492924920,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3377",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492924920,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226713576,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3377",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226713576,
      "name": "__swap_duplicate",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286332832,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3377",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286332832,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272844710,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3377",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272844710,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471968,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3377",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471968,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414224,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3377",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414224,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463280,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3377",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463280,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int __swap_duplicate(swp_entry_t entry, unsigned char usage)
```

```json
{
  "name": "__swap_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581528000,
      "name": "__swap_duplicate",
      "external": false,
      "loc": "mm/swapfile.c:3377",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swapcache_prepare",
        "mm/swapfile.c:swap_duplicate",
        "mm/swapfile.c:swap_shmem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528000,
      "name": "__swap_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
