# Function: <code>migrate_prep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580881616,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:54",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SyS_move_pages"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881616,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581018286,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:56",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SyS_move_pages"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012432,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581092719,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:56",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:do_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086608,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581139546,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:58",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134240,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581261546,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:62",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/mempolicy.c:SYSC_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252176,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581407688,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:63",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398256,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581491176,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:63",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481856,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581599037,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:63",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592960,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581669594,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:64",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661040,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581888922,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:65",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": [
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882368,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581935385,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:65",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": [
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928416,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493113084,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:64",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493106536,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226803312,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:64",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226803312,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286589388,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:64",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:do_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286575728,
      "name": "migrate_prep",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272953700,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:64",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272953700,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581638330,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:64",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581629776,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581579290,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:64",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570832,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581629642,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:64",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621088,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int migrate_prep()
```

```json
{
  "name": "migrate_prep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581695946,
      "name": "migrate_prep",
      "external": true,
      "loc": "mm/migrate.c:64",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687472,
      "name": "migrate_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void migrate_prep()
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
