# Function: <code>uv_local_mmr_address</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```

```json
{
  "name": "uv_local_mmr_address",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579293777,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:680",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    },
    {
      "addr": 18446744071579465445,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:680",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack"
      ],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu"
      ]
    },
    {
      "addr": 18446744071579470309,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:680",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474853,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:680",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293488,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579459056,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579473376,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```

```json
{
  "name": "uv_local_mmr_address",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609122492,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:626",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579486859,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:626",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack"
      ],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout",
        "arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout"
      ]
    },
    {
      "addr": 18446744071579492665,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:626",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497118,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:626",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476368,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579494848,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```

```json
{
  "name": "uv_local_mmr_address",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591261627,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect"
      ]
    },
    {
      "addr": 18446744071579475129,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479461,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591261627,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071579476976,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```

```json
{
  "name": "uv_local_mmr_address",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591204697,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect"
      ]
    },
    {
      "addr": 18446744071579477161,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579481313,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591204697,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579478960,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```

```json
{
  "name": "uv_local_mmr_address",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592075979,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect"
      ]
    },
    {
      "addr": 18446744071579542825,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547735,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592075979,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579545152,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```

```json
{
  "name": "uv_local_mmr_address",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593842573,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect"
      ]
    },
    {
      "addr": 18446744071579631554,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636531,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi"
      ],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593842573,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071579633840,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
  "name": "uv_local_mmr_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627681773,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746066,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753331,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:607",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs"
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
  "name": "uv_local_mmr_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619440661,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:613",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792610,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:613",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579800098,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:613",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs"
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
  "name": "uv_local_mmr_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621736741,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:613",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_mn",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect",
        "arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826290,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:613",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833719,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:613",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_check_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs"
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```

```json
{
  "name": "uv_local_mmr_address",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579299617,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:680",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    },
    {
      "addr": 18446744071579470773,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:680",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:read_status",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack"
      ],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu"
      ]
    },
    {
      "addr": 18446744071579475637,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:680",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_read_rtc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480179,
      "name": "uv_local_mmr_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:680",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299328,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579464576,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579478704,
      "name": "uv_local_mmr_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```
</details>
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
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
long unsigned int * uv_local_mmr_address(long unsigned int offset)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
