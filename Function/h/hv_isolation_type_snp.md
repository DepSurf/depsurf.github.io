# Function: <code>hv_isolation_type_snp</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool hv_isolation_type_snp()
```

```json
{
  "name": "hv_isolation_type_snp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579104400,
      "name": "hv_isolation_type_snp",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:267",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579104400,
      "name": "hv_isolation_type_snp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool hv_isolation_type_snp()
```

```json
{
  "name": "hv_isolation_type_snp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579141616,
      "name": "hv_isolation_type_snp",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:267",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141616,
      "name": "hv_isolation_type_snp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool hv_isolation_type_snp()
```

```json
{
  "name": "hv_isolation_type_snp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579142896,
      "name": "hv_isolation_type_snp",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:411",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_non_nested_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142896,
      "name": "hv_isolation_type_snp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool hv_isolation_type_snp()
```

```json
{
  "name": "hv_isolation_type_snp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579170692,
      "name": "hv_isolation_type_snp",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:703",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_ivm_msr_read",
        "arch/x86/hyperv/ivm.c:hv_ivm_msr_write",
        "arch/x86/hyperv/ivm.c:hv_do_hypercall"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/irqdomain.c:hv_do_hypercall",
        "arch/x86/hyperv/hv_proc.c:hv_do_hypercall",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus",
        "drivers/hv/hv_common.c:hv_common_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579171648,
      "name": "hv_isolation_type_snp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool hv_isolation_type_snp()
```
</details>
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
