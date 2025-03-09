# Function: <code>__vmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580742368,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1719",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_init_module",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvmalloc",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742368,
      "name": "__vmalloc",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861536,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1740",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:SYSC_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/file.c:alloc_fdmem",
        "fs/ext4/super.c:ext4_kvmalloc",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861536,
      "name": "__vmalloc",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931840,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1753",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:SYSC_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/file.c:alloc_fdmem",
        "fs/ext4/super.c:ext4_kvmalloc",
        "drivers/md/dm-ioctl.c:ctl_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931840,
      "name": "__vmalloc",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976112,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1816",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:SYSC_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "kernel/bpf/syscall.c:bpf_map_area_alloc",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976112,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078688,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1808",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:SYSC_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078688,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581217632,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1795",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217632,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581301312,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1801",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301312,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378480,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2549",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378480,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581439680,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2557",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439680,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648576,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2600",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648576,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694960,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2633",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694960,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716816,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2980",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:nh_notifier_res_table_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716816,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989056,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3086",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989056,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582413280,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3243",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "kernel/module/main.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/util.c:vcalloc",
        "mm/util.c:__vcalloc",
        "mm/util.c:vmalloc_array",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413280,
      "name": "__vmalloc",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * __vmalloc(long unsigned int size, gfp_t gfp_mask)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582920896,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3305",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "kernel/module/main.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/util.c:vcalloc",
        "mm/util.c:__vcalloc",
        "mm/util.c:vmalloc_array",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582920896,
      "name": "__vmalloc",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void * __vmalloc(long unsigned int size, gfp_t gfp_mask)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583137056,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3398",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "kernel/module/main.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/util.c:vcalloc",
        "mm/util.c:__vcalloc",
        "mm/util.c:vmalloc_array",
        "drivers/block/virtio_blk.c:virtblk_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137056,
      "name": "__vmalloc",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void * __vmalloc(long unsigned int size, gfp_t gfp_mask)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320176,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3398",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "kernel/module/main.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/util.c:vcalloc",
        "mm/util.c:__vcalloc",
        "mm/util.c:vmalloc_array",
        "drivers/block/virtio_blk.c:virtblk_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "net/ipv4/nexthop.c:nexthop_create_group",
        "net/ipv4/nexthop.c:nh_notifier_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320176,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492843576,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2557",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492843576,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226650128,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2557",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__se_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc",
        "sound/core/pcm_memory.c:_snd_pcm_lib_alloc_vmalloc_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226650128,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286232336,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2557",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286232336,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272795112,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2557",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272795112,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581408528,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2557",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408528,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351040,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2557",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351040,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399728,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2557",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399728,
      "name": "__vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void * __vmalloc(long unsigned int size, gfp_t gfp_mask, pgprot_t prot)
```

```json
{
  "name": "__vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463712,
      "name": "__vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2557",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "kernel/groups.c:groups_alloc",
        "kernel/module.c:__do_sys_init_module",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats",
        "mm/page_alloc.c:alloc_large_system_hash",
        "fs/ext4/super.c:ext4_kvzalloc",
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463712,
      "name": "__vmalloc",
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pgprot_t prot</code>
</li>
</ul>
</details>
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
