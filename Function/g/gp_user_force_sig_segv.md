# Function: <code>gp_user_force_sig_segv</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void gp_user_force_sig_segv(struct pt_regs * regs, int trapnr, long unsigned int error_code, const char * str)
```

```json
{
  "name": "gp_user_force_sig_segv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gp_user_force_sig_segv",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:710",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579117952,
      "name": "gp_user_force_sig_segv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071593818161,
      "name": "gp_user_force_sig_segv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
  "name": "gp_user_force_sig_segv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596392154,
      "name": "gp_user_force_sig_segv",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:719",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_general_protection"
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
  "name": "gp_user_force_sig_segv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596922390,
      "name": "gp_user_force_sig_segv",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:720",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_general_protection"
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
  "name": "gp_user_force_sig_segv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597848118,
      "name": "gp_user_force_sig_segv",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:634",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:exc_general_protection"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void gp_user_force_sig_segv(struct pt_regs * regs, int trapnr, long unsigned int error_code, const char * str)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void gp_user_force_sig_segv(struct pt_regs * regs, int trapnr, long unsigned int error_code, const char * str)
```
</details>
</li>
</ul>
