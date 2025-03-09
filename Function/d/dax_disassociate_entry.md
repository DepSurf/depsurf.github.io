# Function: <code>dax_disassociate_entry</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581949152,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:365",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:__dax_invalidate_mapping_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949152,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035408,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:344",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035408,
      "name": "dax_disassociate_entry",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582200160,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:349",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200160,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280976,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:350",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280976,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567040,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:350",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567040,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582638608,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:350",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582638608,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582667472,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:361",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582667472,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582993312,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:361",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582993312,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583463920,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:361",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463920,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056880,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:393",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056880,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584281792,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:393",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281792,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498592,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:379",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498592,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493854920,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:350",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:__dax_invalidate_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493854920,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287484304,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:350",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287484304,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273424440,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:350",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:__dax_invalidate_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273424440,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582249712,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:350",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249712,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582187440,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:350",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582187440,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582240192,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:350",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240192,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```

```json
{
  "name": "dax_disassociate_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318672,
      "name": "dax_disassociate_entry",
      "external": false,
      "loc": "fs/dax.c:350",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_insert_entry",
        "fs/dax.c:__dax_invalidate_entry",
        "fs/dax.c:grab_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318672,
      "name": "dax_disassociate_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void dax_disassociate_entry(void * entry, struct address_space * mapping, bool trunc)
```
</details>
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
