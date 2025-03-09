# Struct: <code>irte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
    __u128 irte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
    __u128 irte;
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
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u128 irte</code>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct irte {
    __u64 present;
    __u64 fpd;
    __u64 __res0;
    __u64 avail;
    __u64 __res1;
    __u64 pst;
    __u64 vector;
    __u64 __res2;
    __u64 r_present;
    __u64 r_fpd;
    __u64 dst_mode;
    __u64 redir_hint;
    __u64 trigger_mode;
    __u64 dlvry_mode;
    __u64 r_avail;
    __u64 r_res0;
    __u64 r_vector;
    __u64 r_res1;
    __u64 dest_id;
    __u64 p_present;
    __u64 p_fpd;
    __u64 p_res0;
    __u64 p_avail;
    __u64 p_res1;
    __u64 p_urgent;
    __u64 p_pst;
    __u64 p_vector;
    __u64 p_res2;
    __u64 pda_l;
    __u64 low;
    __u64 sid;
    __u64 sq;
    __u64 svt;
    __u64 __res3;
    __u64 p_sid;
    __u64 p_sq;
    __u64 p_svt;
    __u64 p_res3;
    __u64 pda_h;
    __u64 high;
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
