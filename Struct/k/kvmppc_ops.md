# Struct: <code>kvmppc_ops</code>

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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kvmppc_ops {
    struct module * owner;
    int (*)(struct kvm_vcpu *, struct kvm_sregs *) get_sregs;
    int (*)(struct kvm_vcpu *, struct kvm_sregs *) set_sregs;
    int (*)(struct kvm_vcpu *, u64, union kvmppc_one_reg *) get_one_reg;
    int (*)(struct kvm_vcpu *, u64, union kvmppc_one_reg *) set_one_reg;
    void (*)(struct kvm_vcpu *, int) vcpu_load;
    void (*)(struct kvm_vcpu *) vcpu_put;
    void (*)(struct kvm_vcpu *, u64) set_msr;
    int (*)(struct kvm_run *, struct kvm_vcpu *) vcpu_run;
    struct kvm_vcpu * (*)(struct kvm *, unsigned int) vcpu_create;
    void (*)(struct kvm_vcpu *) vcpu_free;
    int (*)(struct kvm_vcpu *) check_requests;
    int (*)(struct kvm *, struct kvm_dirty_log *) get_dirty_log;
    void (*)(struct kvm *, struct kvm_memory_slot *) flush_memslot;
    int (*)(struct kvm *, struct kvm_memory_slot *, const struct kvm_userspace_memory_region *) prepare_memory_region;
    void (*)(struct kvm *, const struct kvm_userspace_memory_region *, const struct kvm_memory_slot *, const struct kvm_memory_slot *, enum kvm_mr_change) commit_memory_region;
    int (*)(struct kvm *, long unsigned int, long unsigned int) unmap_hva_range;
    int (*)(struct kvm *, long unsigned int, long unsigned int) age_hva;
    int (*)(struct kvm *, long unsigned int) test_age_hva;
    void (*)(struct kvm *, long unsigned int, pte_t) set_spte_hva;
    void (*)(struct kvm_vcpu *) mmu_destroy;
    void (*)(struct kvm_memory_slot *, struct kvm_memory_slot *) free_memslot;
    int (*)(struct kvm_memory_slot *, long unsigned int) create_memslot;
    int (*)(struct kvm *) init_vm;
    void (*)(struct kvm *) destroy_vm;
    int (*)(struct kvm *, struct kvm_ppc_smmu_info *) get_smmu_info;
    int (*)(struct kvm_run *, struct kvm_vcpu *, unsigned int, int *) emulate_op;
    int (*)(struct kvm_vcpu *, int, ulong) emulate_mtspr;
    int (*)(struct kvm_vcpu *, int, ulong *) emulate_mfspr;
    void (*)(struct kvm_vcpu *) fast_vcpu_kick;
    long int (*)(struct file *, unsigned int, long unsigned int) arch_vm_ioctl;
    int (*)(long unsigned int) hcall_implemented;
    int (*)(struct irq_bypass_consumer *, struct irq_bypass_producer *) irq_bypass_add_producer;
    void (*)(struct irq_bypass_consumer *, struct irq_bypass_producer *) irq_bypass_del_producer;
    int (*)(struct kvm *, struct kvm_ppc_mmuv3_cfg *) configure_mmu;
    int (*)(struct kvm *, struct kvm_ppc_rmmu_info *) get_rmmu_info;
    int (*)(struct kvm *, long unsigned int, long unsigned int) set_smt_mode;
    void (*)(struct kvm_vcpu *, ulong) giveup_ext;
    int (*)(struct kvm *) enable_nested;
    int (*)(struct kvm_vcpu *, ulong *, void *, int) load_from_eaddr;
    int (*)(struct kvm_vcpu *, ulong *, void *, int) store_to_eaddr;
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
struct kvmppc_ops {
    struct module * owner;
    int (*)(struct kvm_vcpu *, struct kvm_sregs *) get_sregs;
    int (*)(struct kvm_vcpu *, struct kvm_sregs *) set_sregs;
    int (*)(struct kvm_vcpu *, u64, union kvmppc_one_reg *) get_one_reg;
    int (*)(struct kvm_vcpu *, u64, union kvmppc_one_reg *) set_one_reg;
    void (*)(struct kvm_vcpu *, int) vcpu_load;
    void (*)(struct kvm_vcpu *) vcpu_put;
    void (*)(struct kvm_vcpu *, u64) set_msr;
    int (*)(struct kvm_run *, struct kvm_vcpu *) vcpu_run;
    struct kvm_vcpu * (*)(struct kvm *, unsigned int) vcpu_create;
    void (*)(struct kvm_vcpu *) vcpu_free;
    int (*)(struct kvm_vcpu *) check_requests;
    int (*)(struct kvm *, struct kvm_dirty_log *) get_dirty_log;
    void (*)(struct kvm *, struct kvm_memory_slot *) flush_memslot;
    int (*)(struct kvm *, struct kvm_memory_slot *, const struct kvm_userspace_memory_region *) prepare_memory_region;
    void (*)(struct kvm *, const struct kvm_userspace_memory_region *, const struct kvm_memory_slot *, const struct kvm_memory_slot *, enum kvm_mr_change) commit_memory_region;
    int (*)(struct kvm *, long unsigned int, long unsigned int) unmap_hva_range;
    int (*)(struct kvm *, long unsigned int, long unsigned int) age_hva;
    int (*)(struct kvm *, long unsigned int) test_age_hva;
    void (*)(struct kvm *, long unsigned int, pte_t) set_spte_hva;
    void (*)(struct kvm_vcpu *) mmu_destroy;
    void (*)(struct kvm_memory_slot *, struct kvm_memory_slot *) free_memslot;
    int (*)(struct kvm_memory_slot *, long unsigned int) create_memslot;
    int (*)(struct kvm *) init_vm;
    void (*)(struct kvm *) destroy_vm;
    int (*)(struct kvm *, struct kvm_ppc_smmu_info *) get_smmu_info;
    int (*)(struct kvm_run *, struct kvm_vcpu *, unsigned int, int *) emulate_op;
    int (*)(struct kvm_vcpu *, int, ulong) emulate_mtspr;
    int (*)(struct kvm_vcpu *, int, ulong *) emulate_mfspr;
    void (*)(struct kvm_vcpu *) fast_vcpu_kick;
    long int (*)(struct file *, unsigned int, long unsigned int) arch_vm_ioctl;
    int (*)(long unsigned int) hcall_implemented;
    int (*)(struct irq_bypass_consumer *, struct irq_bypass_producer *) irq_bypass_add_producer;
    void (*)(struct irq_bypass_consumer *, struct irq_bypass_producer *) irq_bypass_del_producer;
    int (*)(struct kvm *, struct kvm_ppc_mmuv3_cfg *) configure_mmu;
    int (*)(struct kvm *, struct kvm_ppc_rmmu_info *) get_rmmu_info;
    int (*)(struct kvm *, long unsigned int, long unsigned int) set_smt_mode;
    void (*)(struct kvm_vcpu *, ulong) giveup_ext;
    int (*)(struct kvm *) enable_nested;
    int (*)(struct kvm_vcpu *, ulong *, void *, int) load_from_eaddr;
    int (*)(struct kvm_vcpu *, ulong *, void *, int) store_to_eaddr;
}
```
</details>
</li>
</ul>
