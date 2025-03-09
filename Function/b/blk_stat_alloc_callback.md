# Function: <code>blk_stat_alloc_callback</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583253696,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:136",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253696,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583433040,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:105",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583433040,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583644080,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:101",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583644080,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750832,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:101",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750832,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583939904,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:102",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939904,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584043376,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:102",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584043376,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584439152,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:103",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584439152,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584555968,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:103",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555968,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584588768,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:103",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588768,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585003376,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:103",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003376,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717920,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:103",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717920,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586498464,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:103",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586498464,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586746080,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:103",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586746080,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587018256,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:103",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587018256,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495878608,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:102",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495878608,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229224220,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:102",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229224220,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290080512,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:102",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290080512,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275001168,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:102",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275001168,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584012112,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:102",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012112,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947936,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:102",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947936,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995872,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:102",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995872,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```

```json
{
  "name": "blk_stat_alloc_callback",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584098224,
      "name": "blk_stat_alloc_callback",
      "external": true,
      "loc": "block/blk-stat.c:102",
      "file": "block/blk-stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-wbt.c:wbt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584098224,
      "name": "blk_stat_alloc_callback",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct blk_stat_callback * blk_stat_alloc_callback(void (*)(struct blk_stat_callback *) timer_fn, int (*)(const struct request *) bucket_fn, unsigned int buckets, void * data)
```
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
