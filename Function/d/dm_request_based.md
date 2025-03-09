# Function: <code>dm_request_based</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585799913,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm.c:1788",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_attr_rq_based_seq_io_merge_deadline_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804768,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586249600,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:61",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586249600,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586454400,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:57",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586454400,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586559440,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:57",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586559440,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587026976,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:57",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026976,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587325456,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:57",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587325456,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587504512,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:44",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587504512,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587778528,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587778528,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587983200,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983200,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588837648,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588837648,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588853920,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588853920,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588741008,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588741008,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589431456,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431456,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590909536,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:59",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590909536,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592606208,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:58",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592606208,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593036784,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:59",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593036784,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593788160,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:59",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593788160,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501227376,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501227376,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233731356,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233731356,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294755520,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294755520,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277922096,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277922096,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587614176,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587614176,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587382192,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382192,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587939344,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587939344,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int dm_request_based(struct mapped_device * md)
```

```json
{
  "name": "dm_request_based",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588054624,
      "name": "dm_request_based",
      "external": true,
      "loc": "drivers/md/dm-rq.c:60",
      "file": "drivers/md/dm-rq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588054624,
      "name": "dm_request_based",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
