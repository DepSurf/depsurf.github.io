# Function: <code>_exception</code>

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
void _exception(int signr, struct pt_regs * regs, int code, long unsigned int addr)
```

```json
{
  "name": "_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282350704,
      "name": "_exception",
      "external": true,
      "loc": "arch/powerpc/kernel/traps.c:368",
      "file": "arch/powerpc/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/traps.c:altivec_assist_exception",
        "arch/powerpc/kernel/traps.c:facility_unavailable_exception",
        "arch/powerpc/kernel/traps.c:vsx_unavailable_exception",
        "arch/powerpc/kernel/traps.c:altivec_unavailable_exception",
        "arch/powerpc/kernel/traps.c:alignment_exception",
        "arch/powerpc/kernel/traps.c:program_check_exception",
        "arch/powerpc/kernel/traps.c:program_check_exception",
        "arch/powerpc/kernel/traps.c:program_check_exception",
        "arch/powerpc/kernel/traps.c:RunModeException",
        "arch/powerpc/kernel/traps.c:instruction_breakpoint_exception",
        "arch/powerpc/kernel/traps.c:unknown_exception",
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "arch/powerpc/mm/fault.c:bad_access",
        "arch/powerpc/mm/fault.c:bad_area",
        "arch/powerpc/mm/fault.c:bad_area_nosemaphore",
        "arch/powerpc/mm/book3s64/hash_utils.c:low_hash_fault",
        "arch/powerpc/mm/book3s64/hash_utils.c:low_hash_fault",
        "arch/powerpc/mm/book3s64/slb.c:do_bad_slb_fault",
        "arch/powerpc/platforms/powernv/opal.c:opal_machine_check",
        "arch/powerpc/platforms/pseries/ras.c:pSeries_machine_check_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282350704,
      "name": "_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void _exception(int signr, struct pt_regs * regs, int code, long unsigned int addr)
```
</details>
</li>
</ul>
