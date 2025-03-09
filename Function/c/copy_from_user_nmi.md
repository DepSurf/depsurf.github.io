# Function: <code>copy_from_user_nmi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583004880,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:18",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:perf_callchain_user",
        "arch/x86/events/core.c:perf_callchain_user",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004880,
      "name": "copy_from_user_nmi.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071583004976,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583295312,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:18",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295312,
      "name": "copy_from_user_nmi.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071583295456,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583414064,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:18",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414064,
      "name": "copy_from_user_nmi.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071583414336,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271200,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:15",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271200,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588826944,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:15",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588826944,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589205008,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:17",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589205008,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446592,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:17",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446592,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589904496,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:17",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904496,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590130480,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:17",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130480,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585134736,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:17",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "kernel/events/core.c:perf_output_sample_ustack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585134736,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585286080,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:31",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585286080,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585169840,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:31",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585169840,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623536,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:31",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623536,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586782608,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:31",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782608,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595948992,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:32",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/utils.c:get_branch_type",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595948992,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596466448,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:32",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/utils.c:get_branch_type",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596466448,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597361472,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:32",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/utils.c:get_branch_type",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597361472,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589732736,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:17",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589732736,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458416,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:17",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458416,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590176112,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:17",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590176112,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```

```json
{
  "name": "copy_from_user_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590226560,
      "name": "copy_from_user_nmi",
      "external": true,
      "loc": "arch/x86/lib/usercopy.c:17",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip",
        "arch/x86/events/intel/lbr.c:branch_type",
        "kernel/events/core.c:perf_output_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590226560,
      "name": "copy_from_user_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int copy_from_user_nmi(void * to, const void * from, long unsigned int n)
```
</details>
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
