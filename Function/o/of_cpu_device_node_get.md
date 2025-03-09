# Function: <code>of_cpu_device_node_get</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct device_node * of_cpu_device_node_get(int cpu)
```

```json
{
  "name": "of_cpu_device_node_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501278232,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511266532,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/cpufreq/cpufreq-dt-platdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501338764,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/cpuidle/dt_idle_states.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501340060,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/cpuidle/cpuidle-psci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle-psci.c:psci_idle_init",
        "drivers/cpuidle/cpuidle-psci.c:psci_idle_init"
      ]
    },
    {
      "addr": 18446603336501609232,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_cpu_node_to_id",
        "drivers/of/base.c:of_cpu_node_to_id"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501340060,
      "name": "of_cpu_device_node_get",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
struct device_node * of_cpu_device_node_get(int cpu)
```

```json
{
  "name": "of_cpu_device_node_get",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243268092,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "arch/arm/kernel/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/cpuidle.c:arm_cpuidle_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230892064,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/soc/qcom/spm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/spm.c:spm_dev_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233766624,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3243917060,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/cpufreq/cpufreq-dt-platdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3233811948,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/cpufreq/tegra124-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233830992,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/cpuidle/dt_idle_states.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver",
        "drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 3233832972,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/cpuidle/cpuidle-psci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle-psci.c:psci_idle_init",
        "drivers/cpuidle/cpuidle-psci.c:psci_idle_init"
      ]
    },
    {
      "addr": 3234133372,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_cpu_node_to_id",
        "drivers/of/base.c:of_cpu_node_to_id"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233832972,
      "name": "of_cpu_device_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "of_cpu_device_node_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294801356,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295035736,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_cpu_node_to_id",
        "drivers/of/base.c:of_cpu_node_to_id"
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
  "name": "of_cpu_device_node_get",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271349154,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "arch/riscv/kernel/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves",
        "arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves",
        "arch/riscv/kernel/cacheinfo.c:_init_cache_level",
        "arch/riscv/kernel/cacheinfo.c:_init_cache_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277952286,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/opp/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278074628,
      "name": "of_cpu_device_node_get",
      "external": false,
      "loc": "include/linux/of_device.h:49",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_find_last_cache_level",
        "drivers/of/base.c:of_cpu_node_to_id",
        "drivers/of/base.c:of_cpu_node_to_id"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct device_node * of_cpu_device_node_get(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * of_cpu_device_node_get(int cpu)
```
</details>
</li>
</ul>
