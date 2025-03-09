# Function: <code>memory_bm_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699856,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:612",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_write_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699856,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719584,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:684",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719584,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747120,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:684",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747120,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743376,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:686",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743376,
      "name": "memory_bm_free",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776688,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:688",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776688,
      "name": "memory_bm_free",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810144,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:688",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810144,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856864,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:688",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856864,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890976,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:686",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890976,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941248,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:686",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941248,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984304,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:685",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984304,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579969072,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:719",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969072,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971712,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:719",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971712,
      "name": "memory_bm_free",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580103200,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:719",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103200,
      "name": "memory_bm_free",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580242112,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:723",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242112,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580438656,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:723",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580438656,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507616,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:723",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507616,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567552,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:725",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567552,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225149960,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:686",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225149960,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579909024,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:685",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909024,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848256,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:686",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848256,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579901520,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:686",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901520,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```

```json
{
  "name": "memory_bm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947552,
      "name": "memory_bm_free",
      "external": false,
      "loc": "kernel/power/snapshot.c:686",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:free_basic_memory_bitmaps",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947552,
      "name": "memory_bm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void memory_bm_free(struct memory_bitmap * bm, int clear_nosave_free)
```
</details>
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
