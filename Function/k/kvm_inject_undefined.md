# Function: <code>kvm_inject_undefined</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void kvm_inject_undefined(struct kvm_vcpu * vcpu)
```

```json
{
  "name": "kvm_inject_undefined",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490480584,
      "name": "kvm_inject_undefined",
      "external": true,
      "loc": "arch/arm64/kvm/inject_fault.c:208",
      "file": "arch/arm64/kvm/inject_fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kvm/handle_exit.c:kvm_handle_unknown_ec",
        "arch/arm64/kvm/sys_regs.c:kvm_handle_sys_reg",
        "arch/arm64/kvm/sys_regs.c:unhandled_cp_access",
        "arch/arm64/kvm/sys_regs.c:perform_access",
        "arch/arm64/kvm/sys_regs.c:kvm_handle_cp14_load_store",
        "arch/arm64/kvm/sys_regs.c:access_pminten",
        "arch/arm64/kvm/sys_regs.c:check_pmu_access_disabled",
        "arch/arm64/kvm/sys_regs.c:trap_loregion",
        "arch/arm64/kvm/sys_regs.c:write_to_read_only",
        "arch/arm64/kvm/sys_regs.c:read_from_write_only"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490480584,
      "name": "kvm_inject_undefined",
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
void kvm_inject_undefined(struct kvm_vcpu * vcpu)
```
</details>
</li>
</ul>
