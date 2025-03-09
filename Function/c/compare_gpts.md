# Function: <code>compare_gpts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582859232,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:490",
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
      "addr": 18446744071582859232,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583144688,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:490",
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
      "addr": 18446744071583144688,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583256608,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:490",
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
      "addr": 18446744071583256608,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307568,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:497",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071583307568,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583490208,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:497",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071583490208,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
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
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583704751,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:497",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:find_valid_gpt"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:497",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810496,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071583813726,
      "name": "compare_gpts.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000576,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071584003848,
      "name": "compare_gpts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103936,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071584107213,
      "name": "compare_gpts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498864,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071584502784,
      "name": "compare_gpts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584609744,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071591376194,
      "name": "compare_gpts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584641296,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071591318850,
      "name": "compare_gpts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:481",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585057936,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071592319371,
      "name": "compare_gpts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:481",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585780160,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071594103830,
      "name": "compare_gpts.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586560768,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:481",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586560768,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586816416,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:481",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816416,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587093456,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:481",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587093456,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495946872,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
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
      "addr": 18446603336495946872,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229290456,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
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
      "addr": 3229290456,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
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
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290169384,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:find_valid_gpt"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275056380,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275056380,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2094
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072672,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071584075949,
      "name": "compare_gpts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008432,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071584011709,
      "name": "compare_gpts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056432,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071584059709,
      "name": "compare_gpts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```

```json
{
  "name": "compare_gpts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compare_gpts",
      "external": false,
      "loc": "block/partitions/efi.c:483",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584158928,
      "name": "compare_gpts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    },
    {
      "addr": 18446744071584162205,
      "name": "compare_gpts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void compare_gpts(gpt_header * pgpt, gpt_header * agpt, u64 lastlba)
```
</details>
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
