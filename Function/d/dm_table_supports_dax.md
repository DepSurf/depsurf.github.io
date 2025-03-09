# Function: <code>dm_table_supports_dax</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586211953,
      "name": "dm_table_supports_dax",
      "external": false,
      "loc": "drivers/md/dm-table.c:856",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586416396,
      "name": "dm_table_supports_dax",
      "external": false,
      "loc": "drivers/md/dm-table.c:850",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586520157,
      "name": "dm_table_supports_dax",
      "external": false,
      "loc": "drivers/md/dm-table.c:890",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586987593,
      "name": "dm_table_supports_dax",
      "external": false,
      "loc": "drivers/md/dm-table.c:892",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587280896,
      "name": "dm_table_supports_dax",
      "external": false,
      "loc": "drivers/md/dm-table.c:891",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587280896,
      "name": "dm_table_supports_dax.isra.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587461056,
      "name": "dm_table_supports_dax",
      "external": false,
      "loc": "drivers/md/dm-table.c:889",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587461056,
      "name": "dm_table_supports_dax.isra.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737168,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:900",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737168,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587941440,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:898",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941440,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588794512,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:885",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_determine_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588794512,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588812480,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:843",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_determine_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588812480,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588698368,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:829",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_determine_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588698368,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589386384,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:824",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_determine_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386384,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590855696,
      "name": "dm_table_supports_dax",
      "external": false,
      "loc": "drivers/md/dm-table.c:827",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_determine_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590855696,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592546992,
      "name": "dm_table_supports_dax",
      "external": false,
      "loc": "drivers/md/dm-table.c:826",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_determine_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592546992,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592978240,
      "name": "dm_table_supports_dax",
      "external": false,
      "loc": "drivers/md/dm-table.c:821",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_determine_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592978240,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593728224,
      "name": "dm_table_supports_dax",
      "external": false,
      "loc": "drivers/md/dm-table.c:842",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_determine_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593728224,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501180000,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:898",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501180000,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233687372,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:898",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233687372,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294692432,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:898",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294692432,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277883854,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:898",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277883854,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587572416,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:898",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587572416,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587340496,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:898",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587340496,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587897584,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:898",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587897584,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
```

```json
{
  "name": "dm_table_supports_dax",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588012848,
      "name": "dm_table_supports_dax",
      "external": true,
      "loc": "drivers/md/dm-table.c:898",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588012848,
      "name": "dm_table_supports_dax",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool dm_table_supports_dax(struct dm_table * t, iterate_devices_callout_fn iterate_fn, int * blocksize)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int * blocksize</code>
</li>
</ul>
</details>
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
