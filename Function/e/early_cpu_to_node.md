# Function: <code>early_cpu_to_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579111669,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:65",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179967,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:65",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595031587,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:65",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595068574,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:65",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_remove_cpu"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579111446,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180369,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595198074,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329093,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579109991,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190862,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595440963,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344437,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579101674,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189153,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596361780,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338469,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579113140,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204944,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602679609,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363909,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579119492,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216498,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602851076,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376517,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579125099,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240178,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604647900,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404181,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579134750,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254444,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604745639,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419589,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579136670,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256145,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604759038,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422757,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int early_cpu_to_node(int cpu)
```

```json
{
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579152535,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277509,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:announce_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288369,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem"
      ]
    },
    {
      "addr": 18446744071579453029,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288369,
      "name": "early_cpu_to_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579452336,
      "name": "early_cpu_to_node",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int early_cpu_to_node(int cpu)
```

```json
{
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579150183,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284885,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:announce_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591259256,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem"
      ]
    },
    {
      "addr": 18446744071579449957,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591259256,
      "name": "early_cpu_to_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579449264,
      "name": "early_cpu_to_node",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int early_cpu_to_node(int cpu)
```

```json
{
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156516,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287413,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:announce_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591202387,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem"
      ]
    },
    {
      "addr": 18446744071579452453,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202387,
      "name": "early_cpu_to_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579451760,
      "name": "early_cpu_to_node",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int early_cpu_to_node(int cpu)
```

```json
{
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579186573,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331413,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:announce_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592073348,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem"
      ]
    },
    {
      "addr": 18446744071579517765,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592073348,
      "name": "early_cpu_to_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071579516784,
      "name": "early_cpu_to_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int early_cpu_to_node(int cpu)
```

```json
{
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579234342,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392501,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:announce_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593839836,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_to_node",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance"
      ]
    },
    {
      "addr": 18446744071579601685,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu"
      ],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593839836,
      "name": "early_cpu_to_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071579600512,
      "name": "early_cpu_to_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579293574,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579470805,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:announce_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627646149,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_to_node",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627720533,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714501,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579300057,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579483813,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:announce_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619402674,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_to_node",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619478133,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579728133,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579329678,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514021,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:announce_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621697896,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_to_node",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621774741,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579763077,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510835104,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/arm64/mm/numa.c:144",
      "file": "arch/arm64/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/numa.c:pcpu_fc_alloc",
        "arch/arm64/mm/numa.c:pcpu_cpu_distance",
        "arch/arm64/mm/numa.c:pcpu_cpu_distance"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282364304,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/powerpc/include/asm/topology.h:53",
      "file": "arch/powerpc/kernel/setup_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/setup_64.c:pcpu_cpu_distance",
        "arch/powerpc/kernel/setup_64.c:pcpu_cpu_distance",
        "arch/powerpc/kernel/setup_64.c:pcpu_fc_alloc",
        "arch/powerpc/kernel/setup_64.c:alloc_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302396236,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/powerpc/include/asm/topology.h:53",
      "file": "arch/powerpc/kernel/paca.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/paca.c:alloc_paca_data"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579137054,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254849,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604685317,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418597,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579067811,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190081,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604652871,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579347733,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579136606,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256049,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604762901,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418517,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
  "name": "early_cpu_to_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579141726,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261617,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604763158,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_cpu_distance",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427573,
      "name": "early_cpu_to_node",
      "external": false,
      "loc": "arch/x86/include/asm/topology.h:56",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_remove_cpu",
        "arch/x86/mm/numa.c:numa_add_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int early_cpu_to_node(int cpu)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int early_cpu_to_node(int cpu)
```
</details>
</li>
</ul>
