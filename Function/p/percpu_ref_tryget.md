# Function: <code>percpu_ref_tryget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579980253,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:206",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580526016,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:206",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580610963,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:206",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580928283,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:206",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580030870,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:204",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580610256,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:204",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714419,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:204",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581074746,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:204",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067779,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:204",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580065043,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:204",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580677504,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:204",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580780259,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:204",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150364,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:204",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583175603,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:204",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580060381,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:205",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580709570,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:205",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817739,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:205",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581197494,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:205",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235267,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:205",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580111164,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:206",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580795090,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:206",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907931,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:206",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327446,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:206",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583413763,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:206",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580170339,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:212",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932760,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:212",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044400,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:212",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475717,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:212",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583625596,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:212",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580218243,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:213",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009345,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:213",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581121770,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:213",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558114,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:213",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583662386,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:213",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583726220,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:213",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583748691,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:213",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583838853,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:213",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580267006,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580285948,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580308739,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072465,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186003,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684622,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581991691,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188730,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_submit_sqe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583850450,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583914748,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583937732,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584029012,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580315309,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580334172,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580357619,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128449,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581240400,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581757486,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769300,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582075684,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268630,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583949778,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584017964,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584041204,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584132937,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580386695,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406924,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580430595,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315917,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429421,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581981151,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989334,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311699,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514194,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_show_fdinfo",
        "fs/io_uring.c:__do_sys_io_uring_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584340396,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_associate_blkg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584413943,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436913,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584530390,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:251",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580373755,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580394232,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580418199,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357243,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472648,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582031378,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:get_obj_cgroup_from_current",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582039349,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582364726,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574360,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_show_fdinfo",
        "fs/io_uring.c:__do_sys_io_uring_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584529623,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584553313,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640235,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591180207,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_create_socket"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580376676,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397176,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580420967,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581374154,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492792,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582058114,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:uncharge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582065461,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582392374,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582640667,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_uring_show_fdinfo",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_req_complete_post"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584561074,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584586148,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584668209,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591116364,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_create_socket"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580537937,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559709,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584279,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622610,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581753619,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cleanup_offline_cgwbs_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582366109,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:uncharge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582375031,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713957,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582968691,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_uring_show_fdinfo",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_req_complete_post"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584972198,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585000612,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585084577,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591961998,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_create_socket"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580735331,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746988,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580758974,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580785386,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581986267,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135691,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cleanup_offline_cgwbs_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673185,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582866559,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:__get_obj_cgroup_from_memcg",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582874820,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258175,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585678580,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585714178,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585810973,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594115947,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_show_fdinfo",
        "io_uring/io_uring.c:__do_sys_io_uring_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593689784,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_create_socket"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581011443,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024140,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581037374,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069242,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752997,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581942663,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_kptr_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582105253,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:alloc_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582422372,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582524914,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:run_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612955,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cleanup_offline_cgwbs_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583203073,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583413862,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:__get_obj_cgroup_from_memcg",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583423282,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583839916,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586456351,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586494498,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586592685,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586822438,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "io_uring/fdinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/fdinfo.c:io_uring_show_fdinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595622938,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_create_socket"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581100003,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112508,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125726,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159658,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912581,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582127400,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_ancestor",
        "kernel/bpf/helpers.c:bpf_cgroup_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303522,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags",
        "kernel/bpf/memalloc.c:alloc_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582627588,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582728592,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:shrink_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582821723,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cleanup_offline_cgwbs_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583418689,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583634134,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:__get_obj_cgroup_from_memcg",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583643682,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584057999,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586654744,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586707811,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_rq_poll",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586742082,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586850894,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587088982,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "io_uring/fdinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/fdinfo.c:io_uring_show_fdinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596131278,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_create_socket"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581197427,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213325,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:task_get_cgroup1",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581224222,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265205,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582037429,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582268504,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_ancestor",
        "kernel/bpf/helpers.c:bpf_cgroup_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582457509,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582799476,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582898192,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:shrink_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997819,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cleanup_offline_cgwbs_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583089645,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_test_recent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583387208,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583502472,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:zswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583829062,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:get_obj_cgroup_from_folio",
        "mm/memcontrol.c:current_objcg_update",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_current",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583838557,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584273134,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586926005,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586980931,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_rq_poll",
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587014162,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128208,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597004966,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:264",
      "file": "net/mptcp/subflow.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/subflow.c:mptcp_subflow_create_socket"
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
bool percpu_ref_tryget(struct percpu_ref * ref)
```

```json
{
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491568492,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491596704,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491616872,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492500576,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492639384,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493211152,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_get_cache"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ]
    },
    {
      "addr": 18446603336493225716,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493607568,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493849224,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_enter",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495773568,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495855224,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495875896,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495982688,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493189688,
      "name": "percpu_ref_tryget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225533236,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 3225556196,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 3225573520,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3226373384,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 3226482420,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226841468,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3227152436,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 3227349556,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 3229123420,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_associate_blkg"
      ],
      "caller_func": []
    },
    {
      "addr": 3229200052,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3229221732,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3229323372,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284548064,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284581072,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284609776,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285787536,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285954592,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286721000,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286741088,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287195008,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287465784,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289943696,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290043752,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290077204,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290207664,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271981850,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272001930,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272018542,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272560934,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272654766,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272987762,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272999442,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273255456,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273419640,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274916386,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274977846,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274998992,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275082476,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580284109,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580302972,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580326419,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097297,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209248,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581726222,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738036,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582044420,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582237366,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583918514,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583986700,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009940,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584101673,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580231517,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580250316,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580273683,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044465,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581156000,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581665006,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676676,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981972,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582175110,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583855474,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583922556,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945764,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584037353,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580275357,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580294220,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580317667,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088497,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200448,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581717534,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729348,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582035700,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582227846,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583902274,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583970460,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583993700,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584085433,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
  "name": "percpu_ref_tryget",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580329058,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580348590,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580372570,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150834,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264767,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581785247,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581797658,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107212,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582308176,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584003450,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584072588,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584096004,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188222,
      "name": "percpu_ref_tryget",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:221",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
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
bool percpu_ref_tryget(struct percpu_ref * ref)
```
</details>
</li>
</ul>
