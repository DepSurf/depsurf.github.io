# Function: <code>bioset_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bioset_free(struct bio_set * bs)
```

```json
{
  "name": "bioset_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582714736,
      "name": "bioset_free",
      "external": true,
      "loc": "block/bio.c:1851",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bioset_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_free_md_mempools",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582714736,
      "name": "bioset_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void bioset_free(struct bio_set * bs)
```

```json
{
  "name": "bioset_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582991712,
      "name": "bioset_free",
      "external": true,
      "loc": "block/bio.c:1846",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bioset_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/dm.c:dm_free_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582991712,
      "name": "bioset_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void bioset_free(struct bio_set * bs)
```

```json
{
  "name": "bioset_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096656,
      "name": "bioset_free",
      "external": true,
      "loc": "block/bio.c:1893",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:__bioset_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/dm.c:dm_free_md_mempools",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096656,
      "name": "bioset_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void bioset_free(struct bio_set * bs)
```

```json
{
  "name": "bioset_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583153056,
      "name": "bioset_free",
      "external": true,
      "loc": "block/bio.c:1922",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153056,
      "name": "bioset_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void bioset_free(struct bio_set * bs)
```

```json
{
  "name": "bioset_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583328352,
      "name": "bioset_free",
      "external": true,
      "loc": "block/bio.c:1886",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bioset_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/md/md.c:md_stop",
        "drivers/md/md.c:md_stop",
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-io.c:dm_io_client_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328352,
      "name": "bioset_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
void bioset_free(struct bio_set * bs)
```
</details>
</li>
</ul>
