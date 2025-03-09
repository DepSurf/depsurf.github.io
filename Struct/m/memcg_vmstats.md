# Struct: <code>memcg_vmstats</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct memcg_vmstats {
    long int[42] state;
    long unsigned int[98] events;
    long int[42] state_pending;
    long unsigned int[98] events_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct memcg_vmstats {
    long int[42] state;
    long unsigned int[100] events;
    long int[42] state_pending;
    long unsigned int[100] events_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct memcg_vmstats {
    long int[48] state;
    long unsigned int[107] events;
    long int[48] state_pending;
    long unsigned int[107] events_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct memcg_vmstats {
    long int[50] state;
    long unsigned int[19] events;
    long int[50] state_pending;
    long unsigned int[19] events_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct memcg_vmstats {
    long int[50] state;
    long unsigned int[19] events;
    long int[50] state_pending;
    long unsigned int[19] events_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct memcg_vmstats {
    long int[53] state;
    long unsigned int[22] events;
    long int[53] state_local;
    long unsigned int[22] events_local;
    long int[53] state_pending;
    long unsigned int[22] events_pending;
    atomic64_t stats_updates;
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct memcg_vmstats {
    long int[42] state;
    long unsigned int[98] events;
    long int[42] state_pending;
    long unsigned int[98] events_pending;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[98] events</code> ➡️ <code>long unsigned int[100] events</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[98] events_pending</code> ➡️ <code>long unsigned int[100] events_pending</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long int[42] state</code> ➡️ <code>long int[48] state</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[100] events</code> ➡️ <code>long unsigned int[107] events</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int[42] state_pending</code> ➡️ <code>long int[48] state_pending</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[100] events_pending</code> ➡️ <code>long unsigned int[107] events_pending</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long int[48] state</code> ➡️ <code>long int[50] state</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[107] events</code> ➡️ <code>long unsigned int[19] events</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int[48] state_pending</code> ➡️ <code>long int[50] state_pending</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[107] events_pending</code> ➡️ <code>long unsigned int[19] events_pending</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long int[53] state_local</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[22] events_local</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t stats_updates</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int[50] state</code> ➡️ <code>long int[53] state</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[19] events</code> ➡️ <code>long unsigned int[22] events</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int[50] state_pending</code> ➡️ <code>long int[53] state_pending</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[19] events_pending</code> ➡️ <code>long unsigned int[22] events_pending</code>
</li>
</ul>
</details>
</li>
</ul>
