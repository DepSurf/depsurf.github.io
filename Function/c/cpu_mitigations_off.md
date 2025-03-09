# Function: <code>cpu_mitigations_off</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604716269,
      "name": "cpu_mitigations_off",
      "external": false,
      "loc": "include/linux/cpu.h:227",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604792036,
      "name": "cpu_mitigations_off",
      "external": false,
      "loc": "include/linux/cpu.h:227",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507472,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2412",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507472,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535728,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2543",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:srbds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v1_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535728,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517888,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2554",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:srbds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v1_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517888,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579521136,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2674",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521136,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592848,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2701",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592848,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684368,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2723",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684368,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807232,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2750",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807232,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855424,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:3147",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:srso_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855424,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893232,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:3229",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:rfds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:srso_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/arraymap.c:array_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893232,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490642664,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2412",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpu_errata.c:has_ssbd_mitigation",
        "arch/arm64/kernel/cpufeature.c:unmap_kernel_at_el0",
        "arch/arm64/kernel/cpufeature.c:unmap_kernel_at_el0"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490642664,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224718812,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2412",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224718812,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283461136,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2412",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup_64.c:setup_rfi_flush",
        "arch/powerpc/kernel/security.c:setup_count_cache_flush",
        "arch/powerpc/kernel/security.c:setup_stf_barrier",
        "arch/powerpc/kernel/security.c:setup_barrier_nospec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283461136,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271394938,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2412",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271394938,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481136,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2412",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481136,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410016,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2412",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410016,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481056,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2412",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481056,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool cpu_mitigations_off()
```

```json
{
  "name": "cpu_mitigations_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512912,
      "name": "cpu_mitigations_off",
      "external": true,
      "loc": "kernel/cpu.c:2412",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/mm/pti.c:pti_check_boottime_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512912,
      "name": "cpu_mitigations_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
bool cpu_mitigations_off()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
