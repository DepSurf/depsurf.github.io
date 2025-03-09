# Function: <code>sync_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585837837,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:404",
      "file": "drivers/md/dm-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:dm_io"
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
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586232369,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:407",
      "file": "drivers/md/dm-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:dm_io"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586436640,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:421",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586436640,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586542304,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586542304,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009840,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009840,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587308176,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587308176,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587488272,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587488272,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587761968,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071587762995,
      "name": "sync_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587966448,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966448,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588820016,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588820016,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588836688,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588836688,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588723744,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723744,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589413088,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589413088,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590889712,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:413",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590889712,
      "name": "sync_io",
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, blk_opf_t opf, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592585136,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:414",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592585136,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, blk_opf_t opf, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593015568,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:426",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593015568,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, blk_opf_t opf, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593766896,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:426",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593766896,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501208376,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501208376,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233713188,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:dm_io"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294730352,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294730352,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277906700,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277906700,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587597424,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587597424,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587365504,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587365504,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587922592,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922592,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```

```json
{
  "name": "sync_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588037856,
      "name": "sync_io",
      "external": false,
      "loc": "drivers/md/dm-io.c:432",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588037856,
      "name": "sync_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```
</details>
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
<code>client, num_regions, where, op, op_flags, dp, error_bits</code> ➡️ <code>client, num_regions, where, opf, dp, error_bits</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int sync_io(struct dm_io_client * client, unsigned int num_regions, struct dm_io_region * where, int op, int op_flags, struct dpages * dp, long unsigned int * error_bits)
```
</details>
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
