# Struct: <code>text_poke_loc</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    s32 rel_addr;
    s32 rel32;
    u8 opcode;
    const const u8[5] text;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    s32 rel_addr;
    s32 rel32;
    u8 opcode;
    const const u8[5] text;
    u8 old;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    s32 rel_addr;
    s32 rel32;
    u8 opcode;
    const const u8[5] text;
    u8 old;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    s32 rel_addr;
    s32 rel32;
    u8 opcode;
    const const u8[5] text;
    u8 old;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    s32 rel_addr;
    s32 disp;
    u8 len;
    u8 opcode;
    const const u8[5] text;
    u8 old;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    s32 rel_addr;
    s32 disp;
    u8 len;
    u8 opcode;
    const const u8[5] text;
    u8 old;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    s32 rel_addr;
    s32 disp;
    u8 len;
    u8 opcode;
    const const u8[5] text;
    u8 old;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    s32 rel_addr;
    s32 disp;
    u8 len;
    u8 opcode;
    const const u8[5] text;
    u8 old;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
}
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>s32 rel_addr</code>
</li>
<li>
<b>Field added. </b>
<code>s32 rel32</code>
</li>
<li>
<b>Field added. </b>
<code>const const u8[5] text</code>
</li>
<li>
<b>Field removed. </b>
<code>void * detour</code>
</li>
<li>
<b>Field removed. </b>
<code>void * addr</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t len</code>
</li>
<li>
<b>Field type changed. </b>
<code>const const char[5] opcode</code> ➡️ <code>u8 opcode</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 old</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>s32 disp</code>
</li>
<li>
<b>Field added. </b>
<code>u8 len</code>
</li>
<li>
<b>Field removed. </b>
<code>s32 rel32</code>
</li>
</ul>
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct text_poke_loc {
    void * detour;
    void * addr;
    size_t len;
    const const char[5] opcode;
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
