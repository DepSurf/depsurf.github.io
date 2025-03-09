# Function: <code>opal_error_code</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int opal_error_code(int rc)
```

```json
{
  "name": "opal_error_code",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282971312,
      "name": "opal_error_code",
      "external": true,
      "loc": "arch/powerpc/platforms/powernv/opal.c:1111",
      "file": "arch/powerpc/platforms/powernv/opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal.c:opal_flush_chars",
        "arch/powerpc/platforms/powernv/opal.c:opal_flush_console",
        "arch/powerpc/platforms/powernv/opal.c:__opal_put_chars",
        "arch/powerpc/platforms/powernv/opal-sysparam.c:sys_param_store",
        "arch/powerpc/platforms/powernv/opal-sysparam.c:sys_param_show",
        "arch/powerpc/platforms/powernv/opal-sysparam.c:sys_param_show",
        "arch/powerpc/platforms/powernv/opal-sensor.c:opal_get_sensor_data",
        "arch/powerpc/platforms/powernv/opal-sensor.c:opal_get_sensor_data",
        "arch/powerpc/platforms/powernv/opal-powercap.c:powercap_store",
        "arch/powerpc/platforms/powernv/opal-powercap.c:powercap_store",
        "arch/powerpc/platforms/powernv/opal-powercap.c:powercap_show",
        "arch/powerpc/platforms/powernv/opal-powercap.c:powercap_show",
        "arch/powerpc/platforms/powernv/opal-psr.c:psr_store",
        "arch/powerpc/platforms/powernv/opal-psr.c:psr_store",
        "arch/powerpc/platforms/powernv/opal-psr.c:psr_show",
        "arch/powerpc/platforms/powernv/opal-psr.c:psr_show",
        "arch/powerpc/platforms/powernv/opal-sensor-groups.c:sensor_group_enable",
        "arch/powerpc/platforms/powernv/pci.c:pnv_pci_set_tunnel_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282971312,
      "name": "opal_error_code",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int opal_error_code(int rc)
```
</details>
</li>
</ul>
