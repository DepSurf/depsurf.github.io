# Function: <code>qm_ccsr_in</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u32 qm_ccsr_in(u32 offset)
```

```json
{
  "name": "qm_ccsr_in",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498086568,
      "name": "qm_ccsr_in",
      "external": false,
      "loc": "drivers/soc/fsl/qbman/qman_ccsr.c:279",
      "file": "drivers/soc/fsl/qbman/qman_ccsr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_set_sdest",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_set_sdest",
        "drivers/soc/fsl/qbman/qman_ccsr.c:__qman_liodn_fixup",
        "drivers/soc/fsl/qbman/qman_ccsr.c:__qman_liodn_fixup",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory"
      ],
      "caller_func": [
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qman_isr",
        "drivers/soc/fsl/qbman/qman_ccsr.c:log_edata_bits",
        "drivers/soc/fsl/qbman/qman_ccsr.c:log_edata_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498084840,
      "name": "qm_ccsr_in",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
u32 qm_ccsr_in(u32 offset)
```
</details>
</li>
</ul>
