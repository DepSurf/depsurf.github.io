# Function: <code>decompress_record</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582517972,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:778",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582669548,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:775",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582862457,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:621",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582970505,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:664",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583151369,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:658",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583257433,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:658",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:668",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void decompress_record(struct pstore_record * record)
```

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:668",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/platform.c:pstore_get_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703840,
      "name": "decompress_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071591360972,
      "name": "decompress_record.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void decompress_record(struct pstore_record * record)
```

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:671",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/platform.c:pstore_get_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728576,
      "name": "decompress_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071591303797,
      "name": "decompress_record.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void decompress_record(struct pstore_record * record)
```

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:671",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/platform.c:pstore_get_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089824,
      "name": "decompress_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071592290064,
      "name": "decompress_record.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void decompress_record(struct pstore_record * record)
```

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:669",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/platform.c:pstore_get_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584683872,
      "name": "decompress_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071594071906,
      "name": "decompress_record.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void decompress_record(struct pstore_record * record)
```

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:684",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/platform.c:pstore_get_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585369472,
      "name": "decompress_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071596092167,
      "name": "decompress_record.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void decompress_record(struct pstore_record * record)
```

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:684",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/platform.c:pstore_get_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585599872,
      "name": "decompress_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 18446744071596615531,
      "name": "decompress_record.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void decompress_record(struct pstore_record * record, struct z_stream_s * zstream)
```

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:582",
      "file": "fs/pstore/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/platform.c:pstore_get_backend_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585846240,
      "name": "decompress_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    },
    {
      "addr": 18446744071597521435,
      "name": "decompress_record.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494986232,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:658",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228391640,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:658",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288869988,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:658",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274285336,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:658",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583226169,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:658",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583163321,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:658",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583210201,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:658",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "decompress_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583304089,
      "name": "decompress_record",
      "external": false,
      "loc": "fs/pstore/platform.c:658",
      "file": "fs/pstore/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pstore/platform.c:pstore_get_backend_records"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void decompress_record(struct pstore_record * record)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct z_stream_s * zstream</code>
</li>
</ul>
</details>
</li>
</ul>
