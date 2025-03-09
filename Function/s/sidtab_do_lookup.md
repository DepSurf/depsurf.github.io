# Function: <code>sidtab_do_lookup</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583186912,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583186912,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
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
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583374192,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583374192,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583480144,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480144,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
struct sidtab_entry * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583825872,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:179",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_entry_force",
        "security/selinux/ss/sidtab.c:sidtab_search_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583825872,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
struct sidtab_entry * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947312,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:179",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_entry_force",
        "security/selinux/ss/sidtab.c:sidtab_search_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947312,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
struct sidtab_entry * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974304,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:180",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_entry_force",
        "security/selinux/ss/sidtab.c:sidtab_search_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974304,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
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
struct sidtab_entry * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:180",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_entry_force",
        "security/selinux/ss/sidtab.c:sidtab_search_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339904,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
    },
    {
      "addr": 18446744071592297245,
      "name": "sidtab_do_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct sidtab_entry * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:180",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_entry_force",
        "security/selinux/ss/sidtab.c:sidtab_search_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584960800,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071594078887,
      "name": "sidtab_do_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct sidtab_entry * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:181",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_entry_force",
        "security/selinux/ss/sidtab.c:sidtab_search_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585674016,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071596096003,
      "name": "sidtab_do_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct sidtab_entry * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:181",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_entry_force",
        "security/selinux/ss/sidtab.c:sidtab_search_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585904064,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
    },
    {
      "addr": 18446744071596619218,
      "name": "sidtab_do_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct sidtab_entry * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:181",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_entry_force",
        "security/selinux/ss/sidtab.c:sidtab_search_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152480,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1335
    },
    {
      "addr": 18446744071597524918,
      "name": "sidtab_do_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495244248,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495244248,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228625876,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228625876,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289213824,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289213824,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
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
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274470730,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274470730,
      "name": "sidtab_do_lookup",
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
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583448880,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448880,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583385952,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385952,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583432656,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583432656,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```

```json
{
  "name": "sidtab_do_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583528912,
      "name": "sidtab_do_lookup",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:91",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_search_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528912,
      "name": "sidtab_do_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct context * sidtab_do_lookup(struct sidtab * s, u32 index, int alloc)
```
</details>
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
<b>Return type changed. </b>
<code>struct context *</code> ➡️ <code>struct sidtab_entry *</code>
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
