# Function: <code>hv_map_interrupt</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_map_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_map_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:15",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055104,
      "name": "hv_map_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
    },
    {
      "addr": 18446744071591187159,
      "name": "hv_map_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_map_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_map_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:15",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075984,
      "name": "hv_map_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
    },
    {
      "addr": 18446744071592050310,
      "name": "hv_map_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_map_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_map_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:15",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579101216,
      "name": "hv_map_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
    },
    {
      "addr": 18446744071593816777,
      "name": "hv_map_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_map_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138192,
      "name": "hv_map_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:15",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138192,
      "name": "hv_map_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
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
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_map_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_map_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:15",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138736,
      "name": "hv_map_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
    },
    {
      "addr": 18446744071596475374,
      "name": "hv_map_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry * entry)
```

```json
{
  "name": "hv_map_interrupt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_map_interrupt",
      "external": false,
      "loc": "arch/x86/hyperv/irqdomain.c:15",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_map_ioapic_interrupt",
        "arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579165200,
      "name": "hv_map_interrupt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071597370882,
      "name": "hv_map_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int hv_map_interrupt(union hv_device_id device_id, bool level, int cpu, int vector, struct hv_interrupt_entry * entry)
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
