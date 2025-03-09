# Function: <code>ida_pre_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ida_pre_get(struct ida * ida, gfp_t gfp_mask)
```

```json
{
  "name": "ida_pre_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582952944,
      "name": "ida_pre_get",
      "external": true,
      "loc": "lib/idr.c:896",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:mnt_alloc_group_id",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/proc/generic.c:proc_alloc_inum",
        "fs/devpts/inode.c:devpts_new_index",
        "lib/idr.c:ida_simple_get",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/scsi/sd.c:sd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952944,
      "name": "ida_pre_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ida_pre_get(struct ida * ida, gfp_t gfp_mask)
```

```json
{
  "name": "ida_pre_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583240560,
      "name": "ida_pre_get",
      "external": true,
      "loc": "lib/idr.c:896",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/namespace.c:mnt_alloc_group_id",
        "fs/proc/generic.c:proc_alloc_inum",
        "fs/devpts/inode.c:devpts_new_index",
        "lib/idr.c:ida_simple_get",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240560,
      "name": "ida_pre_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ida_pre_get(struct ida * ida, gfp_t gfp_mask)
```

```json
{
  "name": "ida_pre_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583355872,
      "name": "ida_pre_get",
      "external": true,
      "loc": "lib/idr.c:896",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/namespace.c:mnt_alloc_group_id",
        "fs/proc/generic.c:proc_alloc_inum",
        "fs/devpts/inode.c:devpts_new_index",
        "lib/idr.c:ida_simple_get",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/mmc/core/host.c:mmc_alloc_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583355872,
      "name": "ida_pre_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ida_pre_get(struct ida * ida, gfp_t gfp)
```

```json
{
  "name": "ida_pre_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588222288,
      "name": "ida_pre_get",
      "external": true,
      "loc": "lib/radix-tree.c:2119",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/namespace.c:mnt_alloc_group_id",
        "fs/devpts/inode.c:devpts_new_index",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/scsi/sd.c:sd_probe",
        "lib/idr.c:ida_simple_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588222288,
      "name": "ida_pre_get",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ida_pre_get(struct ida * ida, gfp_t gfp)
```

```json
{
  "name": "ida_pre_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588772352,
      "name": "ida_pre_get",
      "external": true,
      "loc": "lib/radix-tree.c:2116",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/namespace.c:mnt_alloc_group_id",
        "fs/devpts/inode.c:devpts_new_index",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/scsi/sd.c:sd_probe",
        "lib/idr.c:ida_simple_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772352,
      "name": "ida_pre_get",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ida_pre_get(struct ida * ida, gfp_t gfp)
```

```json
{
  "name": "ida_pre_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589151600,
      "name": "ida_pre_get",
      "external": true,
      "loc": "lib/radix-tree.c:2117",
      "file": "lib/radix-tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:get_anon_bdev",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/namespace.c:mnt_alloc_group_id",
        "fs/devpts/inode.c:devpts_new_index",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/scsi/sd.c:sd_probe",
        "lib/idr.c:ida_simple_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151600,
      "name": "ida_pre_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int ida_pre_get(struct ida * ida, gfp_t gfp)
```
</details>
</li>
</ul>
