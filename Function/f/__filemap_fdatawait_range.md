# Function: <code>__filemap_fdatawait_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469760,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:334",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469760,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
int __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580547552,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:413",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580547552,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613664,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:378",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613664,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580642496,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:414",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642496,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580724800,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:511",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580724800,
      "name": "__filemap_fdatawait_range",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860576,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:511",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860576,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935168,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:488",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935168,
      "name": "__filemap_fdatawait_range",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021488,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:497",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021488,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076720,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:503",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076720,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581263696,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:503",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263696,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581305872,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:504",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581305872,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323456,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:495",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323456,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569024,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:513",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569024,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924416,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:501",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924416,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582363120,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:501",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors",
        "mm/filemap.c:filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582363120,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571312,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:506",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors",
        "mm/filemap.c:filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571312,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582741104,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:501",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors",
        "mm/filemap.c:filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741104,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492443408,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:503",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492443408,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226315920,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:503",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226315920,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285712240,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:503",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285712240,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272516302,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:503",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors",
        "mm/filemap.c:filemap_fdatawait_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272516302,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045568,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:503",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045568,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992848,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:503",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992848,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036768,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:503",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036768,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "__filemap_fdatawait_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098352,
      "name": "__filemap_fdatawait_range",
      "external": false,
      "loc": "mm/filemap.c:503",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_fdatawait_keep_errors",
        "mm/filemap.c:file_fdatawait_range",
        "mm/filemap.c:filemap_fdatawait_range_keep_errors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098352,
      "name": "__filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
