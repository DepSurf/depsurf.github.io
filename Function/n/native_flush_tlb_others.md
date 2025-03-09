# Function: <code>native_flush_tlb_others</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314000,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:133",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314000,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313872,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:245",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313872,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579329152,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:260",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329152,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579323024,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:206",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323024,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579347968,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:554",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347968,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359664,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:567",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359664,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387104,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:662",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387104,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402672,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:663",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402672,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405856,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:663",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405856,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415808,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:839",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415808,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416000,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:798",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416000,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401760,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:663",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401760,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331200,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:663",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331200,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401680,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:663",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401680,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```

```json
{
  "name": "native_flush_tlb_others",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410368,
      "name": "native_flush_tlb_others",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:663",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/kvm.c:kvm_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410368,
      "name": "native_flush_tlb_others",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct flush_tlb_info * info</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_flush_tlb_others(const struct cpumask * cpumask, const struct flush_tlb_info * info)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
