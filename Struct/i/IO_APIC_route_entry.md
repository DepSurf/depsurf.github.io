# Struct: <code>IO_APIC_route_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    u64 vector;
    u64 delivery_mode;
    u64 dest_mode_logical;
    u64 delivery_status;
    u64 active_low;
    u64 irr;
    u64 is_level;
    u64 masked;
    u64 reserved_0;
    u64 reserved_1;
    u64 virt_destid_8_14;
    u64 destid_0_7;
    u64 ir_shared_0;
    u64 ir_zero;
    u64 ir_index_15;
    u64 ir_shared_1;
    u64 ir_reserved_0;
    u64 ir_format;
    u64 ir_index_0_14;
    u64 w1;
    u64 w2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    u64 vector;
    u64 delivery_mode;
    u64 dest_mode_logical;
    u64 delivery_status;
    u64 active_low;
    u64 irr;
    u64 is_level;
    u64 masked;
    u64 reserved_0;
    u64 reserved_1;
    u64 virt_destid_8_14;
    u64 destid_0_7;
    u64 ir_shared_0;
    u64 ir_zero;
    u64 ir_index_15;
    u64 ir_shared_1;
    u64 ir_reserved_0;
    u64 ir_format;
    u64 ir_index_0_14;
    u64 w1;
    u64 w2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    u64 vector;
    u64 delivery_mode;
    u64 dest_mode_logical;
    u64 delivery_status;
    u64 active_low;
    u64 irr;
    u64 is_level;
    u64 masked;
    u64 reserved_0;
    u64 reserved_1;
    u64 virt_destid_8_14;
    u64 destid_0_7;
    u64 ir_shared_0;
    u64 ir_zero;
    u64 ir_index_15;
    u64 ir_shared_1;
    u64 ir_reserved_0;
    u64 ir_format;
    u64 ir_index_0_14;
    u64 w1;
    u64 w2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    u64 vector;
    u64 delivery_mode;
    u64 dest_mode_logical;
    u64 delivery_status;
    u64 active_low;
    u64 irr;
    u64 is_level;
    u64 masked;
    u64 reserved_0;
    u64 reserved_1;
    u64 virt_destid_8_14;
    u64 destid_0_7;
    u64 ir_shared_0;
    u64 ir_zero;
    u64 ir_index_15;
    u64 ir_shared_1;
    u64 ir_reserved_0;
    u64 ir_format;
    u64 ir_index_0_14;
    u64 w1;
    u64 w2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    u64 vector;
    u64 delivery_mode;
    u64 dest_mode_logical;
    u64 delivery_status;
    u64 active_low;
    u64 irr;
    u64 is_level;
    u64 masked;
    u64 reserved_0;
    u64 reserved_1;
    u64 virt_destid_8_14;
    u64 destid_0_7;
    u64 ir_shared_0;
    u64 ir_zero;
    u64 ir_index_15;
    u64 ir_shared_1;
    u64 ir_reserved_0;
    u64 ir_format;
    u64 ir_index_0_14;
    u64 w1;
    u64 w2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    u64 vector;
    u64 delivery_mode;
    u64 dest_mode_logical;
    u64 delivery_status;
    u64 active_low;
    u64 irr;
    u64 is_level;
    u64 masked;
    u64 reserved_0;
    u64 reserved_1;
    u64 virt_destid_8_14;
    u64 destid_0_7;
    u64 ir_shared_0;
    u64 ir_zero;
    u64 ir_index_15;
    u64 ir_shared_1;
    u64 ir_reserved_0;
    u64 ir_format;
    u64 ir_index_0_14;
    u64 w1;
    u64 w2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    u64 vector;
    u64 delivery_mode;
    u64 dest_mode_logical;
    u64 delivery_status;
    u64 active_low;
    u64 irr;
    u64 is_level;
    u64 masked;
    u64 reserved_0;
    u64 reserved_1;
    u64 virt_destid_8_14;
    u64 destid_0_7;
    u64 ir_shared_0;
    u64 ir_zero;
    u64 ir_index_15;
    u64 ir_shared_1;
    u64 ir_reserved_0;
    u64 ir_format;
    u64 ir_index_0_14;
    u64 w1;
    u64 w2;
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
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 dest_mode_logical</code>
</li>
<li>
<b>Field added. </b>
<code>u64 active_low</code>
</li>
<li>
<b>Field added. </b>
<code>u64 is_level</code>
</li>
<li>
<b>Field added. </b>
<code>u64 masked</code>
</li>
<li>
<b>Field added. </b>
<code>u64 reserved_0</code>
</li>
<li>
<b>Field added. </b>
<code>u64 reserved_1</code>
</li>
<li>
<b>Field added. </b>
<code>u64 virt_destid_8_14</code>
</li>
<li>
<b>Field added. </b>
<code>u64 destid_0_7</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ir_shared_0</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ir_zero</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ir_index_15</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ir_shared_1</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ir_reserved_0</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ir_format</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ir_index_0_14</code>
</li>
<li>
<b>Field added. </b>
<code>u64 w1</code>
</li>
<li>
<b>Field added. </b>
<code>u64 w2</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 dest_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 polarity</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 trigger</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 mask</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 __reserved_2</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 __reserved_3</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 dest</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 vector</code> ➡️ <code>u64 vector</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 delivery_mode</code> ➡️ <code>u64 delivery_mode</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 delivery_status</code> ➡️ <code>u64 delivery_status</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 irr</code> ➡️ <code>u64 irr</code>
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
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct IO_APIC_route_entry {
    __u32 vector;
    __u32 delivery_mode;
    __u32 dest_mode;
    __u32 delivery_status;
    __u32 polarity;
    __u32 irr;
    __u32 trigger;
    __u32 mask;
    __u32 __reserved_2;
    __u32 __reserved_3;
    __u32 dest;
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
