# Function: <code>user_regset_copyout_zero</code>

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
int user_regset_copyout_zero(unsigned int * pos, unsigned int * count, void * * kbuf, void * * ubuf, const int start_pos, const int end_pos)
```

```json
{
  "name": "user_regset_copyout_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490212324,
      "name": "user_regset_copyout_zero",
      "external": false,
      "loc": "include/linux/regset.h:308",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:sve_get",
        "arch/arm64/kernel/ptrace.c:sve_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get",
        "arch/arm64/kernel/ptrace.c:hw_break_get"
      ],
      "caller_func": [
        "arch/arm64/kernel/ptrace.c:sve_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490201696,
      "name": "user_regset_copyout_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyout_zero",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224421296,
      "name": "user_regset_copyout_zero",
      "external": false,
      "loc": "include/linux/regset.h:308",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/ptrace.c:vfp_get"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "user_regset_copyout_zero",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282260952,
      "name": "user_regset_copyout_zero",
      "external": false,
      "loc": "include/linux/regset.h:308",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace.c:tm_cgpr_get",
        "arch/powerpc/kernel/ptrace.c:gpr_get"
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
int user_regset_copyout_zero(unsigned int * pos, unsigned int * count, void * * kbuf, void * * ubuf, const int start_pos, const int end_pos)
```
</details>
</li>
</ul>
