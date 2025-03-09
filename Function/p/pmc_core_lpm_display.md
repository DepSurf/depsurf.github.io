# Function: <code>pmc_core_lpm_display</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pmc_core_lpm_display(struct pmc_dev * pmcdev, struct device * dev, struct seq_file * s, u32 offset, const char * str, const struct pmc_bit_map * * maps)
```

```json
{
  "name": "pmc_core_lpm_display",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589086688,
      "name": "pmc_core_lpm_display",
      "external": false,
      "loc": "drivers/platform/x86/intel_pmc_core.c:654",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_l_sts_regs_show",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_sts_regs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589086688,
      "name": "pmc_core_lpm_display",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void pmc_core_lpm_display(struct pmc_dev * pmcdev, struct device * dev, struct seq_file * s, u32 offset, const char * str, const struct pmc_bit_map * * maps)
```

```json
{
  "name": "pmc_core_lpm_display",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmc_core_lpm_display",
      "external": false,
      "loc": "drivers/platform/x86/intel_pmc_core.c:666",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_l_sts_regs_show",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_sts_regs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589087552,
      "name": "pmc_core_lpm_display",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071591613542,
      "name": "pmc_core_lpm_display.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void pmc_core_lpm_display(struct pmc_dev * pmcdev, struct device * dev, struct seq_file * s, u32 offset, const char * str, const struct pmc_bit_map * * maps)
```

```json
{
  "name": "pmc_core_lpm_display",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmc_core_lpm_display",
      "external": false,
      "loc": "drivers/platform/x86/intel_pmc_core.c:832",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_l_sts_regs_show",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_sts_regs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588976672,
      "name": "pmc_core_lpm_display",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071591556836,
      "name": "pmc_core_lpm_display.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pmc_core_lpm_display(struct pmc_dev * pmcdev, struct device * dev, struct seq_file * s, u32 offset, const char * str, const struct pmc_bit_map * * maps)
```

```json
{
  "name": "pmc_core_lpm_display",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmc_core_lpm_display",
      "external": false,
      "loc": "drivers/platform/x86/intel/pmc/core.c:1132",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_resume",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_show",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687040,
      "name": "pmc_core_lpm_display",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071592677102,
      "name": "pmc_core_lpm_display.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void pmc_core_lpm_display(struct pmc_dev * pmcdev, struct device * dev, struct seq_file * s, u32 offset, const char * str, const struct pmc_bit_map * * maps)
```

```json
{
  "name": "pmc_core_lpm_display",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmc_core_lpm_display",
      "external": false,
      "loc": "drivers/platform/x86/intel/pmc/core.c:1132",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_resume",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_show",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591192224,
      "name": "pmc_core_lpm_display",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071594562308,
      "name": "pmc_core_lpm_display.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void pmc_core_lpm_display(struct pmc_dev * pmcdev, struct device * dev, struct seq_file * s, u32 offset, const char * str, const struct pmc_bit_map * * maps)
```

```json
{
  "name": "pmc_core_lpm_display",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592929296,
      "name": "pmc_core_lpm_display",
      "external": false,
      "loc": "drivers/platform/x86/intel/pmc/core.c:240",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_resume",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_show",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592929296,
      "name": "pmc_core_lpm_display",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void pmc_core_lpm_display(struct pmc * pmc, struct device * dev, struct seq_file * s, u32 offset, int pmc_index, const char * str, const struct pmc_bit_map * * maps)
```

```json
{
  "name": "pmc_core_lpm_display",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593377776,
      "name": "pmc_core_lpm_display",
      "external": false,
      "loc": "drivers/platform/x86/intel/pmc/core.c:254",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_resume_common",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_show",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593377776,
      "name": "pmc_core_lpm_display",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void pmc_core_lpm_display(struct pmc_dev * pmcdev, struct device * dev, struct seq_file * s, u32 offset, const char * str, const struct pmc_bit_map * * maps)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pmc * pmc</code>
</li>
<li>
<b>Param added. </b>
<code>int pmc_index</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pmc_dev * pmcdev</code>
</li>
<li>
<b>Param reordered. </b>
<code>pmcdev, dev, s, offset, str, maps</code> ➡️ <code>pmc, dev, s, offset, pmc_index, str, maps</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void pmc_core_lpm_display(struct pmc * pmc, struct device * dev, struct seq_file * s, u32 offset, int pmc_index, const char * str, const struct pmc_bit_map * * maps)
```
</details>
</li>
</ul>
