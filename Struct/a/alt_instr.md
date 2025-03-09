# Struct: <code>alt_instr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u32 cpuid;
    u32 flags;
    u32 ft_flags;
    u8 instrlen;
    u8 replacementlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u32 cpuid;
    u32 flags;
    u32 ft_flags;
    u8 instrlen;
    u8 replacementlen;
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
struct alt_instr {
    s32 orig_offset;
    s32 alt_offset;
    u16 cpufeature;
    u8 orig_len;
    u8 alt_len;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u8 padlen</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Field added. </b>
<code>u32 ft_flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>u16 cpuid</code> ➡️ <code>u32 cpuid</code>
</li>
</ul>
</details>
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
<code>s32 orig_offset</code>
</li>
<li>
<b>Field added. </b>
<code>s32 alt_offset</code>
</li>
<li>
<b>Field added. </b>
<code>u16 cpufeature</code>
</li>
<li>
<b>Field added. </b>
<code>u8 orig_len</code>
</li>
<li>
<b>Field added. </b>
<code>u8 alt_len</code>
</li>
<li>
<b>Field removed. </b>
<code>s32 instr_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>s32 repl_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 cpuid</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 instrlen</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 replacementlen</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 padlen</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct alt_instr {
    s32 instr_offset;
    s32 repl_offset;
    u16 cpuid;
    u8 instrlen;
    u8 replacementlen;
    u8 padlen;
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
