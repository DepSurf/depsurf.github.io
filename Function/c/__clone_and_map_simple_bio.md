# Function: <code>__clone_and_map_simple_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __clone_and_map_simple_bio(struct clone_info * ci, struct dm_target * ti, unsigned int target_bio_nr, unsigned int * len)
```

```json
{
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585795456,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1559",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585795456,
      "name": "__clone_and_map_simple_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __clone_and_map_simple_bio(struct clone_info * ci, struct dm_target * ti, unsigned int target_bio_nr, unsigned int * len)
```

```json
{
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586193632,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1066",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586193632,
      "name": "__clone_and_map_simple_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __clone_and_map_simple_bio(struct clone_info * ci, struct dm_target * ti, unsigned int target_bio_nr, unsigned int * len)
```

```json
{
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586398160,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1121",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398160,
      "name": "__clone_and_map_simple_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __clone_and_map_simple_bio(struct clone_info * ci, struct dm_target * ti, unsigned int target_bio_nr, unsigned int * len)
```

```json
{
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586500832,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1294",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586500832,
      "name": "__clone_and_map_simple_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void __clone_and_map_simple_bio(struct clone_info * ci, struct dm_target * ti, unsigned int target_bio_nr, unsigned int * len)
```

```json
{
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586968256,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1285",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__send_changing_extent_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586968256,
      "name": "__clone_and_map_simple_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587268946,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1365",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587449654,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1388",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587719314,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1393",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587923602,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1393",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588778612,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1404",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588794072,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1435",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__send_duplicate_bios"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588679160,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1443",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__send_duplicate_bios"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589374607,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1339",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__send_duplicate_bios"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501162216,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1393",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233669864,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1393",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294669932,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1393",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277867208,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1393",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587554578,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1393",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587322674,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1393",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587879746,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1393",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
  "name": "__clone_and_map_simple_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587995378,
      "name": "__clone_and_map_simple_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1393",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__send_duplicate_bios"
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
void __clone_and_map_simple_bio(struct clone_info * ci, struct dm_target * ti, unsigned int target_bio_nr, unsigned int * len)
```
</details>
</li>
</ul>
