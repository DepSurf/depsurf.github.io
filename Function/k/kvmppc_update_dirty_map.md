# Function: <code>kvmppc_update_dirty_map</code>

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
void kvmppc_update_dirty_map(const struct kvm_memory_slot * memslot, long unsigned int gfn, long unsigned int psize)
```

```json
{
  "name": "kvmppc_update_dirty_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283343992,
      "name": "kvmppc_update_dirty_map",
      "external": true,
      "loc": "arch/powerpc/kvm/book3s_hv_rm_mmu.c:109",
      "file": "arch/powerpc/kvm/book3s_hv_rm_mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_rm_h_page_init",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_rm_h_page_init"
      ],
      "caller_func": [
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_clear_mod",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:remove_revmap_chain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283329088,
      "name": "kvmppc_update_dirty_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void kvmppc_update_dirty_map(const struct kvm_memory_slot * memslot, long unsigned int gfn, long unsigned int psize)
```
</details>
</li>
</ul>
