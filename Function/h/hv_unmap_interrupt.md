# Function: <code>hv_unmap_interrupt</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry * old_entry)
```

```json
{
  "name": "hv_unmap_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579054448,
      "name": "hv_unmap_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:72",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054448,
      "name": "hv_unmap_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry * old_entry)
```

```json
{
  "name": "hv_unmap_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579075344,
      "name": "hv_unmap_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:72",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075344,
      "name": "hv_unmap_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry * old_entry)
```

```json
{
  "name": "hv_unmap_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100672,
      "name": "hv_unmap_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:72",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100672,
      "name": "hv_unmap_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry * old_entry)
```

```json
{
  "name": "hv_unmap_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579137264,
      "name": "hv_unmap_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:72",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137264,
      "name": "hv_unmap_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry * old_entry)
```

```json
{
  "name": "hv_unmap_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138160,
      "name": "hv_unmap_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:72",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138160,
      "name": "hv_unmap_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry * old_entry)
```

```json
{
  "name": "hv_unmap_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579164960,
      "name": "hv_unmap_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:72",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_unmap_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_msi_free_irq",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164960,
      "name": "hv_unmap_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int hv_unmap_interrupt(u64 id, struct hv_interrupt_entry * old_entry)
```
</details>
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
