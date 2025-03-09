# Function: <code>md_bitmap_get_counter</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587426976,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1353",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587426976,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587699120,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1354",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587699120,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587903408,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1354",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587903408,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588753568,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1349",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588753568,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588773808,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1350",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588773808,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588661216,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1350",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588661216,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1350",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589339104,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071592645944,
      "name": "md_bitmap_get_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1351",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590808176,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071594530086,
      "name": "md_bitmap_get_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1351",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592494448,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071596310367,
      "name": "md_bitmap_get_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1410",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592924416,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071596839734,
      "name": "md_bitmap_get_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1414",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593675072,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071597763877,
      "name": "md_bitmap_get_counter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501130272,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1354",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501130272,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233639796,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1354",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233639796,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294637312,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1354",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294637312,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277848312,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1354",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277848312,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587534384,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1354",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587534384,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587302528,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1354",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587302528,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587859552,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1354",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587859552,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "md_bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587972976,
      "name": "md_bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1354",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:md_bitmap_start_sync",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972976,
      "name": "md_bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bitmap_counter_t * md_bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
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
