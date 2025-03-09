# Struct: <code>ethtool_link_ext_state_info</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_ext_state_info {
    enum ethtool_link_ext_state link_ext_state;
    enum ethtool_link_ext_substate_autoneg autoneg;
    enum ethtool_link_ext_substate_link_training link_training;
    enum ethtool_link_ext_substate_link_logical_mismatch link_logical_mismatch;
    enum ethtool_link_ext_substate_bad_signal_integrity bad_signal_integrity;
    enum ethtool_link_ext_substate_cable_issue cable_issue;
    u8 __link_ext_substate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_ext_state_info {
    enum ethtool_link_ext_state link_ext_state;
    enum ethtool_link_ext_substate_autoneg autoneg;
    enum ethtool_link_ext_substate_link_training link_training;
    enum ethtool_link_ext_substate_link_logical_mismatch link_logical_mismatch;
    enum ethtool_link_ext_substate_bad_signal_integrity bad_signal_integrity;
    enum ethtool_link_ext_substate_cable_issue cable_issue;
    u8 __link_ext_substate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_ext_state_info {
    enum ethtool_link_ext_state link_ext_state;
    enum ethtool_link_ext_substate_autoneg autoneg;
    enum ethtool_link_ext_substate_link_training link_training;
    enum ethtool_link_ext_substate_link_logical_mismatch link_logical_mismatch;
    enum ethtool_link_ext_substate_bad_signal_integrity bad_signal_integrity;
    enum ethtool_link_ext_substate_cable_issue cable_issue;
    u32 __link_ext_substate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_ext_state_info {
    enum ethtool_link_ext_state link_ext_state;
    enum ethtool_link_ext_substate_autoneg autoneg;
    enum ethtool_link_ext_substate_link_training link_training;
    enum ethtool_link_ext_substate_link_logical_mismatch link_logical_mismatch;
    enum ethtool_link_ext_substate_bad_signal_integrity bad_signal_integrity;
    enum ethtool_link_ext_substate_cable_issue cable_issue;
    enum ethtool_link_ext_substate_module module;
    u32 __link_ext_substate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_ext_state_info {
    enum ethtool_link_ext_state link_ext_state;
    enum ethtool_link_ext_substate_autoneg autoneg;
    enum ethtool_link_ext_substate_link_training link_training;
    enum ethtool_link_ext_substate_link_logical_mismatch link_logical_mismatch;
    enum ethtool_link_ext_substate_bad_signal_integrity bad_signal_integrity;
    enum ethtool_link_ext_substate_cable_issue cable_issue;
    enum ethtool_link_ext_substate_module module;
    u32 __link_ext_substate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_ext_state_info {
    enum ethtool_link_ext_state link_ext_state;
    enum ethtool_link_ext_substate_autoneg autoneg;
    enum ethtool_link_ext_substate_link_training link_training;
    enum ethtool_link_ext_substate_link_logical_mismatch link_logical_mismatch;
    enum ethtool_link_ext_substate_bad_signal_integrity bad_signal_integrity;
    enum ethtool_link_ext_substate_cable_issue cable_issue;
    enum ethtool_link_ext_substate_module module;
    u32 __link_ext_substate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ethtool_link_ext_state_info {
    enum ethtool_link_ext_state link_ext_state;
    enum ethtool_link_ext_substate_autoneg autoneg;
    enum ethtool_link_ext_substate_link_training link_training;
    enum ethtool_link_ext_substate_link_logical_mismatch link_logical_mismatch;
    enum ethtool_link_ext_substate_bad_signal_integrity bad_signal_integrity;
    enum ethtool_link_ext_substate_cable_issue cable_issue;
    enum ethtool_link_ext_substate_module module;
    u32 __link_ext_substate;
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct ethtool_link_ext_state_info {
    enum ethtool_link_ext_state link_ext_state;
    enum ethtool_link_ext_substate_autoneg autoneg;
    enum ethtool_link_ext_substate_link_training link_training;
    enum ethtool_link_ext_substate_link_logical_mismatch link_logical_mismatch;
    enum ethtool_link_ext_substate_bad_signal_integrity bad_signal_integrity;
    enum ethtool_link_ext_substate_cable_issue cable_issue;
    u8 __link_ext_substate;
}
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u8 __link_ext_substate</code> ➡️ <code>u32 __link_ext_substate</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum ethtool_link_ext_substate_module module</code>
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
