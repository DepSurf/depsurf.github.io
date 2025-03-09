# Function: <code>llist_add_batch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031392,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:38",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:generic_exec_single",
        "kernel/smp.c:smp_call_function_many",
        "kernel/irq_work.c:irq_work_queue_on",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031392,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323840,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:38",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/irq_work.c:irq_work_queue_on",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323840,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583448752,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:38",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448752,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469376,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:38",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469376,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583650320,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:38",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583650320,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868400,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:38",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868400,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953680,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:38",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953680,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584133488,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/namespace.c:mntput_no_expire",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133488,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255888,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/namespace.c:mntput_no_expire",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255888,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584663616,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/hugetlb.c:free_huge_page",
        "fs/namespace.c:mntput_no_expire",
        "fs/io_uring.c:io_file_data_ref_zero",
        "fs/io_uring.c:io_file_data_ref_zero",
        "drivers/tty/tty_buffer.c:tty_buffer_free",
        "drivers/iommu/amd/iommu.c:alloc_dev_data",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663616,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780976,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/rcu/tree.c:fill_page_cache_func",
        "kernel/rcu/tree.c:kfree_rcu_work",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/hugetlb.c:free_huge_page",
        "fs/namespace.c:mntput_no_expire",
        "fs/io_uring.c:io_file_data_ref_zero",
        "drivers/tty/tty_buffer.c:tty_buffer_free",
        "drivers/iommu/amd/iommu.c:alloc_dev_data",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780976,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584825008,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/rcu/tree.c:fill_page_cache_func",
        "kernel/rcu/tree.c:kfree_rcu_work",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "fs/namespace.c:mntput_no_expire",
        "fs/io_uring.c:io_rsrc_node_ref_zero",
        "drivers/tty/tty_buffer.c:tty_buffer_free",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584825008,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585243312,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/rcu/tree.c:fill_page_cache_func",
        "kernel/rcu/tree.c:kfree_rcu_work",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "fs/namespace.c:mntput_no_expire",
        "fs/io_uring.c:io_rsrc_node_ref_zero",
        "fs/io_uring.c:io_req_task_work_add",
        "drivers/tty/tty_buffer.c:tty_buffer_free",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585243312,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586084464,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/rcu/tree.c:fill_page_cache_func",
        "kernel/rcu/tree.c:kfree_rcu_work",
        "kernel/module/main.c:do_init_module",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:generic_exec_single",
        "kernel/irq_work.c:__irq_work_queue_local",
        "kernel/irq_work.c:__irq_work_queue_local",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "fs/namespace.c:mntput_no_expire",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "io_uring/io_uring.c:io_rsrc_node_ref_zero",
        "io_uring/io_uring.c:__io_req_task_work_add",
        "drivers/tty/tty_buffer.c:tty_buffer_free",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586084464,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587067056,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/rcu/tree.c:fill_page_cache_func",
        "kernel/rcu/tree.c:kfree_rcu_work",
        "kernel/module/main.c:do_init_module",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:generic_exec_single",
        "kernel/irq_work.c:__irq_work_queue_local",
        "kernel/irq_work.c:__irq_work_queue_local",
        "kernel/bpf/memalloc.c:unit_free",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "fs/namespace.c:mntput_no_expire",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-cgroup.c:blk_cgroup_bio_start",
        "io_uring/io_uring.c:__io_req_task_work_add",
        "io_uring/io_uring.c:__io_req_task_work_add",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/rsrc.c:io_rsrc_node_ref_zero",
        "drivers/tty/tty_buffer.c:tty_buffer_free",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587067056,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587325632,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/rcu/tree.c:fill_page_cache_func",
        "kernel/rcu/tree.c:kvfree_rcu_bulk",
        "kernel/module/main.c:do_init_module",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:__smp_call_single_queue",
        "kernel/bpf/memalloc.c:unit_free",
        "mm/vmalloc.c:vfree_atomic",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "fs/namespace.c:mntput_no_expire",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-cgroup.c:blk_cgroup_bio_start",
        "io_uring/io_uring.c:io_req_normal_work_add",
        "io_uring/io_uring.c:io_fallback_tw",
        "drivers/tty/tty_buffer.c:tty_buffer_free",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587325632,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587608576,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/rcu/tree.c:fill_page_cache_func",
        "kernel/rcu/tree.c:kvfree_rcu_bulk",
        "kernel/module/main.c:do_init_module",
        "kernel/smp.c:smp_call_function_many_cond",
        "kernel/smp.c:__smp_call_single_queue",
        "kernel/bpf/memalloc.c:unit_free_rcu",
        "kernel/bpf/memalloc.c:unit_free",
        "kernel/bpf/memalloc.c:bpf_mem_refill",
        "kernel/bpf/memalloc.c:bpf_mem_refill",
        "kernel/bpf/memalloc.c:__free_by_rcu",
        "mm/vmalloc.c:vfree_atomic",
        "mm/memory-failure.c:__get_huge_page_for_hwpoison",
        "fs/namespace.c:mntput_no_expire",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-mq.c:blk_mq_complete_request_remote",
        "block/blk-cgroup.c:blk_cgroup_bio_start",
        "io_uring/io_uring.c:io_req_normal_work_add",
        "io_uring/io_uring.c:io_fallback_tw",
        "drivers/tty/tty_buffer.c:tty_buffer_free",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/gpu/drm/drm_connector.c:__drm_connector_put_safe",
        "net/core/net_namespace.c:netns_install",
        "net/core/net_namespace.c:netns_put",
        "net/core/net_namespace.c:rtnl_net_dumpid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_getid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587608576,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496134432,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/namespace.c:mntput_no_expire",
        "drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496134432,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229457588,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/namespace.c:mntput_no_expire",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229457588,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290391680,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/namespace.c:mntput_no_expire",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290391680,
      "name": "llist_add_batch",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275192088,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/namespace.c:mntput_no_expire",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275192088,
      "name": "llist_add_batch",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224624,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/namespace.c:mntput_no_expire",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224624,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159840,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/namespace.c:mntput_no_expire",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159840,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208384,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/namespace.c:mntput_no_expire",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208384,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool llist_add_batch(struct llist_node * new_first, struct llist_node * new_last, struct llist_head * head)
```

```json
{
  "name": "llist_add_batch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312944,
      "name": "llist_add_batch",
      "external": true,
      "loc": "lib/llist.c:26",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_prepare_records",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/smp.c:smp_call_function_many",
        "kernel/smp.c:generic_exec_single",
        "kernel/module.c:do_init_module",
        "kernel/irq_work.c:irq_work_queue_on",
        "mm/vmalloc.c:__vfree",
        "mm/vmalloc.c:vfree_atomic",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "fs/namespace.c:mntput_no_expire",
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312944,
      "name": "llist_add_batch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
