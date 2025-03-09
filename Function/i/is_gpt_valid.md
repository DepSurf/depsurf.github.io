# Function: <code>is_gpt_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int is_gpt_valid(struct parsed_partitions * state, u64 lba, gpt_header * * gpt, gpt_entry * * ptes)
```

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582858080,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:351",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582858080,
      "name": "is_gpt_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
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
int is_gpt_valid(struct parsed_partitions * state, u64 lba, gpt_header * * gpt, gpt_entry * * ptes)
```

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583143616,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:351",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583143616,
      "name": "is_gpt_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1065
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
int is_gpt_valid(struct parsed_partitions * state, u64 lba, gpt_header * * gpt, gpt_entry * * ptes)
```

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583255536,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:351",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583255536,
      "name": "is_gpt_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1065
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
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583309784,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:351",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308224,
      "name": "is_gpt_valid.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
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
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583492424,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:351",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490864,
      "name": "is_gpt_valid.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
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
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583704528,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:351",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:find_valid_gpt"
      ],
      "caller_func": [
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:find_valid_gpt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703040,
      "name": "is_gpt_valid.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583812156,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:351",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810832,
      "name": "is_gpt_valid.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584002238,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000912,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1134
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
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584105610,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104272,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584499920,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584499920,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584610768,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584610768,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584642192,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584642192,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585058800,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:335",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058800,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1016
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
int is_gpt_valid(struct parsed_partitions * state, u64 lba, gpt_header * * gpt, gpt_entry * * ptes)
```

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585781104,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:335",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781104,
      "name": "is_gpt_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1022
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
int is_gpt_valid(struct parsed_partitions * state, u64 lba, gpt_header * * gpt, gpt_entry * * ptes)
```

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586561968,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:335",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586561968,
      "name": "is_gpt_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1000
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
int is_gpt_valid(struct parsed_partitions * state, u64 lba, gpt_header * * gpt, gpt_entry * * ptes)
```

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586818080,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:335",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818080,
      "name": "is_gpt_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1033
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
int is_gpt_valid(struct parsed_partitions * state, u64 lba, gpt_header * * gpt, gpt_entry * * ptes)
```

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587095120,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:335",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587095120,
      "name": "is_gpt_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1033
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
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495949432,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495947968,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229292892,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229291316,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290169120,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:find_valid_gpt"
      ],
      "caller_func": [
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:find_valid_gpt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290167264,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275059930,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275058576,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584074346,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073008,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584010106,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008768,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584058106,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056768,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
  "name": "is_gpt_valid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584160602,
      "name": "is_gpt_valid",
      "external": false,
      "loc": "block/partitions/efi.c:337",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159264,
      "name": "is_gpt_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
int is_gpt_valid(struct parsed_partitions * state, u64 lba, gpt_header * * gpt, gpt_entry * * ptes)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int is_gpt_valid(struct parsed_partitions * state, u64 lba, gpt_header * * gpt, gpt_entry * * ptes)
```
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
