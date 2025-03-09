# Function: <code>unregister_shrinker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580549408,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:255",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:exit_mbcache",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549408,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641376,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:269",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641376,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580708160,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:296",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708160,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580742736,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:297",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742736,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580830256,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:298",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830256,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580967376,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:346",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967376,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044368,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:436",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044368,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581108384,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:448",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108384,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165376,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:446",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165376,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581350544,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:403",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350544,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393952,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:396",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393952,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581413632,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:627",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413632,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581664400,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:673",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664400,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582039376,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:670",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039376,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582482256,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:742",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482256,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582687488,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:794",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582687488,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492540760,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:446",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492540760,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226408084,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:446",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226408084,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285843456,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:446",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285843456,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272592038,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:446",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272592038,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581134224,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:446",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134224,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581081168,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:446",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081168,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125424,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:446",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125424,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void unregister_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "unregister_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581187936,
      "name": "unregister_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:446",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:deactivate_locked_super",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/ext4/extents_status.c:ext4_es_unregister_shrinker",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187936,
      "name": "unregister_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void unregister_shrinker(struct shrinker * shrinker)
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
