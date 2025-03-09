# Struct: <code>arch_specific_insn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    int boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    int boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    int boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
    int tp_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    unsigned int boostable;
    unsigned char size;
    unsigned char opcode;
    struct (anon) jcc;
    struct (anon) loop;
    struct (anon) indirect;
    s32 rel32;
    void (*)(struct kprobe *, struct pt_regs *) emulate_op;
    int tp_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    unsigned int boostable;
    unsigned char size;
    unsigned char opcode;
    struct (anon) jcc;
    struct (anon) loop;
    struct (anon) indirect;
    s32 rel32;
    void (*)(struct kprobe *, struct pt_regs *) emulate_op;
    int tp_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    unsigned int boostable;
    unsigned char size;
    unsigned char opcode;
    struct (anon) jcc;
    struct (anon) loop;
    struct (anon) indirect;
    s32 rel32;
    void (*)(struct kprobe *, struct pt_regs *) emulate_op;
    int tp_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    unsigned int boostable;
    unsigned char size;
    unsigned char opcode;
    struct (anon) jcc;
    struct (anon) loop;
    struct (anon) indirect;
    s32 rel32;
    void (*)(struct kprobe *, struct pt_regs *) emulate_op;
    int tp_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    unsigned int boostable;
    unsigned char size;
    unsigned char opcode;
    struct (anon) jcc;
    struct (anon) loop;
    struct (anon) indirect;
    s32 rel32;
    void (*)(struct kprobe *, struct pt_regs *) emulate_op;
    int tp_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    unsigned int boostable;
    unsigned char size;
    unsigned char opcode;
    struct (anon) jcc;
    struct (anon) loop;
    struct (anon) indirect;
    s32 rel32;
    void (*)(struct kprobe *, struct pt_regs *) emulate_op;
    int tp_len;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct arch_specific_insn {
    struct arch_probe_insn api;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    int boostable;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
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
<b>Field type changed. </b>
<code>int boostable</code> ➡️ <code>bool boostable</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int tp_len</code>
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
<code>unsigned char size</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char opcode</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) jcc</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) loop</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) indirect</code>
</li>
<li>
<b>Field added. </b>
<code>s32 rel32</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kprobe *, struct pt_regs *) emulate_op</code>
</li>
<li>
<b>Field removed. </b>
<code>bool if_modifier</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool boostable</code> ➡️ <code>unsigned int boostable</code>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct arch_probe_insn api</code>
</li>
<li>
<b>Field removed. </b>
<code>kprobe_opcode_t * insn</code>
</li>
<li>
<b>Field removed. </b>
<code>bool boostable</code>
</li>
<li>
<b>Field removed. </b>
<code>bool if_modifier</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool if_modifier</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool boostable</code> ➡️ <code>int boostable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct arch_specific_insn {
    kprobe_opcode_t * insn;
    bool boostable;
    bool if_modifier;
}
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
