# Function: <code>cpu_sibling_mask</code>

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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
struct cpumask * cpu_sibling_mask(int cpu)
```

```json
{
  "name": "cpu_sibling_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282491944,
      "name": "cpu_sibling_mask",
      "external": false,
      "loc": "arch/powerpc/include/asm/smp.h:116",
      "file": "arch/powerpc/kernel/dbell.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/dbell.c:doorbell_try_core_ipi"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282515920,
      "name": "cpu_sibling_mask",
      "external": false,
      "loc": "arch/powerpc/include/asm/smp.h:116",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/smp.c:start_secondary",
        "arch/powerpc/kernel/smp.c:start_secondary",
        "arch/powerpc/kernel/smp.c:smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282832680,
      "name": "cpu_sibling_mask",
      "external": false,
      "loc": "arch/powerpc/include/asm/smp.h:116",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283384816,
      "name": "cpu_sibling_mask",
      "external": false,
      "loc": "arch/powerpc/include/asm/smp.h:116",
      "file": "arch/powerpc/perf/imc-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline",
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline",
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294859196,
      "name": "cpu_sibling_mask",
      "external": false,
      "loc": "arch/powerpc/include/asm/smp.h:116",
      "file": "drivers/cpufreq/powernv-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282506992,
      "name": "cpu_sibling_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
struct cpumask * cpu_sibling_mask(int cpu)
```
</details>
</li>
</ul>
