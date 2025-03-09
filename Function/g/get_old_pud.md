# Function: <code>get_old_pud</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
pud_t * get_old_pud(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "get_old_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581642448,
      "name": "get_old_pud",
      "external": false,
      "loc": "mm/mremap.c:33",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581642448,
      "name": "get_old_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
pud_t * get_old_pud(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "get_old_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664048,
      "name": "get_old_pud",
      "external": false,
      "loc": "mm/mremap.c:32",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664048,
      "name": "get_old_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
pud_t * get_old_pud(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "get_old_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_old_pud",
      "external": false,
      "loc": "mm/mremap.c:33",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932384,
      "name": "get_old_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071592200866,
      "name": "get_old_pud.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
pud_t * get_old_pud(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "get_old_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_old_pud",
      "external": false,
      "loc": "mm/mremap.c:33",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340896,
      "name": "get_old_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071593977383,
      "name": "get_old_pud.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
pud_t * get_old_pud(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "get_old_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_old_pud",
      "external": false,
      "loc": "mm/mremap.c:35",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582842512,
      "name": "get_old_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071596033356,
      "name": "get_old_pud.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
pud_t * get_old_pud(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "get_old_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_old_pud",
      "external": false,
      "loc": "mm/mremap.c:35",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583058256,
      "name": "get_old_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071596555303,
      "name": "get_old_pud.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
pud_t * get_old_pud(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "get_old_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_old_pud",
      "external": false,
      "loc": "mm/mremap.c:35",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239968,
      "name": "get_old_pud",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071597459408,
      "name": "get_old_pud.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
pud_t * get_old_pud(struct mm_struct * mm, long unsigned int addr)
```
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
