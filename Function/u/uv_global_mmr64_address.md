# Function: <code>uv_global_mmr64_address</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_global_mmr64_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292815,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:650",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604837036,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:650",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:read_gmmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_gmmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_last",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_first"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579469689,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:650",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579470570,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:650",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
volatile void * uv_global_mmr64_address(int pnode, long unsigned int offset)
```

```json
{
  "name": "uv_global_mmr64_address",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579321567,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:596",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480400,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:596",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:read_gmmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_gmmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_last",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_first"
      ],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:pq_init",
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control"
      ]
    },
    {
      "addr": 18446744071579492182,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:596",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579492830,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:596",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476080,
      "name": "uv_global_mmr64_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_global_mmr64_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579325028,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474727,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579475348,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr"
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
  "name": "uv_global_mmr64_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579327748,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579476797,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579477380,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr"
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
  "name": "uv_global_mmr64_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579382441,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579542428,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_irq.c:uv_program_mmr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579543076,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr"
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
  "name": "uv_global_mmr64_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579447613,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579631120,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_irq.c:uv_program_mmr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579631732,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr"
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
  "name": "uv_global_mmr64_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579534525,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579745568,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_irq.c:uv_program_mmr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746260,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:577",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr"
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
  "name": "uv_global_mmr64_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579547437,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:583",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792112,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:583",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_irq.c:uv_program_mmr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792804,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:583",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr"
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
  "name": "uv_global_mmr64_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579575717,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:583",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825796,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:583",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579826483,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:583",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_global_mmr64_address",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579298655,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:650",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604841193,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:650",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:enable_timeouts",
        "arch/x86/platform/uv/tlb_uv.c:read_gmmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_gmmr_proc_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_last",
        "arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_first"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579475017,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:650",
      "file": "arch/x86/platform/uv/uv_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579475898,
      "name": "uv_global_mmr64_address",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:650",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr",
        "arch/x86/platform/uv/uv_time.c:uv_setup_intr"
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
volatile void * uv_global_mmr64_address(int pnode, long unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
volatile void * uv_global_mmr64_address(int pnode, long unsigned int offset)
```
</details>
</li>
</ul>
