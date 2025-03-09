# Function: <code>ida_get_new_above</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ida_get_new_above(struct ida * ida, int starting_id, int * p_id)
```

```json
{
  "name": "ida_get_new_above",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952416,
      "name": "ida_get_new_above",
      "external": true,
      "loc": "lib/idr.c:932",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071582952416,
      "name": "ida_get_new_above",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int ida_get_new_above(struct ida * ida, int starting_id, int * p_id)
```

```json
{
  "name": "ida_get_new_above",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240032,
      "name": "ida_get_new_above",
      "external": true,
      "loc": "lib/idr.c:932",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071583240032,
      "name": "ida_get_new_above",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
int ida_get_new_above(struct ida * ida, int starting_id, int * p_id)
```

```json
{
  "name": "ida_get_new_above",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583355248,
      "name": "ida_get_new_above",
      "external": true,
      "loc": "lib/idr.c:935",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071583355248,
      "name": "ida_get_new_above",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
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
int ida_get_new_above(struct ida * ida, int start, int * id)
```

```json
{
  "name": "ida_get_new_above",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588203600,
      "name": "ida_get_new_above",
      "external": true,
      "loc": "lib/idr.c:250",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071588203600,
      "name": "ida_get_new_above",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 789
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
int ida_get_new_above(struct ida * ida, int start, int * id)
```

```json
{
  "name": "ida_get_new_above",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588752496,
      "name": "ida_get_new_above",
      "external": true,
      "loc": "lib/idr.c:258",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071588752496,
      "name": "ida_get_new_above",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 789
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
int ida_get_new_above(struct ida * ida, int start, int * id)
```

```json
{
  "name": "ida_get_new_above",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130832,
      "name": "ida_get_new_above",
      "external": true,
      "loc": "lib/idr.c:390",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071589130832,
      "name": "ida_get_new_above",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
<code>int start</code>
</li>
<li>
<b>Param added. </b>
<code>int * id</code>
</li>
<li>
<b>Param removed. </b>
<code>int starting_id</code>
</li>
<li>
<b>Param removed. </b>
<code>int * p_id</code>
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
int ida_get_new_above(struct ida * ida, int start, int * id)
```
</details>
</li>
</ul>
