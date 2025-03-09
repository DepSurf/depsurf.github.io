# Function: <code>match_config_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int match_config_table(efi_guid_t * guid, long unsigned int table, efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595320253,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:373",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595320253,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 285
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
int match_config_table(efi_guid_t * guid, long unsigned int table, efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595506128,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:442",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595506128,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 348
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
int match_config_table(efi_guid_t * guid, long unsigned int table, efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595759519,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:451",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595759519,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596690420,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:450",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596688597,
      "name": "match_config_table.part.1",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 302
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603020451,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:470",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603018628,
      "name": "match_config_table.part.1",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 302
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603192032,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:482",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603192032,
      "name": "match_config_table.isra.2",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605002430,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:493",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605002430,
      "name": "match_config_table.isra.4",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605114661,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:494",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605114661,
      "name": "match_config_table.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605153258,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:484",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605153258,
      "name": "match_config_table.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 283
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
int match_config_table(const efi_guid_t * guid, long unsigned int table, const efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609422642,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:526",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609422642,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 290
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
int match_config_table(const efi_guid_t * guid, long unsigned int table, const efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612496458,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:533",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612496458,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 290
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
int match_config_table(const efi_guid_t * guid, long unsigned int table, const efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614638370,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:533",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614638370,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 290
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
int match_config_table(const efi_guid_t * guid, long unsigned int table, const efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615596166,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:533",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615596166,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 290
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
int match_config_table(const efi_guid_t * guid, long unsigned int table, const efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617404776,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:547",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617404776,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 285
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
int match_config_table(const efi_guid_t * guid, long unsigned int table, const efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628155776,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:559",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628155776,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 247
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
int match_config_table(const efi_guid_t * guid, long unsigned int table, const efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619922864,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:601",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619922864,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 287
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
int match_config_table(const efi_guid_t * guid, long unsigned int table, const efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622234000,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:623",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622234000,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 287
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511280308,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:484",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511280308,
      "name": "match_config_table.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 248
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
int match_config_table(efi_guid_t * guid, long unsigned int table, efi_config_table_type_t * table_types)
```

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243931536,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:484",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243931536,
      "name": "match_config_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605043696,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:484",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605043696,
      "name": "match_config_table.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605009036,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:484",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605009036,
      "name": "match_config_table.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605130271,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:484",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605130271,
      "name": "match_config_table.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_config_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605157452,
      "name": "match_config_table",
      "external": false,
      "loc": "drivers/firmware/efi/efi.c:484",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605157452,
      "name": "match_config_table.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 283
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int match_config_table(efi_guid_t * guid, long unsigned int table, efi_config_table_type_t * table_types)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int match_config_table(const efi_guid_t * guid, long unsigned int table, const efi_config_table_type_t * table_types)
```
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int match_config_table(efi_guid_t * guid, long unsigned int table, efi_config_table_type_t * table_types)
```
</details>
</li>
</ul>
