# Function: <code>idr_alloc_cmn</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int idr_alloc_cmn(struct idr * idr, void * ptr, long unsigned int * index, long unsigned int start, long unsigned int end, gfp_t gfp, bool ext)
```

```json
{
  "name": "idr_alloc_cmn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588751616,
      "name": "idr_alloc_cmn",
      "external": true,
      "loc": "lib/idr.c:10",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:tcf_idr_create",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588751616,
      "name": "idr_alloc_cmn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int idr_alloc_cmn(struct idr * idr, void * ptr, long unsigned int * index, long unsigned int start, long unsigned int end, gfp_t gfp, bool ext)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int idr_alloc_cmn(struct idr * idr, void * ptr, long unsigned int * index, long unsigned int start, long unsigned int end, gfp_t gfp, bool ext)
```
</details>
</li>
</ul>
