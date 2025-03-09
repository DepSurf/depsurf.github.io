# Struct: <code>bpf_jit_poke_descriptor</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_jit_poke_descriptor {
    void * ip;
    struct (anon) tail_call;
    bool ip_stable;
    u8 adj_off;
    u16 reason;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_jit_poke_descriptor {
    void * tailcall_target;
    void * tailcall_bypass;
    void * bypass_addr;
    struct (anon) tail_call;
    bool tailcall_target_stable;
    u8 adj_off;
    u16 reason;
    u32 insn_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_jit_poke_descriptor {
    void * tailcall_target;
    void * tailcall_bypass;
    void * bypass_addr;
    void * aux;
    struct (anon) tail_call;
    bool tailcall_target_stable;
    u8 adj_off;
    u16 reason;
    u32 insn_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_jit_poke_descriptor {
    void * tailcall_target;
    void * tailcall_bypass;
    void * bypass_addr;
    void * aux;
    struct (anon) tail_call;
    bool tailcall_target_stable;
    u8 adj_off;
    u16 reason;
    u32 insn_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_jit_poke_descriptor {
    void * tailcall_target;
    void * tailcall_bypass;
    void * bypass_addr;
    void * aux;
    struct (anon) tail_call;
    bool tailcall_target_stable;
    u8 adj_off;
    u16 reason;
    u32 insn_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_jit_poke_descriptor {
    void * tailcall_target;
    void * tailcall_bypass;
    void * bypass_addr;
    void * aux;
    struct (anon) tail_call;
    bool tailcall_target_stable;
    u8 adj_off;
    u16 reason;
    u32 insn_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_jit_poke_descriptor {
    void * tailcall_target;
    void * tailcall_bypass;
    void * bypass_addr;
    void * aux;
    struct (anon) tail_call;
    bool tailcall_target_stable;
    u8 adj_off;
    u16 reason;
    u32 insn_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_jit_poke_descriptor {
    void * tailcall_target;
    void * tailcall_bypass;
    void * bypass_addr;
    void * aux;
    struct (anon) tail_call;
    bool tailcall_target_stable;
    u8 adj_off;
    u16 reason;
    u32 insn_idx;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct bpf_jit_poke_descriptor {
    void * ip;
    struct (anon) tail_call;
    bool ip_stable;
    u8 adj_off;
    u16 reason;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * tailcall_target</code>
</li>
<li>
<b>Field added. </b>
<code>void * tailcall_bypass</code>
</li>
<li>
<b>Field added. </b>
<code>void * bypass_addr</code>
</li>
<li>
<b>Field added. </b>
<code>bool tailcall_target_stable</code>
</li>
<li>
<b>Field added. </b>
<code>u32 insn_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>void * ip</code>
</li>
<li>
<b>Field removed. </b>
<code>bool ip_stable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * aux</code>
</li>
</ul>
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
