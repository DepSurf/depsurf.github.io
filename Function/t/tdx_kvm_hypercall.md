# Function: <code>tdx_kvm_hypercall</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int tdx_kvm_hypercall(unsigned int nr, long unsigned int p1, long unsigned int p2, long unsigned int p3, long unsigned int p4)
```

```json
{
  "name": "tdx_kvm_hypercall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578856224,
      "name": "tdx_kvm_hypercall",
      "external": true,
      "loc": "arch/x86/coco/tdx/tdx.c:82",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_kick_cpu",
        "arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856224,
      "name": "tdx_kvm_hypercall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long int tdx_kvm_hypercall(unsigned int nr, long unsigned int p1, long unsigned int p2, long unsigned int p3, long unsigned int p4)
```

```json
{
  "name": "tdx_kvm_hypercall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858656,
      "name": "tdx_kvm_hypercall",
      "external": true,
      "loc": "arch/x86/coco/tdx/tdx.c:84",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_kick_cpu",
        "arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858656,
      "name": "tdx_kvm_hypercall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
long int tdx_kvm_hypercall(unsigned int nr, long unsigned int p1, long unsigned int p2, long unsigned int p3, long unsigned int p4)
```

```json
{
  "name": "tdx_kvm_hypercall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578856432,
      "name": "tdx_kvm_hypercall",
      "external": true,
      "loc": "arch/x86/coco/tdx/tdx.c:48",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_kick_cpu",
        "arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856432,
      "name": "tdx_kvm_hypercall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int tdx_kvm_hypercall(unsigned int nr, long unsigned int p1, long unsigned int p2, long unsigned int p3, long unsigned int p4)
```

```json
{
  "name": "tdx_kvm_hypercall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578856832,
      "name": "tdx_kvm_hypercall",
      "external": true,
      "loc": "arch/x86/coco/tdx/tdx.c:49",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_kick_cpu",
        "arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/kernel/kvm.c:__send_ipi_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856832,
      "name": "tdx_kvm_hypercall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long int tdx_kvm_hypercall(unsigned int nr, long unsigned int p1, long unsigned int p2, long unsigned int p3, long unsigned int p4)
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
