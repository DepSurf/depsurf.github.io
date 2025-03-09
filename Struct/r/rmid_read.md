# Struct: <code>rmid_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    u32 rmid;
    u32 evt_type;
    atomic64_t value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    u32 rmid;
    u32 evt_type;
    atomic64_t value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    u32 rmid;
    u32 evt_type;
    atomic64_t value;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_resource * r;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_resource * r;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_resource * r;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_resource * r;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_resource * r;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_resource * r;
    struct rdt_domain * d;
    enum resctrl_event_id evtid;
    bool first;
    int err;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_resource * r;
    struct rdt_domain * d;
    enum resctrl_event_id evtid;
    bool first;
    int err;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_resource * r;
    struct rdt_domain * d;
    enum resctrl_event_id evtid;
    bool first;
    int err;
    u64 val;
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
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
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
<b>Field added. </b>
<code>struct rdtgroup * rgrp</code>
</li>
<li>
<b>Field added. </b>
<code>struct rdt_domain * d</code>
</li>
<li>
<b>Field added. </b>
<code>int evtid</code>
</li>
<li>
<b>Field added. </b>
<code>bool first</code>
</li>
<li>
<b>Field added. </b>
<code>u64 val</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rmid</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 evt_type</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic64_t value</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rdt_resource * r</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int err</code>
</li>
<li>
<b>Field type changed. </b>
<code>int evtid</code> ➡️ <code>enum resctrl_event_id evtid</code>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct rmid_read {
    struct rdtgroup * rgrp;
    struct rdt_domain * d;
    int evtid;
    bool first;
    u64 val;
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
