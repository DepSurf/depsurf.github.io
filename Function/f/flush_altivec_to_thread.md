# Function: <code>flush_altivec_to_thread</code>

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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void flush_altivec_to_thread(struct task_struct * tsk)
```

```json
{
  "name": "flush_altivec_to_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282297216,
      "name": "flush_altivec_to_thread",
      "external": true,
      "loc": "arch/powerpc/kernel/process.c:309",
      "file": "arch/powerpc/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/ptrace.c:tm_spr_set",
        "arch/powerpc/kernel/ptrace.c:tm_spr_get",
        "arch/powerpc/kernel/ptrace.c:tm_cvsx_set",
        "arch/powerpc/kernel/ptrace.c:tm_cvsx_get",
        "arch/powerpc/kernel/ptrace.c:tm_cvmx_set",
        "arch/powerpc/kernel/ptrace.c:tm_cvmx_get",
        "arch/powerpc/kernel/ptrace.c:tm_cfpr_set",
        "arch/powerpc/kernel/ptrace.c:tm_cfpr_get",
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_set",
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_get",
        "arch/powerpc/kernel/ptrace.c:vsr_set",
        "arch/powerpc/kernel/ptrace.c:vsr_get",
        "arch/powerpc/kernel/ptrace.c:vr_set",
        "arch/powerpc/kernel/ptrace.c:vr_get",
        "arch/powerpc/kernel/ptrace.c:vr_active",
        "arch/powerpc/kernel/signal_32.c:save_user_regs",
        "arch/powerpc/kernel/traps.c:altivec_assist_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282297216,
      "name": "flush_altivec_to_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void flush_altivec_to_thread(struct task_struct * tsk)
```
</details>
</li>
</ul>
