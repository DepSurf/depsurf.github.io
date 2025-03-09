# Function: <code>hv_do_hypercall</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
u64 hv_do_hypercall(u64 control, void * input, void * output)
```

```json
{
  "name": "hv_do_hypercall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579024288,
      "name": "hv_do_hypercall",
      "external": true,
      "loc": "arch/x86/hyperv/hv_init.c:203",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024288,
      "name": "hv_do_hypercall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
u64 hv_do_hypercall(u64 control, void * input, void * output)
```

```json
{
  "name": "hv_do_hypercall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579016672,
      "name": "hv_do_hypercall",
      "external": true,
      "loc": "arch/x86/hyperv/hv_init.c:184",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579016672,
      "name": "hv_do_hypercall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hv_do_hypercall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579019156,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:179",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579022236,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:128",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024647,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:128",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579025295,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:140",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579027985,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:140",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579028938,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:140",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579033683,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035505,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036168,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579036003,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037825,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038488,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579045706,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:67",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047626,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:67",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047992,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:67",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579049146,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:82",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579050970,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:82",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051320,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:82",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614255221,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:48",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051990,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:48",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053887,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:48",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054543,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:48",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056508,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:48",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579059625,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:48",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615175261,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:46",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_get_partition_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072878,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:46",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074797,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:46",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075439,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:46",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078154,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:46",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579080777,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:46",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728230,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:46",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616940792,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:39",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_get_partition_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097997,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:39",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100033,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:39",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100758,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:39",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104136,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:39",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106222,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:39",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579109148,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:39",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591237147,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:39",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv_common.c:hv_query_ext_cap"
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627548315,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:37",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_get_partition_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134392,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:37",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136581,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:37",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137360,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:37",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141318,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:37",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142887,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:37",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579146722,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:37",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592988827,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:37",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv_common.c:hv_query_ext_cap"
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619294651,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:54",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_get_partition_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134990,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:54",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137477,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:54",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138256,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:54",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142258,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:54",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143513,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:54",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579147282,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:54",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593440395,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:54",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv_common.c:hv_query_ext_cap"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u64 hv_do_hypercall(u64 control, void * input, void * output)
```

```json
{
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:71",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_get_partition_id"
      ]
    },
    {
      "addr": 0,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:71",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ]
    },
    {
      "addr": 0,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:71",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ]
    },
    {
      "addr": 0,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:71",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ]
    },
    {
      "addr": 0,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:71",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility",
        "arch/x86/hyperv/ivm.c:hv_snp_boot_ap"
      ]
    },
    {
      "addr": 0,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:71",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:71",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ]
    },
    {
      "addr": 0,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:71",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/hv_common.c:hv_query_ext_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153344,
      "name": "hv_do_hypercall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071597370509,
      "name": "hv_do_hypercall.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579160416,
      "name": "hv_do_hypercall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071597370660,
      "name": "hv_do_hypercall.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579163152,
      "name": "hv_do_hypercall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071597370798,
      "name": "hv_do_hypercall.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579164592,
      "name": "hv_do_hypercall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071597370840,
      "name": "hv_do_hypercall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579169088,
      "name": "hv_do_hypercall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    },
    {
      "addr": 18446744071597371027,
      "name": "hv_do_hypercall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579172096,
      "name": "hv_do_hypercall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071597371143,
      "name": "hv_do_hypercall.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579175024,
      "name": "hv_do_hypercall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071597371240,
      "name": "hv_do_hypercall.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071594186624,
      "name": "hv_do_hypercall.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071597774091,
      "name": "hv_do_hypercall.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579036355,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038177,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038840,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578968992,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970974,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971650,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587559146,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "drivers/hv/hv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv.c:hv_post_message"
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579035939,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037761,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038424,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
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
  "name": "hv_do_hypercall",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579039532,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041377,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042072,
      "name": "hv_do_hypercall",
      "external": false,
      "loc": "arch/x86/include/asm/mshyperv.h:74",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
u64 hv_do_hypercall(u64 control, void * input, void * output)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
u64 hv_do_hypercall(u64 control, void * input, void * output)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
u64 hv_do_hypercall(u64 control, void * input, void * output)
```
</details>
</li>
</ul>
