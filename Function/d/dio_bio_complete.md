# Function: <code>dio_bio_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243456,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:465",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243456,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410496,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:474",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410496,
      "name": "dio_bio_complete",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491168,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:477",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491168,
      "name": "dio_bio_complete",
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546048,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:478",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546048,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689104,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:517",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689104,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581851792,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851792,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939504,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939504,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582077040,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:539",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077040,
      "name": "dio_bio_complete",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582154480,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154480,
      "name": "dio_bio_complete",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391408,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:519",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582391408,
      "name": "dio_bio_complete",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582445088,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:500",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445088,
      "name": "dio_bio_complete",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582472080,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:502",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472080,
      "name": "dio_bio_complete",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:502",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582785152,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071592233218,
      "name": "dio_bio_complete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:492",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583337728,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071594013451,
      "name": "dio_bio_complete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:492",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583920432,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071596053257,
      "name": "dio_bio_complete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:498",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153952,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071596577686,
      "name": "dio_bio_complete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:498",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_send_cur_page",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584368144,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071597481737,
      "name": "dio_bio_complete.cold",
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493707520,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493707520,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227234296,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227234296,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287312064,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287312064,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273322828,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273322828,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123216,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123216,
      "name": "dio_bio_complete",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582060656,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582060656,
      "name": "dio_bio_complete",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582113696,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582113696,
      "name": "dio_bio_complete",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
blk_status_t dio_bio_complete(struct dio * dio, struct bio * bio)
```

```json
{
  "name": "dio_bio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582186656,
      "name": "dio_bio_complete",
      "external": false,
      "loc": "fs/direct-io.c:538",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186656,
      "name": "dio_bio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
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
