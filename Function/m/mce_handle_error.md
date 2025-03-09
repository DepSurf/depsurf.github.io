# Function: <code>mce_handle_error</code>

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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
long int mce_handle_error(struct pt_regs * regs, const struct mce_derror_table * dtable, const struct mce_ierror_table * itable)
```

```json
{
  "name": "mce_handle_error",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282402992,
      "name": "mce_handle_error",
      "external": false,
      "loc": "arch/powerpc/kernel/mce_power.c:605",
      "file": "arch/powerpc/kernel/mce_power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/mce_power.c:__machine_check_early_realmode_p9",
        "arch/powerpc/kernel/mce_power.c:__machine_check_early_realmode_p8",
        "arch/powerpc/kernel/mce_power.c:__machine_check_early_realmode_p7"
      ]
    },
    {
      "addr": 13835058055283157536,
      "name": "mce_handle_error",
      "external": false,
      "loc": "arch/powerpc/platforms/pseries/ras.c:498",
      "file": "arch/powerpc/platforms/pseries/ras.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/ras.c:pseries_machine_check_realmode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282402992,
      "name": "mce_handle_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
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
long int mce_handle_error(struct pt_regs * regs, const struct mce_derror_table * dtable, const struct mce_ierror_table * itable)
```
</details>
</li>
</ul>
