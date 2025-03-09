# Function: <code>add_bytestring_header</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584083616,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:606",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584083616,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584206320,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:607",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206320,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584600976,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:609",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600976,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584719824,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:609",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719824,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584747200,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:609",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584747200,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585175712,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:609",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585175712,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585913392,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:609",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913392,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586703296,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:649",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586703296,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586963360,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:657",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963360,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587245152,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:770",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587245152,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496077216,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:607",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496077216,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229406276,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:607",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229406276,
      "name": "add_bytestring_header",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290316912,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:607",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290316912,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275147772,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:607",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275147772,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584175056,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:607",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175056,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584110304,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:607",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110304,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584158816,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:607",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584158816,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```

```json
{
  "name": "add_bytestring_header",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584263200,
      "name": "add_bytestring_header",
      "external": false,
      "loc": "block/sed-opal.c:607",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:add_token_bytestring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584263200,
      "name": "add_bytestring_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
u8 * add_bytestring_header(int * err, struct opal_dev * cmd, size_t len)
```
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
