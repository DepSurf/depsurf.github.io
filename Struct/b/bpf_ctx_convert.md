# Struct: <code>bpf_ctx_convert</code>

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
struct bpf_ctx_convert {
    struct __sk_buff BPF_PROG_TYPE_SOCKET_FILTER_prog;
    struct sk_buff BPF_PROG_TYPE_SOCKET_FILTER_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_CLS_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_CLS_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_ACT_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_ACT_kern;
    struct xdp_md BPF_PROG_TYPE_XDP_prog;
    struct xdp_buff BPF_PROG_TYPE_XDP_kern;
    struct __sk_buff BPF_PROG_TYPE_CGROUP_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_CGROUP_SKB_kern;
    struct bpf_sock BPF_PROG_TYPE_CGROUP_SOCK_prog;
    struct sock BPF_PROG_TYPE_CGROUP_SOCK_kern;
    struct bpf_sock_addr BPF_PROG_TYPE_CGROUP_SOCK_ADDR_prog;
    struct bpf_sock_addr_kern BPF_PROG_TYPE_CGROUP_SOCK_ADDR_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_IN_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_IN_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_OUT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_OUT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_XMIT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_XMIT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_kern;
    struct bpf_sock_ops BPF_PROG_TYPE_SOCK_OPS_prog;
    struct bpf_sock_ops_kern BPF_PROG_TYPE_SOCK_OPS_kern;
    struct __sk_buff BPF_PROG_TYPE_SK_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_SK_SKB_kern;
    struct sk_msg_md BPF_PROG_TYPE_SK_MSG_prog;
    struct sk_msg BPF_PROG_TYPE_SK_MSG_kern;
    struct __sk_buff BPF_PROG_TYPE_FLOW_DISSECTOR_prog;
    struct bpf_flow_dissector BPF_PROG_TYPE_FLOW_DISSECTOR_kern;
    bpf_user_pt_regs_t BPF_PROG_TYPE_KPROBE_prog;
    struct pt_regs BPF_PROG_TYPE_KPROBE_kern;
    __u64 BPF_PROG_TYPE_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_TRACEPOINT_kern;
    struct bpf_perf_event_data BPF_PROG_TYPE_PERF_EVENT_prog;
    struct bpf_perf_event_data_kern BPF_PROG_TYPE_PERF_EVENT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_kern;
    void * BPF_PROG_TYPE_TRACING_prog;
    void * BPF_PROG_TYPE_TRACING_kern;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_prog;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_kern;
    struct bpf_sysctl BPF_PROG_TYPE_CGROUP_SYSCTL_prog;
    struct bpf_sysctl_kern BPF_PROG_TYPE_CGROUP_SYSCTL_kern;
    struct bpf_sockopt BPF_PROG_TYPE_CGROUP_SOCKOPT_prog;
    struct bpf_sockopt_kern BPF_PROG_TYPE_CGROUP_SOCKOPT_kern;
    struct sk_reuseport_md BPF_PROG_TYPE_SK_REUSEPORT_prog;
    struct sk_reuseport_kern BPF_PROG_TYPE_SK_REUSEPORT_kern;
    void * BPF_PROG_TYPE_STRUCT_OPS_prog;
    void * BPF_PROG_TYPE_STRUCT_OPS_kern;
    void * BPF_PROG_TYPE_EXT_prog;
    void * BPF_PROG_TYPE_EXT_kern;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_ctx_convert {
    struct __sk_buff BPF_PROG_TYPE_SOCKET_FILTER_prog;
    struct sk_buff BPF_PROG_TYPE_SOCKET_FILTER_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_CLS_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_CLS_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_ACT_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_ACT_kern;
    struct xdp_md BPF_PROG_TYPE_XDP_prog;
    struct xdp_buff BPF_PROG_TYPE_XDP_kern;
    struct __sk_buff BPF_PROG_TYPE_CGROUP_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_CGROUP_SKB_kern;
    struct bpf_sock BPF_PROG_TYPE_CGROUP_SOCK_prog;
    struct sock BPF_PROG_TYPE_CGROUP_SOCK_kern;
    struct bpf_sock_addr BPF_PROG_TYPE_CGROUP_SOCK_ADDR_prog;
    struct bpf_sock_addr_kern BPF_PROG_TYPE_CGROUP_SOCK_ADDR_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_IN_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_IN_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_OUT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_OUT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_XMIT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_XMIT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_kern;
    struct bpf_sock_ops BPF_PROG_TYPE_SOCK_OPS_prog;
    struct bpf_sock_ops_kern BPF_PROG_TYPE_SOCK_OPS_kern;
    struct __sk_buff BPF_PROG_TYPE_SK_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_SK_SKB_kern;
    struct sk_msg_md BPF_PROG_TYPE_SK_MSG_prog;
    struct sk_msg BPF_PROG_TYPE_SK_MSG_kern;
    struct __sk_buff BPF_PROG_TYPE_FLOW_DISSECTOR_prog;
    struct bpf_flow_dissector BPF_PROG_TYPE_FLOW_DISSECTOR_kern;
    bpf_user_pt_regs_t BPF_PROG_TYPE_KPROBE_prog;
    struct pt_regs BPF_PROG_TYPE_KPROBE_kern;
    __u64 BPF_PROG_TYPE_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_TRACEPOINT_kern;
    struct bpf_perf_event_data BPF_PROG_TYPE_PERF_EVENT_prog;
    struct bpf_perf_event_data_kern BPF_PROG_TYPE_PERF_EVENT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_kern;
    void * BPF_PROG_TYPE_TRACING_prog;
    void * BPF_PROG_TYPE_TRACING_kern;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_prog;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_kern;
    struct bpf_sysctl BPF_PROG_TYPE_CGROUP_SYSCTL_prog;
    struct bpf_sysctl_kern BPF_PROG_TYPE_CGROUP_SYSCTL_kern;
    struct bpf_sockopt BPF_PROG_TYPE_CGROUP_SOCKOPT_prog;
    struct bpf_sockopt_kern BPF_PROG_TYPE_CGROUP_SOCKOPT_kern;
    struct sk_reuseport_md BPF_PROG_TYPE_SK_REUSEPORT_prog;
    struct sk_reuseport_kern BPF_PROG_TYPE_SK_REUSEPORT_kern;
    struct bpf_sk_lookup BPF_PROG_TYPE_SK_LOOKUP_prog;
    struct bpf_sk_lookup_kern BPF_PROG_TYPE_SK_LOOKUP_kern;
    void * BPF_PROG_TYPE_STRUCT_OPS_prog;
    void * BPF_PROG_TYPE_STRUCT_OPS_kern;
    void * BPF_PROG_TYPE_EXT_prog;
    void * BPF_PROG_TYPE_EXT_kern;
    void * BPF_PROG_TYPE_LSM_prog;
    void * BPF_PROG_TYPE_LSM_kern;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_ctx_convert {
    struct __sk_buff BPF_PROG_TYPE_SOCKET_FILTER_prog;
    struct sk_buff BPF_PROG_TYPE_SOCKET_FILTER_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_CLS_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_CLS_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_ACT_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_ACT_kern;
    struct xdp_md BPF_PROG_TYPE_XDP_prog;
    struct xdp_buff BPF_PROG_TYPE_XDP_kern;
    struct __sk_buff BPF_PROG_TYPE_CGROUP_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_CGROUP_SKB_kern;
    struct bpf_sock BPF_PROG_TYPE_CGROUP_SOCK_prog;
    struct sock BPF_PROG_TYPE_CGROUP_SOCK_kern;
    struct bpf_sock_addr BPF_PROG_TYPE_CGROUP_SOCK_ADDR_prog;
    struct bpf_sock_addr_kern BPF_PROG_TYPE_CGROUP_SOCK_ADDR_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_IN_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_IN_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_OUT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_OUT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_XMIT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_XMIT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_kern;
    struct bpf_sock_ops BPF_PROG_TYPE_SOCK_OPS_prog;
    struct bpf_sock_ops_kern BPF_PROG_TYPE_SOCK_OPS_kern;
    struct __sk_buff BPF_PROG_TYPE_SK_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_SK_SKB_kern;
    struct sk_msg_md BPF_PROG_TYPE_SK_MSG_prog;
    struct sk_msg BPF_PROG_TYPE_SK_MSG_kern;
    struct __sk_buff BPF_PROG_TYPE_FLOW_DISSECTOR_prog;
    struct bpf_flow_dissector BPF_PROG_TYPE_FLOW_DISSECTOR_kern;
    bpf_user_pt_regs_t BPF_PROG_TYPE_KPROBE_prog;
    struct pt_regs BPF_PROG_TYPE_KPROBE_kern;
    __u64 BPF_PROG_TYPE_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_TRACEPOINT_kern;
    struct bpf_perf_event_data BPF_PROG_TYPE_PERF_EVENT_prog;
    struct bpf_perf_event_data_kern BPF_PROG_TYPE_PERF_EVENT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_kern;
    void * BPF_PROG_TYPE_TRACING_prog;
    void * BPF_PROG_TYPE_TRACING_kern;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_prog;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_kern;
    struct bpf_sysctl BPF_PROG_TYPE_CGROUP_SYSCTL_prog;
    struct bpf_sysctl_kern BPF_PROG_TYPE_CGROUP_SYSCTL_kern;
    struct bpf_sockopt BPF_PROG_TYPE_CGROUP_SOCKOPT_prog;
    struct bpf_sockopt_kern BPF_PROG_TYPE_CGROUP_SOCKOPT_kern;
    struct sk_reuseport_md BPF_PROG_TYPE_SK_REUSEPORT_prog;
    struct sk_reuseport_kern BPF_PROG_TYPE_SK_REUSEPORT_kern;
    struct bpf_sk_lookup BPF_PROG_TYPE_SK_LOOKUP_prog;
    struct bpf_sk_lookup_kern BPF_PROG_TYPE_SK_LOOKUP_kern;
    void * BPF_PROG_TYPE_STRUCT_OPS_prog;
    void * BPF_PROG_TYPE_STRUCT_OPS_kern;
    void * BPF_PROG_TYPE_EXT_prog;
    void * BPF_PROG_TYPE_EXT_kern;
    void * BPF_PROG_TYPE_LSM_prog;
    void * BPF_PROG_TYPE_LSM_kern;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_ctx_convert {
    struct __sk_buff BPF_PROG_TYPE_SOCKET_FILTER_prog;
    struct sk_buff BPF_PROG_TYPE_SOCKET_FILTER_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_CLS_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_CLS_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_ACT_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_ACT_kern;
    struct xdp_md BPF_PROG_TYPE_XDP_prog;
    struct xdp_buff BPF_PROG_TYPE_XDP_kern;
    struct __sk_buff BPF_PROG_TYPE_CGROUP_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_CGROUP_SKB_kern;
    struct bpf_sock BPF_PROG_TYPE_CGROUP_SOCK_prog;
    struct sock BPF_PROG_TYPE_CGROUP_SOCK_kern;
    struct bpf_sock_addr BPF_PROG_TYPE_CGROUP_SOCK_ADDR_prog;
    struct bpf_sock_addr_kern BPF_PROG_TYPE_CGROUP_SOCK_ADDR_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_IN_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_IN_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_OUT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_OUT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_XMIT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_XMIT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_kern;
    struct bpf_sock_ops BPF_PROG_TYPE_SOCK_OPS_prog;
    struct bpf_sock_ops_kern BPF_PROG_TYPE_SOCK_OPS_kern;
    struct __sk_buff BPF_PROG_TYPE_SK_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_SK_SKB_kern;
    struct sk_msg_md BPF_PROG_TYPE_SK_MSG_prog;
    struct sk_msg BPF_PROG_TYPE_SK_MSG_kern;
    struct __sk_buff BPF_PROG_TYPE_FLOW_DISSECTOR_prog;
    struct bpf_flow_dissector BPF_PROG_TYPE_FLOW_DISSECTOR_kern;
    bpf_user_pt_regs_t BPF_PROG_TYPE_KPROBE_prog;
    struct pt_regs BPF_PROG_TYPE_KPROBE_kern;
    __u64 BPF_PROG_TYPE_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_TRACEPOINT_kern;
    struct bpf_perf_event_data BPF_PROG_TYPE_PERF_EVENT_prog;
    struct bpf_perf_event_data_kern BPF_PROG_TYPE_PERF_EVENT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_kern;
    void * BPF_PROG_TYPE_TRACING_prog;
    void * BPF_PROG_TYPE_TRACING_kern;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_prog;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_kern;
    struct bpf_sysctl BPF_PROG_TYPE_CGROUP_SYSCTL_prog;
    struct bpf_sysctl_kern BPF_PROG_TYPE_CGROUP_SYSCTL_kern;
    struct bpf_sockopt BPF_PROG_TYPE_CGROUP_SOCKOPT_prog;
    struct bpf_sockopt_kern BPF_PROG_TYPE_CGROUP_SOCKOPT_kern;
    struct sk_reuseport_md BPF_PROG_TYPE_SK_REUSEPORT_prog;
    struct sk_reuseport_kern BPF_PROG_TYPE_SK_REUSEPORT_kern;
    struct bpf_sk_lookup BPF_PROG_TYPE_SK_LOOKUP_prog;
    struct bpf_sk_lookup_kern BPF_PROG_TYPE_SK_LOOKUP_kern;
    void * BPF_PROG_TYPE_STRUCT_OPS_prog;
    void * BPF_PROG_TYPE_STRUCT_OPS_kern;
    void * BPF_PROG_TYPE_EXT_prog;
    void * BPF_PROG_TYPE_EXT_kern;
    void * BPF_PROG_TYPE_LSM_prog;
    void * BPF_PROG_TYPE_LSM_kern;
    void * BPF_PROG_TYPE_SYSCALL_prog;
    void * BPF_PROG_TYPE_SYSCALL_kern;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_ctx_convert {
    struct __sk_buff BPF_PROG_TYPE_SOCKET_FILTER_prog;
    struct sk_buff BPF_PROG_TYPE_SOCKET_FILTER_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_CLS_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_CLS_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_ACT_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_ACT_kern;
    struct xdp_md BPF_PROG_TYPE_XDP_prog;
    struct xdp_buff BPF_PROG_TYPE_XDP_kern;
    struct __sk_buff BPF_PROG_TYPE_CGROUP_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_CGROUP_SKB_kern;
    struct bpf_sock BPF_PROG_TYPE_CGROUP_SOCK_prog;
    struct sock BPF_PROG_TYPE_CGROUP_SOCK_kern;
    struct bpf_sock_addr BPF_PROG_TYPE_CGROUP_SOCK_ADDR_prog;
    struct bpf_sock_addr_kern BPF_PROG_TYPE_CGROUP_SOCK_ADDR_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_IN_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_IN_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_OUT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_OUT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_XMIT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_XMIT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_kern;
    struct bpf_sock_ops BPF_PROG_TYPE_SOCK_OPS_prog;
    struct bpf_sock_ops_kern BPF_PROG_TYPE_SOCK_OPS_kern;
    struct __sk_buff BPF_PROG_TYPE_SK_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_SK_SKB_kern;
    struct sk_msg_md BPF_PROG_TYPE_SK_MSG_prog;
    struct sk_msg BPF_PROG_TYPE_SK_MSG_kern;
    struct __sk_buff BPF_PROG_TYPE_FLOW_DISSECTOR_prog;
    struct bpf_flow_dissector BPF_PROG_TYPE_FLOW_DISSECTOR_kern;
    bpf_user_pt_regs_t BPF_PROG_TYPE_KPROBE_prog;
    struct pt_regs BPF_PROG_TYPE_KPROBE_kern;
    __u64 BPF_PROG_TYPE_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_TRACEPOINT_kern;
    struct bpf_perf_event_data BPF_PROG_TYPE_PERF_EVENT_prog;
    struct bpf_perf_event_data_kern BPF_PROG_TYPE_PERF_EVENT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_kern;
    void * BPF_PROG_TYPE_TRACING_prog;
    void * BPF_PROG_TYPE_TRACING_kern;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_prog;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_kern;
    struct bpf_sysctl BPF_PROG_TYPE_CGROUP_SYSCTL_prog;
    struct bpf_sysctl_kern BPF_PROG_TYPE_CGROUP_SYSCTL_kern;
    struct bpf_sockopt BPF_PROG_TYPE_CGROUP_SOCKOPT_prog;
    struct bpf_sockopt_kern BPF_PROG_TYPE_CGROUP_SOCKOPT_kern;
    struct sk_reuseport_md BPF_PROG_TYPE_SK_REUSEPORT_prog;
    struct sk_reuseport_kern BPF_PROG_TYPE_SK_REUSEPORT_kern;
    struct bpf_sk_lookup BPF_PROG_TYPE_SK_LOOKUP_prog;
    struct bpf_sk_lookup_kern BPF_PROG_TYPE_SK_LOOKUP_kern;
    void * BPF_PROG_TYPE_STRUCT_OPS_prog;
    void * BPF_PROG_TYPE_STRUCT_OPS_kern;
    void * BPF_PROG_TYPE_EXT_prog;
    void * BPF_PROG_TYPE_EXT_kern;
    void * BPF_PROG_TYPE_LSM_prog;
    void * BPF_PROG_TYPE_LSM_kern;
    void * BPF_PROG_TYPE_SYSCALL_prog;
    void * BPF_PROG_TYPE_SYSCALL_kern;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_ctx_convert {
    struct __sk_buff BPF_PROG_TYPE_SOCKET_FILTER_prog;
    struct sk_buff BPF_PROG_TYPE_SOCKET_FILTER_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_CLS_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_CLS_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_ACT_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_ACT_kern;
    struct xdp_md BPF_PROG_TYPE_XDP_prog;
    struct xdp_buff BPF_PROG_TYPE_XDP_kern;
    struct __sk_buff BPF_PROG_TYPE_CGROUP_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_CGROUP_SKB_kern;
    struct bpf_sock BPF_PROG_TYPE_CGROUP_SOCK_prog;
    struct sock BPF_PROG_TYPE_CGROUP_SOCK_kern;
    struct bpf_sock_addr BPF_PROG_TYPE_CGROUP_SOCK_ADDR_prog;
    struct bpf_sock_addr_kern BPF_PROG_TYPE_CGROUP_SOCK_ADDR_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_IN_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_IN_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_OUT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_OUT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_XMIT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_XMIT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_kern;
    struct bpf_sock_ops BPF_PROG_TYPE_SOCK_OPS_prog;
    struct bpf_sock_ops_kern BPF_PROG_TYPE_SOCK_OPS_kern;
    struct __sk_buff BPF_PROG_TYPE_SK_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_SK_SKB_kern;
    struct sk_msg_md BPF_PROG_TYPE_SK_MSG_prog;
    struct sk_msg BPF_PROG_TYPE_SK_MSG_kern;
    struct __sk_buff BPF_PROG_TYPE_FLOW_DISSECTOR_prog;
    struct bpf_flow_dissector BPF_PROG_TYPE_FLOW_DISSECTOR_kern;
    bpf_user_pt_regs_t BPF_PROG_TYPE_KPROBE_prog;
    struct pt_regs BPF_PROG_TYPE_KPROBE_kern;
    __u64 BPF_PROG_TYPE_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_TRACEPOINT_kern;
    struct bpf_perf_event_data BPF_PROG_TYPE_PERF_EVENT_prog;
    struct bpf_perf_event_data_kern BPF_PROG_TYPE_PERF_EVENT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_kern;
    void * BPF_PROG_TYPE_TRACING_prog;
    void * BPF_PROG_TYPE_TRACING_kern;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_prog;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_kern;
    struct bpf_sysctl BPF_PROG_TYPE_CGROUP_SYSCTL_prog;
    struct bpf_sysctl_kern BPF_PROG_TYPE_CGROUP_SYSCTL_kern;
    struct bpf_sockopt BPF_PROG_TYPE_CGROUP_SOCKOPT_prog;
    struct bpf_sockopt_kern BPF_PROG_TYPE_CGROUP_SOCKOPT_kern;
    struct sk_reuseport_md BPF_PROG_TYPE_SK_REUSEPORT_prog;
    struct sk_reuseport_kern BPF_PROG_TYPE_SK_REUSEPORT_kern;
    struct bpf_sk_lookup BPF_PROG_TYPE_SK_LOOKUP_prog;
    struct bpf_sk_lookup_kern BPF_PROG_TYPE_SK_LOOKUP_kern;
    void * BPF_PROG_TYPE_STRUCT_OPS_prog;
    void * BPF_PROG_TYPE_STRUCT_OPS_kern;
    void * BPF_PROG_TYPE_EXT_prog;
    void * BPF_PROG_TYPE_EXT_kern;
    void * BPF_PROG_TYPE_LSM_prog;
    void * BPF_PROG_TYPE_LSM_kern;
    void * BPF_PROG_TYPE_SYSCALL_prog;
    void * BPF_PROG_TYPE_SYSCALL_kern;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_ctx_convert {
    struct __sk_buff BPF_PROG_TYPE_SOCKET_FILTER_prog;
    struct sk_buff BPF_PROG_TYPE_SOCKET_FILTER_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_CLS_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_CLS_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_ACT_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_ACT_kern;
    struct xdp_md BPF_PROG_TYPE_XDP_prog;
    struct xdp_buff BPF_PROG_TYPE_XDP_kern;
    struct __sk_buff BPF_PROG_TYPE_CGROUP_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_CGROUP_SKB_kern;
    struct bpf_sock BPF_PROG_TYPE_CGROUP_SOCK_prog;
    struct sock BPF_PROG_TYPE_CGROUP_SOCK_kern;
    struct bpf_sock_addr BPF_PROG_TYPE_CGROUP_SOCK_ADDR_prog;
    struct bpf_sock_addr_kern BPF_PROG_TYPE_CGROUP_SOCK_ADDR_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_IN_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_IN_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_OUT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_OUT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_XMIT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_XMIT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_kern;
    struct bpf_sock_ops BPF_PROG_TYPE_SOCK_OPS_prog;
    struct bpf_sock_ops_kern BPF_PROG_TYPE_SOCK_OPS_kern;
    struct __sk_buff BPF_PROG_TYPE_SK_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_SK_SKB_kern;
    struct sk_msg_md BPF_PROG_TYPE_SK_MSG_prog;
    struct sk_msg BPF_PROG_TYPE_SK_MSG_kern;
    struct __sk_buff BPF_PROG_TYPE_FLOW_DISSECTOR_prog;
    struct bpf_flow_dissector BPF_PROG_TYPE_FLOW_DISSECTOR_kern;
    bpf_user_pt_regs_t BPF_PROG_TYPE_KPROBE_prog;
    struct pt_regs BPF_PROG_TYPE_KPROBE_kern;
    __u64 BPF_PROG_TYPE_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_TRACEPOINT_kern;
    struct bpf_perf_event_data BPF_PROG_TYPE_PERF_EVENT_prog;
    struct bpf_perf_event_data_kern BPF_PROG_TYPE_PERF_EVENT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_kern;
    void * BPF_PROG_TYPE_TRACING_prog;
    void * BPF_PROG_TYPE_TRACING_kern;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_prog;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_kern;
    struct bpf_sysctl BPF_PROG_TYPE_CGROUP_SYSCTL_prog;
    struct bpf_sysctl_kern BPF_PROG_TYPE_CGROUP_SYSCTL_kern;
    struct bpf_sockopt BPF_PROG_TYPE_CGROUP_SOCKOPT_prog;
    struct bpf_sockopt_kern BPF_PROG_TYPE_CGROUP_SOCKOPT_kern;
    struct sk_reuseport_md BPF_PROG_TYPE_SK_REUSEPORT_prog;
    struct sk_reuseport_kern BPF_PROG_TYPE_SK_REUSEPORT_kern;
    struct bpf_sk_lookup BPF_PROG_TYPE_SK_LOOKUP_prog;
    struct bpf_sk_lookup_kern BPF_PROG_TYPE_SK_LOOKUP_kern;
    void * BPF_PROG_TYPE_STRUCT_OPS_prog;
    void * BPF_PROG_TYPE_STRUCT_OPS_kern;
    void * BPF_PROG_TYPE_EXT_prog;
    void * BPF_PROG_TYPE_EXT_kern;
    void * BPF_PROG_TYPE_LSM_prog;
    void * BPF_PROG_TYPE_LSM_kern;
    void * BPF_PROG_TYPE_SYSCALL_prog;
    void * BPF_PROG_TYPE_SYSCALL_kern;
    struct bpf_nf_ctx BPF_PROG_TYPE_NETFILTER_prog;
    struct bpf_nf_ctx BPF_PROG_TYPE_NETFILTER_kern;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_ctx_convert {
    struct __sk_buff BPF_PROG_TYPE_SOCKET_FILTER_prog;
    struct sk_buff BPF_PROG_TYPE_SOCKET_FILTER_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_CLS_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_CLS_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_ACT_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_ACT_kern;
    struct xdp_md BPF_PROG_TYPE_XDP_prog;
    struct xdp_buff BPF_PROG_TYPE_XDP_kern;
    struct __sk_buff BPF_PROG_TYPE_CGROUP_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_CGROUP_SKB_kern;
    struct bpf_sock BPF_PROG_TYPE_CGROUP_SOCK_prog;
    struct sock BPF_PROG_TYPE_CGROUP_SOCK_kern;
    struct bpf_sock_addr BPF_PROG_TYPE_CGROUP_SOCK_ADDR_prog;
    struct bpf_sock_addr_kern BPF_PROG_TYPE_CGROUP_SOCK_ADDR_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_IN_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_IN_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_OUT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_OUT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_XMIT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_XMIT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_kern;
    struct bpf_sock_ops BPF_PROG_TYPE_SOCK_OPS_prog;
    struct bpf_sock_ops_kern BPF_PROG_TYPE_SOCK_OPS_kern;
    struct __sk_buff BPF_PROG_TYPE_SK_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_SK_SKB_kern;
    struct sk_msg_md BPF_PROG_TYPE_SK_MSG_prog;
    struct sk_msg BPF_PROG_TYPE_SK_MSG_kern;
    struct __sk_buff BPF_PROG_TYPE_FLOW_DISSECTOR_prog;
    struct bpf_flow_dissector BPF_PROG_TYPE_FLOW_DISSECTOR_kern;
    bpf_user_pt_regs_t BPF_PROG_TYPE_KPROBE_prog;
    struct pt_regs BPF_PROG_TYPE_KPROBE_kern;
    __u64 BPF_PROG_TYPE_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_TRACEPOINT_kern;
    struct bpf_perf_event_data BPF_PROG_TYPE_PERF_EVENT_prog;
    struct bpf_perf_event_data_kern BPF_PROG_TYPE_PERF_EVENT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_kern;
    void * BPF_PROG_TYPE_TRACING_prog;
    void * BPF_PROG_TYPE_TRACING_kern;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_prog;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_kern;
    struct bpf_sysctl BPF_PROG_TYPE_CGROUP_SYSCTL_prog;
    struct bpf_sysctl_kern BPF_PROG_TYPE_CGROUP_SYSCTL_kern;
    struct bpf_sockopt BPF_PROG_TYPE_CGROUP_SOCKOPT_prog;
    struct bpf_sockopt_kern BPF_PROG_TYPE_CGROUP_SOCKOPT_kern;
    struct sk_reuseport_md BPF_PROG_TYPE_SK_REUSEPORT_prog;
    struct sk_reuseport_kern BPF_PROG_TYPE_SK_REUSEPORT_kern;
    struct bpf_sk_lookup BPF_PROG_TYPE_SK_LOOKUP_prog;
    struct bpf_sk_lookup_kern BPF_PROG_TYPE_SK_LOOKUP_kern;
    void * BPF_PROG_TYPE_STRUCT_OPS_prog;
    void * BPF_PROG_TYPE_STRUCT_OPS_kern;
    void * BPF_PROG_TYPE_EXT_prog;
    void * BPF_PROG_TYPE_EXT_kern;
    void * BPF_PROG_TYPE_LSM_prog;
    void * BPF_PROG_TYPE_LSM_kern;
    void * BPF_PROG_TYPE_SYSCALL_prog;
    void * BPF_PROG_TYPE_SYSCALL_kern;
    struct bpf_nf_ctx BPF_PROG_TYPE_NETFILTER_prog;
    struct bpf_nf_ctx BPF_PROG_TYPE_NETFILTER_kern;
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
struct bpf_ctx_convert {
    struct __sk_buff BPF_PROG_TYPE_SOCKET_FILTER_prog;
    struct sk_buff BPF_PROG_TYPE_SOCKET_FILTER_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_CLS_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_CLS_kern;
    struct __sk_buff BPF_PROG_TYPE_SCHED_ACT_prog;
    struct sk_buff BPF_PROG_TYPE_SCHED_ACT_kern;
    struct xdp_md BPF_PROG_TYPE_XDP_prog;
    struct xdp_buff BPF_PROG_TYPE_XDP_kern;
    struct __sk_buff BPF_PROG_TYPE_CGROUP_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_CGROUP_SKB_kern;
    struct bpf_sock BPF_PROG_TYPE_CGROUP_SOCK_prog;
    struct sock BPF_PROG_TYPE_CGROUP_SOCK_kern;
    struct bpf_sock_addr BPF_PROG_TYPE_CGROUP_SOCK_ADDR_prog;
    struct bpf_sock_addr_kern BPF_PROG_TYPE_CGROUP_SOCK_ADDR_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_IN_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_IN_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_OUT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_OUT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_XMIT_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_XMIT_kern;
    struct __sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_prog;
    struct sk_buff BPF_PROG_TYPE_LWT_SEG6LOCAL_kern;
    struct bpf_sock_ops BPF_PROG_TYPE_SOCK_OPS_prog;
    struct bpf_sock_ops_kern BPF_PROG_TYPE_SOCK_OPS_kern;
    struct __sk_buff BPF_PROG_TYPE_SK_SKB_prog;
    struct sk_buff BPF_PROG_TYPE_SK_SKB_kern;
    struct sk_msg_md BPF_PROG_TYPE_SK_MSG_prog;
    struct sk_msg BPF_PROG_TYPE_SK_MSG_kern;
    struct __sk_buff BPF_PROG_TYPE_FLOW_DISSECTOR_prog;
    struct bpf_flow_dissector BPF_PROG_TYPE_FLOW_DISSECTOR_kern;
    bpf_user_pt_regs_t BPF_PROG_TYPE_KPROBE_prog;
    struct pt_regs BPF_PROG_TYPE_KPROBE_kern;
    __u64 BPF_PROG_TYPE_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_TRACEPOINT_kern;
    struct bpf_perf_event_data BPF_PROG_TYPE_PERF_EVENT_prog;
    struct bpf_perf_event_data_kern BPF_PROG_TYPE_PERF_EVENT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_kern;
    struct bpf_raw_tracepoint_args BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_prog;
    u64 BPF_PROG_TYPE_RAW_TRACEPOINT_WRITABLE_kern;
    void * BPF_PROG_TYPE_TRACING_prog;
    void * BPF_PROG_TYPE_TRACING_kern;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_prog;
    struct bpf_cgroup_dev_ctx BPF_PROG_TYPE_CGROUP_DEVICE_kern;
    struct bpf_sysctl BPF_PROG_TYPE_CGROUP_SYSCTL_prog;
    struct bpf_sysctl_kern BPF_PROG_TYPE_CGROUP_SYSCTL_kern;
    struct bpf_sockopt BPF_PROG_TYPE_CGROUP_SOCKOPT_prog;
    struct bpf_sockopt_kern BPF_PROG_TYPE_CGROUP_SOCKOPT_kern;
    struct sk_reuseport_md BPF_PROG_TYPE_SK_REUSEPORT_prog;
    struct sk_reuseport_kern BPF_PROG_TYPE_SK_REUSEPORT_kern;
    void * BPF_PROG_TYPE_STRUCT_OPS_prog;
    void * BPF_PROG_TYPE_STRUCT_OPS_kern;
    void * BPF_PROG_TYPE_EXT_prog;
    void * BPF_PROG_TYPE_EXT_kern;
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
<code>struct bpf_sk_lookup BPF_PROG_TYPE_SK_LOOKUP_prog</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_sk_lookup_kern BPF_PROG_TYPE_SK_LOOKUP_kern</code>
</li>
<li>
<b>Field added. </b>
<code>void * BPF_PROG_TYPE_LSM_prog</code>
</li>
<li>
<b>Field added. </b>
<code>void * BPF_PROG_TYPE_LSM_kern</code>
</li>
</ul>
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
<b>Field added. </b>
<code>void * BPF_PROG_TYPE_SYSCALL_prog</code>
</li>
<li>
<b>Field added. </b>
<code>void * BPF_PROG_TYPE_SYSCALL_kern</code>
</li>
</ul>
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
<b>Field added. </b>
<code>struct bpf_nf_ctx BPF_PROG_TYPE_NETFILTER_prog</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_nf_ctx BPF_PROG_TYPE_NETFILTER_kern</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
