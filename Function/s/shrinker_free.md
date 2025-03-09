# Function: <code>shrinker_free</code>

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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void shrinker_free(struct shrinker * shrinker)
```

```json
{
  "name": "shrinker_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582924208,
      "name": "shrinker_free",
      "external": true,
      "loc": "mm/shrinker.c:767",
      "file": "mm/shrinker.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/workingset.c:workingset_init",
        "mm/zswap.c:zswap_pool_destroy",
        "mm/zswap.c:zswap_pool_create",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/huge_memory.c:hugepage_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/super.c:sget",
        "fs/super.c:sget",
        "fs/super.c:sget",
        "fs/super.c:sget_fc",
        "fs/super.c:sget_fc",
        "fs/super.c:sget_fc",
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:alloc_super",
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
      "addr": 18446744071582924208,
      "name": "shrinker_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void shrinker_free(struct shrinker * shrinker)
```
</details>
</li>
</ul>
