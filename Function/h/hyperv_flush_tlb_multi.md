# Function: <code>hyperv_flush_tlb_multi</code>

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
void hyperv_flush_tlb_multi(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579052144,
      "name": "hyperv_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:55",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579052144,
      "name": "hyperv_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1051
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
void hyperv_flush_tlb_multi(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073024,
      "name": "hyperv_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:55",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073024,
      "name": "hyperv_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1075
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
void hyperv_flush_tlb_multi(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098144,
      "name": "hyperv_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:55",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098144,
      "name": "hyperv_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1121
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
void hyperv_flush_tlb_multi(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579134560,
      "name": "hyperv_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:55",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579134560,
      "name": "hyperv_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
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
void hyperv_flush_tlb_multi(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hyperv_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:60",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135152,
      "name": "hyperv_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1264
    },
    {
      "addr": 18446744071596475331,
      "name": "hyperv_flush_tlb_multi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void hyperv_flush_tlb_multi(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_multi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hyperv_flush_tlb_multi",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:60",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161648,
      "name": "hyperv_flush_tlb_multi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
    },
    {
      "addr": 18446744071597370755,
      "name": "hyperv_flush_tlb_multi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void hyperv_flush_tlb_multi(const struct cpumask * cpus, const struct flush_tlb_info * info)
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
