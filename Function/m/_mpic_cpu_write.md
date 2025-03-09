# Function: <code>_mpic_cpu_write</code>

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
void _mpic_cpu_write(struct mpic * mpic, unsigned int reg, u32 value)
```

```json
{
  "name": "_mpic_cpu_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282912100,
      "name": "_mpic_cpu_write",
      "external": false,
      "loc": "arch/powerpc/sysdev/mpic.c:258",
      "file": "arch/powerpc/sysdev/mpic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/mpic.c:smp_mpic_message_pass",
        "arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq",
        "arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq",
        "arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu",
        "arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu",
        "arch/powerpc/sysdev/mpic.c:mpic_cpu_set_priority",
        "arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu",
        "arch/powerpc/sysdev/mpic.c:mpic_end_ipi",
        "arch/powerpc/sysdev/mpic.c:mpic_end_irq"
      ],
      "caller_func": [
        "arch/powerpc/sysdev/mpic.c:mpic_init",
        "arch/powerpc/sysdev/mpic.c:mpic_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282903792,
      "name": "_mpic_cpu_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void _mpic_cpu_write(struct mpic * mpic, unsigned int reg, u32 value)
```
</details>
</li>
</ul>
