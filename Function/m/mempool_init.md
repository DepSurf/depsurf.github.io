# Function: <code>mempool_init</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881152,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:225",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881152,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954464,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:226",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954464,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581049696,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049696,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105360,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105360,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288000,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288000,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332048,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:226",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332048,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351344,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:226",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351344,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581598608,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581598608,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956528,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:227",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bio-integrity.c:bioset_integrity_create",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956528,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582389056,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:233",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "fs/verity/hash_algs.c:fsverity_get_hash_alg",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bio-integrity.c:bioset_integrity_create",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582389056,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582594816,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:233",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bio-integrity.c:bioset_integrity_create",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582594816,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582766000,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:243",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_add_mark",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bio-integrity.c:bioset_integrity_create",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582766000,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492470928,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492470928,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226346980,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "block/bounce.c:init_emergency_pool",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226346980,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285753776,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285753776,
      "name": "mempool_init",
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272540398,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272540398,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074208,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074208,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021392,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021392,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065408,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065408,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
```

```json
{
  "name": "mempool_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126960,
      "name": "mempool_init",
      "external": true,
      "loc": "mm/mempool.c:228",
      "file": "mm/mempool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_init",
        "block/bounce.c:init_emergency_isa_pool",
        "drivers/md/dm-io.c:dm_io_client_create",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126960,
      "name": "mempool_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mempool_init(mempool_t * pool, int min_nr, mempool_alloc_t * alloc_fn, mempool_free_t * free_fn, void * pool_data)
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
