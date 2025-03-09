# Function: <code>kvm_vcpu_gfn_to_memslot</code>

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
struct kvm_memory_slot * kvm_vcpu_gfn_to_memslot(struct kvm_vcpu * vcpu, gfn_t gfn)
```

```json
{
  "name": "kvm_vcpu_gfn_to_memslot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490388772,
      "name": "kvm_vcpu_gfn_to_memslot",
      "external": true,
      "loc": "virt/kvm/kvm_main.c:1380",
      "file": "virt/kvm/kvm_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_vcpu_mark_page_dirty",
        "virt/kvm/kvm_main.c:kvm_vcpu_write_guest_page",
        "virt/kvm/kvm_main.c:kvm_vcpu_read_guest_atomic",
        "virt/kvm/kvm_main.c:kvm_vcpu_read_guest_page",
        "virt/kvm/kvm_main.c:kvm_vcpu_unmap",
        "virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_pfn",
        "virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_pfn_atomic",
        "virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_hva_prot",
        "virt/kvm/kvm_main.c:kvm_vcpu_gfn_to_hva"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490407384,
      "name": "kvm_vcpu_gfn_to_memslot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct kvm_memory_slot * kvm_vcpu_gfn_to_memslot(struct kvm_vcpu * vcpu, gfn_t gfn)
```
</details>
</li>
</ul>
