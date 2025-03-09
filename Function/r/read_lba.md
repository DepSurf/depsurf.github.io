# Function: <code>read_lba</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582839040,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:95",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071582857552,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:251",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582839040,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    },
    {
      "addr": 18446744071582857552,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583122416,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:95",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071583142992,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:251",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:is_gpt_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122416,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    },
    {
      "addr": 18446744071583142992,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583234336,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:95",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071583254912,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:251",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:is_gpt_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234336,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    },
    {
      "addr": 18446744071583254912,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583287920,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:95",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071583307072,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:251",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583287920,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071583307072,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583468608,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071583489664,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:251",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468608,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071583489664,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583681104,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071583702496,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:251",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:find_valid_gpt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681104,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071583702496,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583788400,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071583809952,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:251",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788400,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071583809952,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583978224,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071584000032,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978224,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071584000032,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584081600,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071584103392,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584081600,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071584103392,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584476720,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:95",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071584499200,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:alloc_read_gpt_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476720,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071584499200,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584590320,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:95",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071584610080,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:alloc_read_gpt_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590320,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071584610080,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584622368,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:95",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071584641632,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584622368,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071584641632,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585037883,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:79",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071585058272,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:235",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585036928,
      "name": "read_lba.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071585058272,
      "name": "read_lba",
      "section": ".text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585755040,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:79",
      "file": "block/partitions/aix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071585780512,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:235",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:is_gpt_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585755040,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071585780512,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586537216,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:79",
      "file": "block/partitions/aix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071586561536,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:235",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:is_gpt_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537216,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071586561536,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586786320,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:79",
      "file": "block/partitions/aix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071586817648,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:235",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:is_gpt_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586786320,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071586817648,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587063072,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:79",
      "file": "block/partitions/aix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071587094688,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:235",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:is_gpt_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063072,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071587094688,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495923904,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446603336495947544,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495923904,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446603336495947544,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229267344,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 3229289776,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229267344,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 3229289776,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290137008,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 13835058055290166608,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:find_valid_gpt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290137008,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 13835058055290166608,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275036838,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446743936275056086,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275056086,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446743936275036838,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584050336,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071584072128,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050336,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071584072128,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583986096,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071584007888,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986096,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071584007888,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584034096,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071584055888,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584034096,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071584055888,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
size_t read_lba(struct parsed_partitions * state, u64 lba, u8 * buffer, size_t count)
```

```json
{
  "name": "read_lba",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584136592,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/aix.c:96",
      "file": "block/partitions/aix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ]
    },
    {
      "addr": 18446744071584158384,
      "name": "read_lba",
      "external": false,
      "loc": "block/partitions/efi.c:237",
      "file": "block/partitions/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/efi.c:efi_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136592,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071584158384,
      "name": "read_lba",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
