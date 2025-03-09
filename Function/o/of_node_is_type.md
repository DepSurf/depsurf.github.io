# Function: <code>of_node_is_type</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "of_node_is_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501635532,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "drivers/of/address.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "of_node_is_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234162344,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "drivers/of/address.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
bool of_node_is_type(const struct device_node * np, const char * type)
```

```json
{
  "name": "of_node_is_type",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282338472,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "arch/powerpc/kernel/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282359744,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "arch/powerpc/kernel/setup-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/setup-common.c:check_legacy_ioport"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282591692,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "arch/powerpc/kernel/legacy_serial.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports"
      ]
    },
    {
      "addr": 13835058055282604240,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "arch/powerpc/kernel/isa-bridge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/isa-bridge.c:isa_bridge_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282618416,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "arch/powerpc/kernel/pci_of_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev",
        "arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev",
        "arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282829296,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283141400,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "arch/powerpc/platforms/pseries/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/setup.c:pSeries_probe",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch",
        "arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch"
      ]
    },
    {
      "addr": 13835058055283191720,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "arch/powerpc/platforms/pseries/hotplug-memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_notifier",
        "arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283216420,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "arch/powerpc/platforms/pseries/vio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/vio.c:vio_find_node",
        "arch/powerpc/platforms/pseries/vio.c:vio_find_node",
        "arch/powerpc/platforms/pseries/vio.c:vio_register_device_node",
        "arch/powerpc/platforms/pseries/vio.c:vio_register_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295078100,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "drivers/of/address.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282591692,
      "name": "of_node_is_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 13835058055283141400,
      "name": "of_node_is_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
  "name": "of_node_is_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278095296,
      "name": "of_node_is_type",
      "external": false,
      "loc": "include/linux/of.h:1027",
      "file": "drivers/of/address.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
bool of_node_is_type(const struct device_node * np, const char * type)
```
</details>
</li>
</ul>
