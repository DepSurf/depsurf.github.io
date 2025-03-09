# Function: <code>parse_slub_debug_flags</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
char * parse_slub_debug_flags(char * str, slab_flags_t * flags, char * * slabs, bool init)
```

```json
{
  "name": "parse_slub_debug_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_slub_debug_flags",
      "external": false,
      "loc": "mm/slub.c:1271",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_flags",
        "mm/slub.c:setup_slub_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871760,
      "name": "parse_slub_debug_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071591333303,
      "name": "parse_slub_debug_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
char * parse_slub_debug_flags(char * str, slab_flags_t * flags, char * * slabs, bool init)
```

```json
{
  "name": "parse_slub_debug_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_slub_debug_flags",
      "external": false,
      "loc": "mm/slub.c:1283",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_flags",
        "mm/slub.c:setup_slub_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902352,
      "name": "parse_slub_debug_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071591276310,
      "name": "parse_slub_debug_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
char * parse_slub_debug_flags(char * str, slab_flags_t * flags, char * * slabs, bool init)
```

```json
{
  "name": "parse_slub_debug_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_slub_debug_flags",
      "external": false,
      "loc": "mm/slub.c:1407",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_flags",
        "mm/slub.c:setup_slub_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582197072,
      "name": "parse_slub_debug_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071592217186,
      "name": "parse_slub_debug_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
char * parse_slub_debug_flags(char * str, slab_flags_t * flags, char * * slabs, bool init)
```

```json
{
  "name": "parse_slub_debug_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_slub_debug_flags",
      "external": false,
      "loc": "mm/slub.c:1456",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_flags",
        "mm/slub.c:setup_slub_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661168,
      "name": "parse_slub_debug_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
    },
    {
      "addr": 18446744071593996068,
      "name": "parse_slub_debug_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
char * parse_slub_debug_flags(char * str, slab_flags_t * flags, char * * slabs, bool init)
```

```json
{
  "name": "parse_slub_debug_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583185152,
      "name": "parse_slub_debug_flags",
      "external": false,
      "loc": "mm/slub.c:1492",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_flags",
        "mm/slub.c:setup_slub_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185152,
      "name": "parse_slub_debug_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
char * parse_slub_debug_flags(char * str, slab_flags_t * flags, char * * slabs, bool init)
```

```json
{
  "name": "parse_slub_debug_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583403024,
      "name": "parse_slub_debug_flags",
      "external": false,
      "loc": "mm/slub.c:1505",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_flags",
        "mm/slub.c:setup_slub_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583403024,
      "name": "parse_slub_debug_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
char * parse_slub_debug_flags(char * str, slab_flags_t * flags, char * * slabs, bool init)
```

```json
{
  "name": "parse_slub_debug_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583382480,
      "name": "parse_slub_debug_flags",
      "external": false,
      "loc": "mm/slub.c:1629",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_flags",
        "mm/slub.c:setup_slub_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382480,
      "name": "parse_slub_debug_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
char * parse_slub_debug_flags(char * str, slab_flags_t * flags, char * * slabs, bool init)
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
