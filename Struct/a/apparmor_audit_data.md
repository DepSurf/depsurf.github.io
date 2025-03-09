# Struct: <code>apparmor_audit_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) net;
    int signal;
    struct (anon) iface;
    struct (anon) rlim;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) net;
    int signal;
    struct (anon) iface;
    struct (anon) rlim;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) net;
    int signal;
    struct (anon) iface;
    struct (anon) rlim;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) net;
    int signal;
    struct (anon) rlim;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) net;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    u16 class;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) mq;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    u16 class;
    const char * op;
    const struct cred * subj_cred;
    struct aa_label * subj_label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct task_struct * subjtsk;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) mq;
    struct (anon) iface;
    struct (anon) mnt;
    struct common_audit_data common;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    u32 flags;
    int error;
    int type;
    u16 class;
    const char * op;
    const struct cred * subj_cred;
    struct aa_label * subj_label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct task_struct * subjtsk;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) mq;
    struct (anon) iface;
    struct (anon) mnt;
    struct (anon) uring;
    struct common_audit_data common;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    u32 flags;
    int error;
    int type;
    u16 class;
    const char * op;
    const struct cred * subj_cred;
    struct aa_label * subj_label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct task_struct * subjtsk;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) mq;
    struct (anon) ns;
    struct (anon) iface;
    struct (anon) mnt;
    struct (anon) uring;
    struct common_audit_data common;
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
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct apparmor_audit_data {
    int error;
    int type;
    const char * op;
    struct aa_label * label;
    const char * name;
    const char * info;
    u32 request;
    u32 denied;
    struct aa_label * peer;
    struct (anon) fs;
    struct (anon) rlim;
    int signal;
    int unmappedsig;
    struct (anon) net;
    struct (anon) iface;
    struct (anon) mnt;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int unmappedsig</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 class</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) mq</code>
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
<code>const struct cred * subj_cred</code>
</li>
<li>
<b>Field added. </b>
<code>struct aa_label * subj_label</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * subjtsk</code>
</li>
<li>
<b>Field added. </b>
<code>struct common_audit_data common</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aa_label * label</code>
</li>
</ul>
</details>
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
<code>struct (anon) uring</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) ns</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
