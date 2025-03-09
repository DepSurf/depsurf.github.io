# Function: <code>_raw_write_lock_irqsave</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587381376,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_remove",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "drivers/iommu/amd_iommu.c:protection_domain_free",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587381376,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587884336,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "security/apparmor/policy_ns.c:destroy_ns",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:protection_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884336,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588102640,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "security/apparmor/policy_ns.c:destroy_ns",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:domain_id_free",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588102640,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588328320,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/char/random.c:invalidate_batched_entropy",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:domain_id_free",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328320,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588894976,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:294",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/char/random.c:invalidate_batched_entropy",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_free",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:domain_id_free",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894976,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589273360,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:294",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/char/random.c:invalidate_batched_entropy",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589273360,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589516336,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:294",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/char/random.c:invalidate_batched_entropy",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589516336,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589975216,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589975216,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590202512,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590202512,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591218528,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591218528,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591713040,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591713040,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591660496,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591660496,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592834224,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:306",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592834224,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594745360,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:316",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594745360,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596498320,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:316",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596498320,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597035888,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:316",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/xen/events/events_base.c:xen_free_irq",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597035888,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597967856,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:316",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:label_merge_insert",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_sfp",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597967856,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236558236,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "sound/core/control.c:snd_ctl_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236558236,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297805344,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297805344,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279811276,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279811276,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589804800,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589804800,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589527072,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589527072,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590248208,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590248208,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590300128,
      "name": "_raw_write_lock_irqsave",
      "external": true,
      "loc": "kernel/locking/spinlock.c:301",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_labelset_destroy",
        "security/apparmor/label.c:aa_update_label_name",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_insert",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_replace",
        "security/apparmor/label.c:aa_label_remove",
        "drivers/scsi/sg.c:sg_remove_sfp",
        "drivers/scsi/sg.c:sg_remove_sfp_usercontext",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_get_rq_mark",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_unregister_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_driver",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590300128,
      "name": "_raw_write_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int _raw_write_lock_irqsave(rwlock_t * lock)
```
</details>
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
