# Function: <code>set_cpu_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_cpu_present(unsigned int cpu, bool present)
```

```json
{
  "name": "set_cpu_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579377472,
      "name": "set_cpu_present",
      "external": true,
      "loc": "kernel/cpu.c:790",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info",
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377472,
      "name": "set_cpu_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595149969,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:735",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579171622,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:735",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595195770,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:735",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:smp_init_package_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191061,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:735",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595247119,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:735",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584173573,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:735",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595393180,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:740",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181718,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:740",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202579,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:740",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595491263,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:740",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584354967,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:740",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596312390,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:783",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180646,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:783",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200328,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:783",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596412355,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:783",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436518,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:783",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602629949,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:787",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196118,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:787",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216049,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:787",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602737086,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:787",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584844938,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:787",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602798565,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:789",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208025,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:789",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228070,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:789",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602909551,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:789",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585075738,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:789",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604592645,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:801",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231609,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:801",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251766,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:801",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604707166,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:801",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585185370,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:801",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604688289,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:800",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244937,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:800",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265743,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:800",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604807507,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:800",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585397979,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:800",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604700724,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247129,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267391,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604841807,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585538715,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609048964,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:835",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_filter_cpu_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271625,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:835",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294994,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:835",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609176428,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:835",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586256551,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:835",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:enable_hotplug_cpu"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612112308,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_filter_cpu_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279049,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301042,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612241862,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586374615,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:enable_hotplug_cpu"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614252122,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:812",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281817,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:812",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303906,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:812",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614382362,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:812",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586259331,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:812",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615172736,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:812",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325028,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:812",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579351634,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:812",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615315191,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:812",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586769907,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:812",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_cpu_present(unsigned int cpu, bool present)
```

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593815980,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:838",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ]
    },
    {
      "addr": 18446744071579384852,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:838",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413554,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:838",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617096983,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:838",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588047909,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:838",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593815980,
      "name": "set_cpu_present",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627544837,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:947",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462100,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:947",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495752,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:947",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627757656,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:947",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589426643,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:947",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619291114,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:999",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474676,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:999",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579507903,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:999",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619518232,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:999",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589725795,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:999",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621583672,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:1019",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579505439,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:1019",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530740,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:1019",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:cpu_update_apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621815240,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:1019",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590063779,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:1019",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu",
        "drivers/xen/cpu_hotplug.c:disable_hotplug_cpu"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510823716,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:smp_prepare_cpus",
        "arch/arm64/kernel/smp.c:smp_prepare_cpus",
        "arch/arm64/kernel/smp.c:cpu_die_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510874240,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498198028,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243347672,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/arm/mach-qcom/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-qcom/platsmp.c:qcom_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3243360884,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3234031124,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "drivers/firmware/qcom_scm-32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_set_cold_boot_addr"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302390580,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/powerpc/kernel/setup-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283187964,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/powerpc/platforms/pseries/hotplug-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302504068,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270611756,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/riscv/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/smpboot.c:smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270616546,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604627012,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245977,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266095,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604747074,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585300747,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579181417,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201535,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604714691,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604704820,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247033,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267295,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604824641,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489115,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
  "name": "set_cpu_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604704836,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252601,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272895,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604845964,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585597115,
      "name": "set_cpu_present",
      "external": false,
      "loc": "include/linux/cpumask.h:830",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void set_cpu_present(unsigned int cpu, bool present)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void set_cpu_present(unsigned int cpu, bool present)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void set_cpu_present(unsigned int cpu, bool present)
```
</details>
</li>
</ul>
