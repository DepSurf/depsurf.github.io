# Function: <code>cea_set_pte</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602715531,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:27",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/traps.c:trap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348944,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579360608,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:27",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/traps.c:trap_init",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360608,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388128,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:29",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/traps.c:trap_init",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388128,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403632,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:29",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/traps.c:trap_init",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403632,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406816,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:29",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/traps.c:trap_init",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406816,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417408,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:33",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417408,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417440,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:34",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/sev-es.c:setup_vc_stacks",
        "arch/x86/kernel/sev-es.c:setup_vc_stacks",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417440,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420528,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:34",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420528,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579484080,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:34",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484080,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563392,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:34",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563392,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671040,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:72",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671040,
      "name": "cea_set_pte",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684992,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:79",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684992,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719504,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:79",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719504,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402656,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:29",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/traps.c:trap_init",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402656,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579332096,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:29",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/traps.c:trap_init",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579332096,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402576,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:29",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/traps.c:trap_init",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402576,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```

```json
{
  "name": "cea_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411440,
      "name": "cea_set_pte",
      "external": true,
      "loc": "arch/x86/mm/cpu_entry_area.c:29",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:ds_clear_cea",
        "arch/x86/events/intel/ds.c:ds_update_cea",
        "arch/x86/kernel/traps.c:trap_init",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas",
        "arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411440,
      "name": "cea_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```
</details>
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
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cea_set_pte(void * cea_vaddr, phys_addr_t pa, pgprot_t flags)
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
