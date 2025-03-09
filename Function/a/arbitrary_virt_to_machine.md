# Function: <code>arbitrary_virt_to_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578970688,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:134",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:load_TLS_descriptor",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970688,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967664,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:135",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:load_TLS_descriptor",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967664,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578969440,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:135",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:load_TLS_descriptor",
        "arch/x86/xen/mmu.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu.c:xen_set_pmd_hyper",
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969440,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578952656,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:22",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578952656,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578954896,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:22",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954896,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957440,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:22",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957440,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958064,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958064,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965040,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965040,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967504,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967504,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578976656,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976656,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578979264,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:map_ring_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979264,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578988384,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:map_ring_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988384,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579005136,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:map_ring_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579005136,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579021984,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:map_ring_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021984,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049920,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:map_ring_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049920,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049920,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:map_ring_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049920,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579075248,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:map_ring_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075248,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967504,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967504,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967440,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967440,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```

```json
{
  "name": "arbitrary_virt_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578968032,
      "name": "arbitrary_virt_to_machine",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:18",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_mfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry",
        "arch/x86/xen/enlighten_pv.c:load_TLS_descriptor",
        "arch/x86/xen/mmu_pv.c:xen_set_pud_hyper",
        "arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968032,
      "name": "arbitrary_virt_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
xmaddr_t arbitrary_virt_to_machine(void * vaddr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
