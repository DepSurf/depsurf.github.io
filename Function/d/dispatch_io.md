# Function: <code>dispatch_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dispatch_io(int rw, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585836496,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:362",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585836496,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586230880,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:365",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586230880,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 998
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586435568,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:379",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586435568,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1069
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586541216,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586541216,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1077
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587008688,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008688,
      "name": "dispatch_io",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587307072,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1099
    },
    {
      "addr": 18446744071587309218,
      "name": "dispatch_io.cold.9",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587487184,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
    },
    {
      "addr": 18446744071587489314,
      "name": "dispatch_io.cold.9",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587760800,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
    },
    {
      "addr": 18446744071587762978,
      "name": "dispatch_io.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965280,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    },
    {
      "addr": 18446744071587967490,
      "name": "dispatch_io.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588819712,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588819712,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588836384,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588836384,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588723440,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723440,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589412784,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589412784,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590889392,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:371",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590889392,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void dispatch_io(blk_opf_t opf, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592584800,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:372",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592584800,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void dispatch_io(blk_opf_t opf, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593015232,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:384",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593015232,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
void dispatch_io(blk_opf_t opf, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593766560,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:384",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593766560,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501207368,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501207368,
      "name": "dispatch_io",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233711560,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233711560,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294728896,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294728896,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277905738,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277905738,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587596256,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    },
    {
      "addr": 18446744071587598466,
      "name": "dispatch_io.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587364336,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    },
    {
      "addr": 18446744071587366546,
      "name": "dispatch_io.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587921424,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    },
    {
      "addr": 18446744071587923634,
      "name": "dispatch_io.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void dispatch_io(int op, int op_flags, unsigned int num_regions, struct dm_io_region * where, struct dpages * dp, struct io * io, int sync)
```

```json
{
  "name": "dispatch_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dispatch_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:390",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588036688,
      "name": "dispatch_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    },
    {
      "addr": 18446744071588038898,
      "name": "dispatch_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, num_regions, where, dp, io, sync</code> ➡️ <code>op, op_flags, num_regions, where, dp, io, sync</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, op_flags, num_regions, where, dp, io, sync</code> ➡️ <code>opf, num_regions, where, dp, io, sync</code>
</li>
</ul>
</details>
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
