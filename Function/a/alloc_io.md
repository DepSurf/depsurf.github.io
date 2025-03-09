# Function: <code>alloc_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585802216,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:630",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586197736,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:484",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586402232,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:484",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586505686,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:482",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586972662,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:489",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587263536,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:534",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587263536,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587443808,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:585",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587443808,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587713936,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:565",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587713936,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587918144,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:565",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918144,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588769488,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:596",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588769488,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588788992,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:631",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588788992,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588680457,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:636",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589375803,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:516",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590848748,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:574",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592539849,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:569",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592970953,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:573",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:573",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593709296,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071597765440,
      "name": "alloc_io.cold",
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501150568,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:565",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501150568,
      "name": "alloc_io",
      "section": ".text",
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233663844,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:565",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233663844,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294659232,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:565",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294659232,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277862096,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:565",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277862096,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587549120,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:565",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587549120,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587317216,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:565",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587317216,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587874288,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:565",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587874288,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```

```json
{
  "name": "alloc_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587989552,
      "name": "alloc_io",
      "external": false,
      "loc": "drivers/md/dm.c:565",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587989552,
      "name": "alloc_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct dm_io * alloc_io(struct mapped_device * md, struct bio * bio, gfp_t gfp_mask)
```
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
