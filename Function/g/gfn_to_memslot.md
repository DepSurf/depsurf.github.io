# Function: <code>gfn_to_memslot</code>

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
struct kvm_memory_slot * gfn_to_memslot(struct kvm * kvm, gfn_t gfn)
```

```json
{
  "name": "gfn_to_memslot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490388524,
      "name": "gfn_to_memslot",
      "external": true,
      "loc": "virt/kvm/kvm_main.c:1374",
      "file": "virt/kvm/kvm_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:mark_page_dirty",
        "virt/kvm/kvm_main.c:kvm_write_guest_page",
        "virt/kvm/kvm_main.c:kvm_read_guest_atomic",
        "virt/kvm/kvm_main.c:kvm_read_guest_page",
        "virt/kvm/kvm_main.c:kvm_unmap_gfn",
        "virt/kvm/kvm_main.c:gfn_to_pfn",
        "virt/kvm/kvm_main.c:gfn_to_pfn_atomic",
        "virt/kvm/kvm_main.c:gfn_to_pfn_prot",
        "virt/kvm/kvm_main.c:gfn_to_hva_prot",
        "virt/kvm/kvm_main.c:gfn_to_hva",
        "virt/kvm/kvm_main.c:kvm_is_visible_gfn"
      ],
      "caller_func": [
        "virt/kvm/arm/mmu.c:kvm_handle_guest_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490387872,
      "name": "gfn_to_memslot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct kvm_memory_slot * gfn_to_memslot(struct kvm * kvm, gfn_t gfn)
```
</details>
</li>
</ul>
