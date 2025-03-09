# Function: <code>kvm_flush_tlb_multi</code>

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
void kvm_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "kvm_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579366480,
      "name": "kvm_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:575",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366480,
      "name": "kvm_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void kvm_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "kvm_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579427248,
      "name": "kvm_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:578",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427248,
      "name": "kvm_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void kvm_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "kvm_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495280,
      "name": "kvm_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:648",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495280,
      "name": "kvm_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void kvm_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "kvm_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593344,
      "name": "kvm_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:647",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593344,
      "name": "kvm_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void kvm_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "kvm_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:647",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605952,
      "name": "kvm_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071596485087,
      "name": "kvm_flush_tlb_multi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void kvm_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "kvm_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:648",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579635216,
      "name": "kvm_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071597381699,
      "name": "kvm_flush_tlb_multi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void kvm_flush_tlb_multi(const struct cpumask * cpumask, const struct flush_tlb_info * info)
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
