# Function: <code>bitmap_fill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579128924,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595042323,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272998,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "arch/x86/kernel/vsmp_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579564404,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595093833,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595106228,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init_current_mems_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580210963,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978909,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_setup_first_chunk",
        "mm/percpu.c:pcpu_setup_first_chunk"
      ]
    },
    {
      "addr": 18446744071595246989,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585851825,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586781886,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586872788,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587014191,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:191",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978909,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579129111,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595208240,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272230,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/vsmp_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579574650,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595261864,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595275887,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580245803,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133788,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_setup_first_chunk",
        "mm/percpu.c:pcpu_setup_first_chunk"
      ]
    },
    {
      "addr": 18446744071595428586,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586251360,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587233786,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825066,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587461170,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581133788,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579136295,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595451136,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287673,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "arch/x86/kernel/vsmp_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579600233,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595507163,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580609206,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init",
        "kernel/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580288646,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208334,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_setup_first_chunk",
        "mm/percpu.c:pcpu_setup_first_chunk"
      ]
    },
    {
      "addr": 18446744071595680866,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586456139,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587434330,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588039620,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587664674,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:201",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609206,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071581208334,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579134391,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596371979,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284617,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "arch/x86/kernel/vsmp_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596427486,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580092966,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580301942,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830594,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_setup_first_chunk",
        "mm/percpu.c:pcpu_setup_first_chunk"
      ]
    },
    {
      "addr": 18446744071583680483,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596605360,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580715,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587570181,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663243,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587823760,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588227923,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:200",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092966,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071580830594,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579149320,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602752375,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580146036,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580355062,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602805466,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583935687,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602935713,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587063995,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588093969,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588188875,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588353581,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588777892,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:210",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free_cmn",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146036,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579159240,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602924881,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580205620,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580416772,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602978775,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584125646,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071603108465,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587362214,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588447534,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588539794,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588710974,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589156902,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:212",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205620,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604722813,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580257892,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580472436,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604778755,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584210014,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587542086,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588641153,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588738644,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588930421,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589386838,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589429751,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257892,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604823603,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580308919,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580528011,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604874185,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584398702,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587816710,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589053192,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589170597,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589372929,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589843976,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589887455,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:221",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580308919,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604857952,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580357799,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580576856,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604908091,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584529394,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588021910,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589277703,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589395221,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589597361,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590070078,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590113407,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357799,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609188417,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580430775,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580678239,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609225343,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585067153,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585117217,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585189766,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588881894,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589886519,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590255093,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/devinet.c:rtm_to_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590382677,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590603646,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:241",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580430775,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612254764,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591315436,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580563530,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580669064,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612292472,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764138,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585216481,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585266209,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585348950,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588894710,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589925822,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590307989,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/devinet.c:rtm_to_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590440245,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590664366,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315436,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579184273,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_set",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614396430,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591257621,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580566634,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580667784,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614433366,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582793087,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585099387,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585149345,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585233142,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588783718,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589833648,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590223757,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/devinet.c:rtm_to_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590365749,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590589937,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:239",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257621,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579218321,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_set",
        "arch/x86/kernel/cpu/mce/core.c:mce_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615330560,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592161861,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580736671,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580842560,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615373793,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583117350,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585547547,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585601149,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585688438,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589475974,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590596558,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591006413,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/devinet.c:rtm_to_ifaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591158199,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591402593,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:245",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592161861,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579270151,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_set",
        "arch/x86/kernel/cpu/mce/core.c:mce_end"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_set",
        "arch/x86/kernel/cpu/mce/core.c:mce_end"
      ]
    },
    {
      "addr": 18446744071617114282,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593934922,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580949037,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581060127,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915849,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617162239,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583601013,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586703424,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586758894,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586855430,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617316230,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590955403,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592187817,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592216479,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592652777,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592816854,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593078846,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593711558,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:244",
      "file": "net/mptcp/pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm.c:mptcp_pm_data_reset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593831514,
      "name": "bitmap_fill.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071593934922,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579333975,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_set",
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_set",
        "arch/x86/kernel/cpu/mce/core.c:mce_end",
        "arch/x86/kernel/cpu/mce/core.c:mce_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627780523,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627805807,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581243389,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581365567,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582351033,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627847472,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584206293,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588000422,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628038213,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592657899,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594046456,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594519556,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594689524,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594973141,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595646246,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/mptcp/pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm.c:mptcp_pm_data_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595865232,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595919016,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_create"
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
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579342775,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_set",
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_set",
        "arch/x86/kernel/cpu/mce/core.c:mce_end",
        "arch/x86/kernel/cpu/mce/core.c:mce_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619543403,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619568655,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581338564,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581461217,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374037,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_setall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553929,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619624288,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436095,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588275110,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619803701,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593088635,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594424808,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594911666,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595081428,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595365895,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596155041,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "net/mptcp/pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm.c:mptcp_pm_data_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596382576,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596437189,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:250",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_create"
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
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579373623,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_set",
        "arch/x86/kernel/cpu/mce/core.c:fake_panic_set",
        "arch/x86/kernel/cpu/mce/core.c:mce_end",
        "arch/x86/kernel/cpu/mce/core.c:mce_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621842315,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:init_irq_default_affinity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621845155,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_nocb_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621871679,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445524,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581570472,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541365,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_setall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582724505,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621928432,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588567750,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622111749,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593841003,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595227055,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595723412,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595894212,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596206911,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597029009,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "net/mptcp/pm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/pm.c:mptcp_pm_data_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597277824,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597332549,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:227",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_split",
        "lib/xarray.c:xas_create"
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
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/arm64/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490352580,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/arm64/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/context.c:check_and_switch_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510891484,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491618480,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446603336491875032,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510945720,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496633208,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496705372,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501290052,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501322956,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/cpufreq/cpufreq-dt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq-dt.c:cpufreq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501779372,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/perf/arm_pmu_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe",
        "drivers/perf/arm_pmu_platform.c:pmu_parse_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502907820,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503039972,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503274340,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503848020,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503894588,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491618480,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/arm/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243379788,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225573844,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 3225817872,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 3243435804,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 3229941256,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3229998164,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233786608,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3233809200,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/cpufreq/cpufreq-dt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq-dt.c:cpufreq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3234328840,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/perf/arm_pmu_platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe",
        "drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235600824,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 3235729164,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 3235944500,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 3236467620,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 3236524052,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225573844,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302446160,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:shared_proc_topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282839836,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/powerpc/mm/slice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/slice.c:slice_init_new_context_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283328900,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/powerpc/kvm/book3s_hv_rm_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055302525948,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284610104,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 13835058055284950792,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302594400,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290792288,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294828388,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296574736,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296743316,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297017164,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297702416,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297763232,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284610104,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271360042,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/riscv/mm/cacheflush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/cacheflush.c:flush_icache_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270649372,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272167214,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270675234,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275467864,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_allocate_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279002744,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279106210,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279297732,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279737616,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279780156,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604762968,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580326599,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580545656,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604813551,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584486322,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587646902,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588883879,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589000501,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589201729,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589672334,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589715663,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326599,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604730840,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579982633,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nocb_setup"
      ]
    },
    {
      "addr": 18446744071580273863,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580492488,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604782612,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584424450,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587420774,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588595815,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588723557,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588926721,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589398158,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589441439,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982633,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580273863,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604840596,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580317847,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580536904,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604890735,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584481058,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587978054,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589320263,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589436885,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589638593,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590115710,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590159039,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317847,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```

```json
{
  "name": "bitmap_fill",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604862093,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580372839,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init",
        "kernel/cgroup/cpuset.c:cpuset_init"
      ]
    },
    {
      "addr": 18446744071580593384,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_open_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604912272,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc_first_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584587154,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588093430,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589362135,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:inetdev_event",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:devinet_ioctl",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:inet_rtm_newaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589481477,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_init_vif_indev",
        "net/ipv4/ipmr.c:ipmr_init_vif_indev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589687579,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:ipv6_add_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590166094,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:idr_get_free",
        "lib/radix-tree.c:radix_tree_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590209679,
      "name": "bitmap_fill",
      "external": false,
      "loc": "include/linux/bitmap.h:225",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_create",
        "lib/xarray.c:xas_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580372839,
      "name": "bitmap_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void bitmap_fill(long unsigned int * dst, unsigned int nbits)
```
</details>
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
