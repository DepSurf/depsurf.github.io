# Struct: <code>kvm_x86_nested_ops</code>

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
struct kvm_x86_nested_ops {
    int (*)(struct kvm_vcpu *) check_events;
    bool (*)(struct kvm_vcpu *) hv_timer_pending;
    void (*)(struct kvm_vcpu *) triple_fault;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, unsigned int) get_state;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, struct kvm_nested_state *) set_state;
    bool (*)(struct kvm_vcpu *) get_nested_state_pages;
    int (*)(struct kvm_vcpu *, gpa_t) write_log_dirty;
    int (*)(struct kvm_vcpu *, uint16_t *) enable_evmcs;
    uint16_t (*)(struct kvm_vcpu *) get_evmcs_version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_x86_nested_ops {
    void (*)(struct kvm_vcpu *) leave_nested;
    int (*)(struct kvm_vcpu *) check_events;
    bool (*)(struct kvm_vcpu *) hv_timer_pending;
    void (*)(struct kvm_vcpu *) triple_fault;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, unsigned int) get_state;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, struct kvm_nested_state *) set_state;
    bool (*)(struct kvm_vcpu *) get_nested_state_pages;
    int (*)(struct kvm_vcpu *, gpa_t) write_log_dirty;
    int (*)(struct kvm_vcpu *, uint16_t *) enable_evmcs;
    uint16_t (*)(struct kvm_vcpu *) get_evmcs_version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_x86_nested_ops {
    void (*)(struct kvm_vcpu *) leave_nested;
    int (*)(struct kvm_vcpu *) check_events;
    bool (*)(struct kvm_vcpu *, struct x86_exception *) handle_page_fault_workaround;
    bool (*)(struct kvm_vcpu *) hv_timer_pending;
    void (*)(struct kvm_vcpu *) triple_fault;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, unsigned int) get_state;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, struct kvm_nested_state *) set_state;
    bool (*)(struct kvm_vcpu *) get_nested_state_pages;
    int (*)(struct kvm_vcpu *, gpa_t) write_log_dirty;
    int (*)(struct kvm_vcpu *, uint16_t *) enable_evmcs;
    uint16_t (*)(struct kvm_vcpu *) get_evmcs_version;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_x86_nested_ops {
    void (*)(struct kvm_vcpu *) leave_nested;
    bool (*)(struct kvm_vcpu *, u8, u32) is_exception_vmexit;
    int (*)(struct kvm_vcpu *) check_events;
    bool (*)(struct kvm_vcpu *) has_events;
    void (*)(struct kvm_vcpu *) triple_fault;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, unsigned int) get_state;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, struct kvm_nested_state *) set_state;
    bool (*)(struct kvm_vcpu *) get_nested_state_pages;
    int (*)(struct kvm_vcpu *, gpa_t) write_log_dirty;
    int (*)(struct kvm_vcpu *, uint16_t *) enable_evmcs;
    uint16_t (*)(struct kvm_vcpu *) get_evmcs_version;
    void (*)(struct kvm_vcpu *) hv_inject_synthetic_vmexit_post_tlb_flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_x86_nested_ops {
    void (*)(struct kvm_vcpu *) leave_nested;
    bool (*)(struct kvm_vcpu *, u8, u32) is_exception_vmexit;
    int (*)(struct kvm_vcpu *) check_events;
    bool (*)(struct kvm_vcpu *) has_events;
    void (*)(struct kvm_vcpu *) triple_fault;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, unsigned int) get_state;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, struct kvm_nested_state *) set_state;
    bool (*)(struct kvm_vcpu *) get_nested_state_pages;
    int (*)(struct kvm_vcpu *, gpa_t) write_log_dirty;
    int (*)(struct kvm_vcpu *, uint16_t *) enable_evmcs;
    uint16_t (*)(struct kvm_vcpu *) get_evmcs_version;
    void (*)(struct kvm_vcpu *) hv_inject_synthetic_vmexit_post_tlb_flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_x86_nested_ops {
    void (*)(struct kvm_vcpu *) leave_nested;
    bool (*)(struct kvm_vcpu *, u8, u32) is_exception_vmexit;
    int (*)(struct kvm_vcpu *) check_events;
    bool (*)(struct kvm_vcpu *) has_events;
    void (*)(struct kvm_vcpu *) triple_fault;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, unsigned int) get_state;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, struct kvm_nested_state *) set_state;
    bool (*)(struct kvm_vcpu *) get_nested_state_pages;
    int (*)(struct kvm_vcpu *, gpa_t) write_log_dirty;
    int (*)(struct kvm_vcpu *, uint16_t *) enable_evmcs;
    uint16_t (*)(struct kvm_vcpu *) get_evmcs_version;
    void (*)(struct kvm_vcpu *) hv_inject_synthetic_vmexit_post_tlb_flush;
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
struct kvm_x86_nested_ops {
    int (*)(struct kvm_vcpu *) check_events;
    bool (*)(struct kvm_vcpu *) hv_timer_pending;
    void (*)(struct kvm_vcpu *) triple_fault;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, unsigned int) get_state;
    int (*)(struct kvm_vcpu *, struct kvm_nested_state *, struct kvm_nested_state *) set_state;
    bool (*)(struct kvm_vcpu *) get_nested_state_pages;
    int (*)(struct kvm_vcpu *, gpa_t) write_log_dirty;
    int (*)(struct kvm_vcpu *, uint16_t *) enable_evmcs;
    uint16_t (*)(struct kvm_vcpu *) get_evmcs_version;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *) leave_nested</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(struct kvm_vcpu *, struct x86_exception *) handle_page_fault_workaround</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(struct kvm_vcpu *, u8, u32) is_exception_vmexit</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct kvm_vcpu *) has_events</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *) hv_inject_synthetic_vmexit_post_tlb_flush</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct kvm_vcpu *, struct x86_exception *) handle_page_fault_workaround</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct kvm_vcpu *) hv_timer_pending</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
