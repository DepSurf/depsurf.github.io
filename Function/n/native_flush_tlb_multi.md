# Function: <code>native_flush_tlb_multi</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418960,
      "name": "native_flush_tlb_multi",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:808",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418960,
      "name": "native_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
void native_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_flush_tlb_multi",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:867",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592088032,
      "name": "native_flush_tlb_multi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579482384,
      "name": "native_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561456,
      "name": "native_flush_tlb_multi",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:866",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561456,
      "name": "native_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void native_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668848,
      "name": "native_flush_tlb_multi",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:889",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668848,
      "name": "native_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void native_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682816,
      "name": "native_flush_tlb_multi",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:908",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682816,
      "name": "native_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void native_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_multi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717264,
      "name": "native_flush_tlb_multi",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:909",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717264,
      "name": "native_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void native_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
