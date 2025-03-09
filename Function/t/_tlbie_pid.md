# Function: <code>_tlbie_pid</code>

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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void _tlbie_pid(long unsigned int pid, long unsigned int ric)
```

```json
{
  "name": "_tlbie_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282800900,
      "name": "_tlbie_pid",
      "external": false,
      "loc": "arch/powerpc/mm/book3s64/radix_tlb.c:310",
      "file": "arch/powerpc/mm/book3s64/radix_tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize",
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush",
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush",
        "arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range",
        "arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range",
        "arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm",
        "arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm",
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm",
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm"
      ],
      "caller_func": [
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize",
        "arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range",
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282781424,
      "name": "_tlbie_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
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
void _tlbie_pid(long unsigned int pid, long unsigned int ric)
```
</details>
</li>
</ul>
