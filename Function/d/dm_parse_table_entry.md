# Function: <code>dm_parse_table_entry</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605094947,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605134376,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
char * dm_parse_table_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609404910,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_parse_device_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609404910,
      "name": "dm_parse_table_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 346
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
char * dm_parse_table_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612478239,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_parse_device_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612478239,
      "name": "dm_parse_table_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 346
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
char * dm_parse_table_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614620750,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_parse_device_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614620750,
      "name": "dm_parse_table_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 346
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
char * dm_parse_table_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615576219,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_parse_device_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615576219,
      "name": "dm_parse_table_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 523
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
char * dm_parse_table_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617383794,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_parse_device_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617383794,
      "name": "dm_parse_table_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 615
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
char * dm_parse_table_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628127616,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:112",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_parse_device_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628127616,
      "name": "dm_parse_table_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 862
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
char * dm_parse_table_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619894272,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:111",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_parse_device_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619894272,
      "name": "dm_parse_table_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 862
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
char * dm_parse_table_entry(struct dm_device * dev, char * str)
```

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622204048,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:111",
      "file": "drivers/md/dm-init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-init.c:dm_parse_device_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622204048,
      "name": "dm_parse_table_entry",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 909
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
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511261968,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_init_init"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243913988,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_init_init"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302838032,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270830042,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605027388,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604992846,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_parse_table_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605138570,
      "name": "dm_parse_table_entry",
      "external": false,
      "loc": "drivers/md/dm-init.c:106",
      "file": "drivers/md/dm-init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-init.c:dm_parse_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
char * dm_parse_table_entry(struct dm_device * dev, char * str)
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
