# Struct: <code>svc_version</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct svc_version {
    u32 vs_vers;
    u32 vs_nproc;
    const struct svc_procedure * vs_proc;
    unsigned int * vs_count;
    u32 vs_xdrsize;
    bool vs_hidden;
    bool vs_rpcb_optnl;
    bool vs_need_cong_ctrl;
    int (*)(struct svc_rqst *, __be32 *) vs_dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct svc_version {
    u32 vs_vers;
    u32 vs_nproc;
    const struct svc_procedure * vs_proc;
    unsigned int * vs_count;
    u32 vs_xdrsize;
    bool vs_hidden;
    bool vs_rpcb_optnl;
    bool vs_need_cong_ctrl;
    int (*)(struct svc_rqst *, __be32 *) vs_dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct svc_version {
    u32 vs_vers;
    u32 vs_nproc;
    const struct svc_procedure * vs_proc;
    unsigned int * vs_count;
    u32 vs_xdrsize;
    bool vs_hidden;
    bool vs_rpcb_optnl;
    bool vs_need_cong_ctrl;
    int (*)(struct svc_rqst *, __be32 *) vs_dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct svc_version {
    u32 vs_vers;
    u32 vs_nproc;
    const struct svc_procedure * vs_proc;
    long unsigned int * vs_count;
    u32 vs_xdrsize;
    bool vs_hidden;
    bool vs_rpcb_optnl;
    bool vs_need_cong_ctrl;
    int (*)(struct svc_rqst *) vs_dispatch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct svc_version {
    u32 vs_vers;
    u32 vs_nproc;
    const struct svc_procedure * vs_proc;
    long unsigned int * vs_count;
    u32 vs_xdrsize;
    bool vs_hidden;
    bool vs_rpcb_optnl;
    bool vs_need_cong_ctrl;
    int (*)(struct svc_rqst *) vs_dispatch;
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct svc_version {
    u32 vs_vers;
    u32 vs_nproc;
    const struct svc_procedure * vs_proc;
    unsigned int * vs_count;
    u32 vs_xdrsize;
    bool vs_hidden;
    bool vs_rpcb_optnl;
    bool vs_need_cong_ctrl;
    int (*)(struct svc_rqst *, __be32 *) vs_dispatch;
}
```
</details>
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
<b>Field type changed. </b>
<code>unsigned int * vs_count</code> ➡️ <code>long unsigned int * vs_count</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct svc_rqst *, __be32 *) vs_dispatch</code> ➡️ <code>int (*)(struct svc_rqst *) vs_dispatch</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
