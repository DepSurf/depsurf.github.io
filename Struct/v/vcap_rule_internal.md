# Struct: <code>vcap_rule_internal</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vcap_rule_internal {
    struct vcap_rule data;
    struct list_head list;
    struct vcap_admin * admin;
    struct net_device * ndev;
    struct vcap_control * vctrl;
    u32 sort_key;
    int keyset_sw;
    int actionset_sw;
    int keyset_sw_regs;
    int actionset_sw_regs;
    int size;
    u32 addr;
    u32 counter_id;
    struct vcap_counter counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vcap_rule_internal {
    struct vcap_rule data;
    struct list_head list;
    struct vcap_admin * admin;
    struct net_device * ndev;
    struct vcap_control * vctrl;
    u32 sort_key;
    int keyset_sw;
    int actionset_sw;
    int keyset_sw_regs;
    int actionset_sw_regs;
    int size;
    u32 addr;
    u32 counter_id;
    struct vcap_counter counter;
    enum vcap_rule_state state;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vcap_rule_internal {
    struct vcap_rule data;
    struct list_head list;
    struct vcap_admin * admin;
    struct net_device * ndev;
    struct vcap_control * vctrl;
    u32 sort_key;
    int keyset_sw;
    int actionset_sw;
    int keyset_sw_regs;
    int actionset_sw_regs;
    int size;
    u32 addr;
    u32 counter_id;
    struct vcap_counter counter;
    enum vcap_rule_state state;
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct vcap_rule_internal {
    struct vcap_rule data;
    struct list_head list;
    struct vcap_admin * admin;
    struct net_device * ndev;
    struct vcap_control * vctrl;
    u32 sort_key;
    int keyset_sw;
    int actionset_sw;
    int keyset_sw_regs;
    int actionset_sw_regs;
    int size;
    u32 addr;
    u32 counter_id;
    struct vcap_counter counter;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum vcap_rule_state state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
