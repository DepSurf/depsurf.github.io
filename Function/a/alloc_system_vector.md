# Function: <code>alloc_system_vector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void alloc_system_vector(int vector)
```

```json
{
  "name": "alloc_system_vector",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579356119,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:382",
      "file": "arch/x86/kernel/irqinit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ"
      ]
    },
    {
      "addr": 18446744071579169645,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:382",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583866241,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:382",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356119,
      "name": "alloc_system_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void alloc_system_vector(int vector)
```

```json
{
  "name": "alloc_system_vector",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362884,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:382",
      "file": "arch/x86/kernel/irqinit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ"
      ]
    },
    {
      "addr": 18446744071579169980,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:382",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584196864,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:382",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362884,
      "name": "alloc_system_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void alloc_system_vector(int vector)
```

```json
{
  "name": "alloc_system_vector",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579380823,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:382",
      "file": "arch/x86/kernel/irqinit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ"
      ]
    },
    {
      "addr": 18446744071579180220,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:382",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584378322,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:382",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380823,
      "name": "alloc_system_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void alloc_system_vector(int vector)
```

```json
{
  "name": "alloc_system_vector",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579044193,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:489",
      "file": "arch/x86/kernel/irqinit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ",
        "arch/x86/kernel/irqinit.c:native_init_IRQ"
      ]
    },
    {
      "addr": 18446744071579178972,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:489",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584459712,
      "name": "alloc_system_vector",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:489",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044193,
      "name": "alloc_system_vector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void alloc_system_vector(int vector)
```
</details>
</li>
</ul>
