# Function: <code>percpu_ref_tryget_live</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579983869,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_get_e_css",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:css_tryget_online_from_dir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580000029,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "kernel/cgroup_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580011568,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580526252,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580921345,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580947161,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182899,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582715858,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_associate_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582751208,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_enter",
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582874945,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579309504,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580030436,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032974,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "kernel/cgroup_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047546,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:proc_cpuset_show",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541242,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580610491,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580765251,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026727,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581089755,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581096631,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581346391,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992815,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_associate_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583033177,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583160830,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579324717,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064612,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067326,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "kernel/cgroup_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580086964,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:proc_cpuset_show",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605274,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580677739,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830831,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101878,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581165524,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581171863,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425319,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583097759,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_associate_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583138123,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272894,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:238",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580059941,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580068423,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580070719,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580073831,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580092723,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580635334,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580709987,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880081,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151909,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213242,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220100,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479637,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583154059,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_associate_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583195119,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328069,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:239",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580110709,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580121047,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123455,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580126583,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580145779,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717947,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580795513,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964895,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273057,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581343790,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350740,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393552,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_devmem_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621829,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583372379,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511317,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:240",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580169909,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580180618,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580182853,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580187104,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580205378,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849843,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:get_dev_pagemap",
        "kernel/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932991,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491313,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499085,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542288,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_devmem_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780649,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935858,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583581898,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583726794,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:246",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580217829,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580228682,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580231188,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580234393,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580257668,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580917837,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009566,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577170,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584921,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867433,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582018046,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583692477,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583836109,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:247",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580266259,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580277015,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580281972,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580306224,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548491,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688482,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695938,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738173,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582154736,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583881138,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584026089,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580314563,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580325159,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580330196,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580355088,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613371,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761919,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581811693,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231952,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583984290,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584129988,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580384593,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580398345,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580402562,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580428176,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833220,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581983249,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582032029,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582469774,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584369981,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584458499,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_map_sector_rcu",
        "block/genhd.c:disk_map_sector_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527736,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:271",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580371551,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580385753,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580389869,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580415662,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033716,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582080345,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582527002,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582608427,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_grab_identity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584486100,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584637063,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580374559,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580388697,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580392797,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580417262,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582057267,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582105420,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582555789,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520740,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584664183,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580535705,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580550793,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554877,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580581304,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070661,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582365280,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421548,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871917,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584925140,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_try_enter_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585079790,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580733092,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580749282,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580753856,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580782277,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582510551,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582862927,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937156,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583436009,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806864,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581008979,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026626,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581031664,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581065374,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583029439,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583410318,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496240,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:zone_device_page_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584025753,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586588409,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581097571,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114978,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120036,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155742,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583239039,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583630574,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711248,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:zone_device_page_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584250425,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586845605,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592869039,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_handle_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581194995,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cgroup_tryget_css",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581212930,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581218324,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581261112,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583473567,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:get_swap_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496170,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:shrink_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583825366,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583911616,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:zone_device_page_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584466889,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587122930,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593620107,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:306",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_handle_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool percpu_ref_tryget_live(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491538588,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir"
      ]
    },
    {
      "addr": 18446603336491583340,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491591652,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491614532,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493062676,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493189848,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ]
    },
    {
      "addr": 18446603336493809572,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495809236,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495979236,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491532360,
      "name": "percpu_ref_tryget_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446603336493189848,
      "name": "percpu_ref_tryget_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225531912,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 3225545252,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3225551468,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3225571492,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 3226769360,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226846996,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3227315556,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 3229160912,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3229320760,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284546656,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284565124,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284574368,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284606724,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286497296,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286728704,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286807224,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287422976,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289995316,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290203424,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271980904,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271992554,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271997922,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272016636,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272924802,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272992188,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273388214,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274946908,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275079796,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580283363,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293959,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580298996,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580323888,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582107,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730655,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780429,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582200688,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583953026,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584098724,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580230771,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580241319,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580246340,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271162,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523660,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669407,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581718589,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138336,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583889954,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584035156,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580274611,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580285207,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580290244,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580315136,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573419,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721967,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771741,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582191168,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583936786,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584082484,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget_live",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580328122,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580339138,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580344530,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580370268,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638568,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581790101,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581840628,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582267933,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584038680,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584185752,
      "name": "percpu_ref_tryget_live",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:255",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
bool percpu_ref_tryget_live(struct percpu_ref * ref)
```
</details>
</li>
</ul>
