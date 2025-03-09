# Function: <code>__send_duplicate_bios</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585795773,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1575",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__send_changing_extent_only",
        "drivers/md/dm.c:__split_and_process_bio"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586198575,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1082",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__send_changing_extent_only"
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
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586403088,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1137",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__send_changing_extent_only"
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
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586506036,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1310",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__send_changing_extent_only"
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
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586973013,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1301",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__send_changing_extent_only"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587267232,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1379",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587267232,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587447216,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1402",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447216,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587717088,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1407",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587717088,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587921376,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1407",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587921376,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588774016,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1418",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_abnormal_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774016,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588793712,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1449",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588793712,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588678800,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1457",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588678800,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1353",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589374240,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071592648648,
      "name": "__send_duplicate_bios.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590847904,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1429",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590847904,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592538880,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1494",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592538880,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592969904,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1520",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592969904,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
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
unsigned int __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len, gfp_t gfp_flag)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593720096,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1513",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:__send_empty_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593720096,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501160464,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1407",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501160464,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233667404,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1407",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233667404,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294666768,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1407",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294666768,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277865236,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1407",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277865236,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587552352,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1407",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587552352,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587320448,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1407",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587320448,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587877520,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1407",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877520,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```

```json
{
  "name": "__send_duplicate_bios",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587993072,
      "name": "__send_duplicate_bios",
      "external": false,
      "loc": "drivers/md/dm.c:1407",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587993072,
      "name": "__send_duplicate_bios",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __send_duplicate_bios(struct clone_info * ci, struct dm_target * ti, unsigned int num_bios, unsigned int * len)
```
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flag</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
