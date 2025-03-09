# Struct: <code>nvme_ns</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
struct nvme_ns {
    struct list_head list;
    struct nvme_ctrl * ctrl;
    struct request_queue * queue;
    struct gendisk * disk;
    enum nvme_ana_state ana_state;
    u32 ana_grpid;
    struct list_head siblings;
    struct nvm_dev * ndev;
    struct kref kref;
    struct nvme_ns_head * head;
    int lba_shift;
    u16 ms;
    u16 sgs;
    u32 sws;
    bool ext;
    u8 pi_type;
    long unsigned int flags;
    u16 noiob;
    struct nvme_fault_inject fault_inject;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvme_ns {
    struct list_head list;
    struct nvme_ctrl * ctrl;
    struct request_queue * queue;
    struct gendisk * disk;
    enum nvme_ana_state ana_state;
    u32 ana_grpid;
    struct list_head siblings;
    struct nvm_dev * ndev;
    struct kref kref;
    struct nvme_ns_head * head;
    int lba_shift;
    u16 ms;
    u16 sgs;
    u32 sws;
    bool ext;
    u8 pi_type;
    long unsigned int flags;
    u16 noiob;
    struct nvme_fault_inject fault_inject;
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
struct nvme_ns {
    struct list_head list;
    struct nvme_ctrl * ctrl;
    struct request_queue * queue;
    struct gendisk * disk;
    enum nvme_ana_state ana_state;
    u32 ana_grpid;
    struct list_head siblings;
    struct nvm_dev * ndev;
    struct kref kref;
    struct nvme_ns_head * head;
    int lba_shift;
    u16 ms;
    u16 sgs;
    u32 sws;
    bool ext;
    u8 pi_type;
    long unsigned int flags;
    u16 noiob;
    struct nvme_fault_inject fault_inject;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct nvme_ns {
    struct list_head list;
    struct nvme_ctrl * ctrl;
    struct request_queue * queue;
    struct gendisk * disk;
    enum nvme_ana_state ana_state;
    u32 ana_grpid;
    struct list_head siblings;
    struct nvm_dev * ndev;
    struct kref kref;
    struct nvme_ns_head * head;
    int lba_shift;
    u16 ms;
    u16 sgs;
    u32 sws;
    bool ext;
    u8 pi_type;
    long unsigned int flags;
    u16 noiob;
    struct nvme_fault_inject fault_inject;
}
```
</details>
</li>
</ul>
