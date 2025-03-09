# Function: <code>ida_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ida_remove(struct ida * ida, int id)
```

```json
{
  "name": "ida_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582950544,
      "name": "ida_remove",
      "external": true,
      "loc": "lib/idr.c:1010",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_anon_bdev",
        "fs/super.c:free_anon_bdev",
        "fs/namespace.c:cleanup_group_ids",
        "fs/proc/generic.c:proc_alloc_inum",
        "fs/proc/generic.c:proc_free_inum",
        "fs/devpts/inode.c:devpts_new_index",
        "fs/devpts/inode.c:devpts_kill_index",
        "lib/idr.c:ida_simple_get",
        "drivers/iommu/iommu.c:iommu_group_release",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "net/core/net_namespace.c:unregister_pernet_operations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950544,
      "name": "ida_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void ida_remove(struct ida * ida, int id)
```

```json
{
  "name": "ida_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238208,
      "name": "ida_remove",
      "external": true,
      "loc": "lib/idr.c:1010",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:free_anon_bdev",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:cleanup_group_ids",
        "fs/proc/generic.c:proc_free_inum",
        "fs/proc/generic.c:proc_alloc_inum",
        "fs/devpts/inode.c:devpts_kill_index",
        "fs/devpts/inode.c:devpts_new_index",
        "lib/idr.c:ida_simple_get",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/mmc/core/host.c:mmc_host_classdev_release",
        "net/core/net_namespace.c:unregister_pernet_operations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238208,
      "name": "ida_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void ida_remove(struct ida * ida, int id)
```

```json
{
  "name": "ida_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353360,
      "name": "ida_remove",
      "external": true,
      "loc": "lib/idr.c:1013",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:free_anon_bdev",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:cleanup_group_ids",
        "fs/proc/generic.c:proc_free_inum",
        "fs/proc/generic.c:proc_alloc_inum",
        "fs/devpts/inode.c:devpts_kill_index",
        "fs/devpts/inode.c:devpts_new_index",
        "lib/idr.c:ida_simple_get",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/mmc/core/host.c:mmc_host_classdev_release",
        "net/core/net_namespace.c:unregister_pernet_operations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353360,
      "name": "ida_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void ida_remove(struct ida * ida, int id)
```

```json
{
  "name": "ida_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588204624,
      "name": "ida_remove",
      "external": true,
      "loc": "lib/idr.c:346",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:free_anon_bdev",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:cleanup_group_ids",
        "fs/devpts/inode.c:devpts_kill_index",
        "fs/devpts/inode.c:devpts_new_index",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:chan_dev_release",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "lib/idr.c:ida_simple_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588204624,
      "name": "ida_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void ida_remove(struct ida * ida, int id)
```

```json
{
  "name": "ida_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588753520,
      "name": "ida_remove",
      "external": true,
      "loc": "lib/idr.c:354",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:free_anon_bdev",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:cleanup_group_ids",
        "fs/devpts/inode.c:devpts_kill_index",
        "fs/devpts/inode.c:devpts_new_index",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:chan_dev_release",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "lib/idr.c:ida_simple_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588753520,
      "name": "ida_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
void ida_remove(struct ida * ida, int id)
```

```json
{
  "name": "ida_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589131792,
      "name": "ida_remove",
      "external": true,
      "loc": "lib/idr.c:484",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:free_anon_bdev",
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:cleanup_group_ids",
        "fs/devpts/inode.c:devpts_kill_index",
        "fs/devpts/inode.c:devpts_new_index",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:chan_dev_release",
        "drivers/scsi/sd.c:scsi_disk_release",
        "drivers/scsi/sd.c:sd_probe",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "lib/idr.c:ida_simple_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589131792,
      "name": "ida_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void ida_remove(struct ida * ida, int id)
```
</details>
</li>
</ul>
