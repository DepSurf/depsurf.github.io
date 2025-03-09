# Function: <code>opal_message_notifier_register</code>

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
int opal_message_notifier_register(enum opal_msg_type msg_type, struct notifier_block * nb)
```

```json
{
  "name": "opal_message_notifier_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282972304,
      "name": "opal_message_notifier_register",
      "external": true,
      "loc": "arch/powerpc/platforms/powernv/opal.c:244",
      "file": "arch/powerpc/platforms/powernv/opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-async.c:opal_async_comp_init",
        "arch/powerpc/platforms/powernv/opal-hmi.c:opal_hmi_handler_init",
        "arch/powerpc/platforms/powernv/opal-power.c:opal_power_control_init",
        "arch/powerpc/platforms/powernv/opal-power.c:opal_power_control_init",
        "arch/powerpc/platforms/powernv/opal-power.c:opal_power_control_init",
        "arch/powerpc/platforms/powernv/opal-memory-errors.c:__machine_initcall_powernv_opal_mem_err_init",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282972304,
      "name": "opal_message_notifier_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int opal_message_notifier_register(enum opal_msg_type msg_type, struct notifier_block * nb)
```
</details>
</li>
</ul>
