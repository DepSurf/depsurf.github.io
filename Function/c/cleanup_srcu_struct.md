# Function: <code>cleanup_srcu_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * sp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777808,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcu.c:282",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/clk/clk.c:clk_notifier_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777808,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void cleanup_srcu_struct(struct srcu_struct * sp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803168,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcu.c:282",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/clk/clk.c:clk_notifier_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803168,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void cleanup_srcu_struct(struct srcu_struct * sp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831536,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcu.c:282",
      "file": "kernel/rcu/srcu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831536,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void cleanup_srcu_struct(struct srcu_struct * sp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831632,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:348",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_hctx",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831632,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void cleanup_srcu_struct(struct srcu_struct * sp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872256,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:349",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_hctx",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872256,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583621788,
      "name": "cleanup_srcu_struct",
      "external": false,
      "loc": "include/linux/srcu.h:84",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_exit_hctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585006681,
      "name": "cleanup_srcu_struct",
      "external": false,
      "loc": "include/linux/srcu.h:84",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_notifier_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587270782,
      "name": "cleanup_srcu_struct",
      "external": false,
      "loc": "include/linux/srcu.h:84",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:cleanup_mapped_device"
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
  "name": "cleanup_srcu_struct",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583728831,
      "name": "cleanup_srcu_struct",
      "external": false,
      "loc": "include/linux/srcu.h:84",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585113081,
      "name": "cleanup_srcu_struct",
      "external": false,
      "loc": "include/linux/srcu.h:84",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_notifier_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587451341,
      "name": "cleanup_srcu_struct",
      "external": false,
      "loc": "include/linux/srcu.h:84",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:cleanup_mapped_device"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998200,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071579992336,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048345,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580042448,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:383",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_module_notify",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103915,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580097600,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:372",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "kernel/rcu/srcutree.c:srcu_module_notify",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591305270,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580079136,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:375",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "kernel/rcu/srcutree.c:srcu_module_notify",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591248070,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580080704,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:367",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "kernel/rcu/srcutree.c:srcu_module_notify",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592141412,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580216608,
      "name": "cleanup_srcu_struct",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580376579,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:594",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "kernel/rcu/srcutree.c:srcu_module_notify",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-sysfs.c:blk_release_queue",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593912477,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580376512,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580604096,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:599",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "kernel/rcu/srcutree.c:srcu_module_notify",
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603664,
      "name": "cleanup_srcu_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071595990725,
      "name": "cleanup_srcu_struct.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580604096,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:644",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "kernel/rcu/srcutree.c:srcu_module_notify",
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/devfreq/devfreq.c:devfreq_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596508860,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580677824,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:646",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "kernel/rcu/srcutree.c:srcu_module_notify",
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/devfreq/devfreq.c:devfreq_dev_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597406598,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580744496,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491244040,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_put_kvm",
        "virt/kvm/kvm_main.c:kvm_put_kvm",
        "virt/kvm/kvm_main.c:kvm_create_vm",
        "virt/kvm/kvm_main.c:kvm_create_vm",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491244040,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225257108,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225257108,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284146016,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284146016,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271772522,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271772522,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/core.c:nvme_free_ns_head",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017081,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580011184,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/core.c:nvme_free_ns_head",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955749,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071579949936,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008617,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580002720,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```

```json
{
  "name": "cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055511,
      "name": "cleanup_srcu_struct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580050048,
      "name": "cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * sp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void cleanup_srcu_struct(struct srcu_struct * ssp)
```
</details>
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
