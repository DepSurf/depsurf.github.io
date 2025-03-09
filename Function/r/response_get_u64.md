# Function: <code>response_get_u64</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583412416,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:883",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412416,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583592080,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:895",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583592080,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583808992,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:912",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583808992,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583891872,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:912",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583891872,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584082352,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:951",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082352,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584205056,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205056,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597856,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:952",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:response_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597856,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584716704,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:952",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:response_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584716704,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744688,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:952",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744688,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585172752,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:952",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585172752,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585909488,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:952",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909488,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586698592,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:992",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586698592,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586959360,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:1000",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:response_get_column",
        "block/sed-opal.c:response_get_column",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586959360,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587239616,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:1117",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:response_get_column",
        "block/sed-opal.c:response_get_column",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587239616,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496075800,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496075800,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229404792,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229404792,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290315040,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290315040,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275146326,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275146326,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584173792,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173792,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584109040,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109040,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584157552,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157552,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
u64 response_get_u64(const struct parsed_resp * resp, int n)
```

```json
{
  "name": "response_get_u64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584261936,
      "name": "response_get_u64",
      "external": false,
      "loc": "block/sed-opal.c:950",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:parse_and_check_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261936,
      "name": "response_get_u64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
u64 response_get_u64(const struct parsed_resp * resp, int n)
```
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
