# Struct: <code>bpf_link_info</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_link_info {
    __u32 type;
    __u32 id;
    __u32 prog_id;
    struct (anon) raw_tracepoint;
    struct (anon) tracing;
    struct (anon) cgroup;
    struct (anon) netns;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_link_info {
    __u32 type;
    __u32 id;
    __u32 prog_id;
    struct (anon) raw_tracepoint;
    struct (anon) tracing;
    struct (anon) cgroup;
    struct (anon) iter;
    struct (anon) netns;
    struct (anon) xdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_link_info {
    __u32 type;
    __u32 id;
    __u32 prog_id;
    struct (anon) raw_tracepoint;
    struct (anon) tracing;
    struct (anon) cgroup;
    struct (anon) iter;
    struct (anon) netns;
    struct (anon) xdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_link_info {
    __u32 type;
    __u32 id;
    __u32 prog_id;
    struct (anon) raw_tracepoint;
    struct (anon) tracing;
    struct (anon) cgroup;
    struct (anon) iter;
    struct (anon) netns;
    struct (anon) xdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_link_info {
    __u32 type;
    __u32 id;
    __u32 prog_id;
    struct (anon) raw_tracepoint;
    struct (anon) tracing;
    struct (anon) cgroup;
    struct (anon) iter;
    struct (anon) netns;
    struct (anon) xdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_link_info {
    __u32 type;
    __u32 id;
    __u32 prog_id;
    struct (anon) raw_tracepoint;
    struct (anon) tracing;
    struct (anon) cgroup;
    struct (anon) iter;
    struct (anon) netns;
    struct (anon) xdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_link_info {
    __u32 type;
    __u32 id;
    __u32 prog_id;
    struct (anon) raw_tracepoint;
    struct (anon) tracing;
    struct (anon) cgroup;
    struct (anon) iter;
    struct (anon) netns;
    struct (anon) xdp;
    struct (anon) struct_ops;
    struct (anon) netfilter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_link_info {
    __u32 type;
    __u32 id;
    __u32 prog_id;
    struct (anon) raw_tracepoint;
    struct (anon) tracing;
    struct (anon) cgroup;
    struct (anon) iter;
    struct (anon) netns;
    struct (anon) xdp;
    struct (anon) struct_ops;
    struct (anon) netfilter;
    struct (anon) kprobe_multi;
    struct (anon) uprobe_multi;
    struct (anon) perf_event;
    struct (anon) tcx;
    struct (anon) netkit;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct bpf_link_info {
    __u32 type;
    __u32 id;
    __u32 prog_id;
    struct (anon) raw_tracepoint;
    struct (anon) tracing;
    struct (anon) cgroup;
    struct (anon) netns;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) iter</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) xdp</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) struct_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) netfilter</code>
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
<code>struct (anon) kprobe_multi</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) uprobe_multi</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) perf_event</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) tcx</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) netkit</code>
</li>
</ul>
</details>
</li>
</ul>
