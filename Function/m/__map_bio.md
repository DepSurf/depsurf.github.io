# Function: <code>__map_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585795184,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1471",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__clone_and_map_simple_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585795184,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586193376,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:975",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__clone_and_map_simple_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586193376,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586397728,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1025",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__clone_and_map_simple_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397728,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586500384,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1181",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__clone_and_map_simple_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586500384,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
void __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586967808,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1172",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__clone_and_map_simple_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586967808,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587264432,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1234",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587264432,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587444576,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1258",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444576,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1263",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587714720,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071587730738,
      "name": "__map_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1263",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918928,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071587935090,
      "name": "__map_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1272",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588773600,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071588787598,
      "name": "__map_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1291",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588793200,
      "name": "__map_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071591592057,
      "name": "__map_bio.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1299",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588678288,
      "name": "__map_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
    },
    {
      "addr": 18446744071591535111,
      "name": "__map_bio.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1186",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589373632,
      "name": "__map_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
    },
    {
      "addr": 18446744071592648592,
      "name": "__map_bio.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __map_bio(struct bio * clone)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1313",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590847360,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
    },
    {
      "addr": 18446744071594533438,
      "name": "__map_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void __map_bio(struct bio * clone)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592538352,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1388",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592538352,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
void __map_bio(struct bio * clone)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592969376,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1412",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_duplicate_bios",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592969376,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
void __map_bio(struct bio * clone)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1398",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593719504,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
    },
    {
      "addr": 18446744071597765488,
      "name": "__map_bio.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501159920,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1263",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501159920,
      "name": "__map_bio",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233664576,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1263",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233664576,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294660272,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1263",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294660272,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277862752,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1263",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277862752,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1263",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587549904,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071587566066,
      "name": "__map_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1263",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318000,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071587334146,
      "name": "__map_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1263",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587875072,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071587891234,
      "name": "__map_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
blk_qc_t __map_bio(struct dm_target_io * tio)
```

```json
{
  "name": "__map_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__map_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1263",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_duplicate_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587990336,
      "name": "__map_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071588006498,
      "name": "__map_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>blk_qc_t</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
blk_qc_t __map_bio(struct dm_target_io * tio)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __map_bio(struct bio * clone)
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
