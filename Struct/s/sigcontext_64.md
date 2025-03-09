# Struct: <code>sigcontext_64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 __pad0;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
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
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u16 ss</code>
</li>
<li>
<b>Field removed. </b>
<code>__u16 __pad0</code>
</li>
</ul>
</details>
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct sigcontext_64 {
    __u64 r8;
    __u64 r9;
    __u64 r10;
    __u64 r11;
    __u64 r12;
    __u64 r13;
    __u64 r14;
    __u64 r15;
    __u64 di;
    __u64 si;
    __u64 bp;
    __u64 bx;
    __u64 dx;
    __u64 ax;
    __u64 cx;
    __u64 sp;
    __u64 ip;
    __u64 flags;
    __u16 cs;
    __u16 gs;
    __u16 fs;
    __u16 ss;
    __u64 err;
    __u64 trapno;
    __u64 oldmask;
    __u64 cr2;
    __u64 fpstate;
    __u64[8] reserved1;
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
