# Struct: <code>elevator_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct elevator_ops {
    elevator_merge_fn * elevator_merge_fn;
    elevator_merged_fn * elevator_merged_fn;
    elevator_merge_req_fn * elevator_merge_req_fn;
    elevator_allow_merge_fn * elevator_allow_merge_fn;
    elevator_bio_merged_fn * elevator_bio_merged_fn;
    elevator_dispatch_fn * elevator_dispatch_fn;
    elevator_add_req_fn * elevator_add_req_fn;
    elevator_activate_req_fn * elevator_activate_req_fn;
    elevator_deactivate_req_fn * elevator_deactivate_req_fn;
    elevator_completed_req_fn * elevator_completed_req_fn;
    elevator_request_list_fn * elevator_former_req_fn;
    elevator_request_list_fn * elevator_latter_req_fn;
    elevator_init_icq_fn * elevator_init_icq_fn;
    elevator_exit_icq_fn * elevator_exit_icq_fn;
    elevator_set_req_fn * elevator_set_req_fn;
    elevator_put_req_fn * elevator_put_req_fn;
    elevator_may_queue_fn * elevator_may_queue_fn;
    elevator_init_fn * elevator_init_fn;
    elevator_exit_fn * elevator_exit_fn;
    elevator_registered_fn * elevator_registered_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct elevator_ops {
    elevator_merge_fn * elevator_merge_fn;
    elevator_merged_fn * elevator_merged_fn;
    elevator_merge_req_fn * elevator_merge_req_fn;
    elevator_allow_bio_merge_fn * elevator_allow_bio_merge_fn;
    elevator_allow_rq_merge_fn * elevator_allow_rq_merge_fn;
    elevator_bio_merged_fn * elevator_bio_merged_fn;
    elevator_dispatch_fn * elevator_dispatch_fn;
    elevator_add_req_fn * elevator_add_req_fn;
    elevator_activate_req_fn * elevator_activate_req_fn;
    elevator_deactivate_req_fn * elevator_deactivate_req_fn;
    elevator_completed_req_fn * elevator_completed_req_fn;
    elevator_request_list_fn * elevator_former_req_fn;
    elevator_request_list_fn * elevator_latter_req_fn;
    elevator_init_icq_fn * elevator_init_icq_fn;
    elevator_exit_icq_fn * elevator_exit_icq_fn;
    elevator_set_req_fn * elevator_set_req_fn;
    elevator_put_req_fn * elevator_put_req_fn;
    elevator_may_queue_fn * elevator_may_queue_fn;
    elevator_init_fn * elevator_init_fn;
    elevator_exit_fn * elevator_exit_fn;
    elevator_registered_fn * elevator_registered_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct elevator_ops {
    elevator_merge_fn * elevator_merge_fn;
    elevator_merged_fn * elevator_merged_fn;
    elevator_merge_req_fn * elevator_merge_req_fn;
    elevator_allow_bio_merge_fn * elevator_allow_bio_merge_fn;
    elevator_allow_rq_merge_fn * elevator_allow_rq_merge_fn;
    elevator_bio_merged_fn * elevator_bio_merged_fn;
    elevator_dispatch_fn * elevator_dispatch_fn;
    elevator_add_req_fn * elevator_add_req_fn;
    elevator_activate_req_fn * elevator_activate_req_fn;
    elevator_deactivate_req_fn * elevator_deactivate_req_fn;
    elevator_completed_req_fn * elevator_completed_req_fn;
    elevator_request_list_fn * elevator_former_req_fn;
    elevator_request_list_fn * elevator_latter_req_fn;
    elevator_init_icq_fn * elevator_init_icq_fn;
    elevator_exit_icq_fn * elevator_exit_icq_fn;
    elevator_set_req_fn * elevator_set_req_fn;
    elevator_put_req_fn * elevator_put_req_fn;
    elevator_may_queue_fn * elevator_may_queue_fn;
    elevator_init_fn * elevator_init_fn;
    elevator_exit_fn * elevator_exit_fn;
    elevator_registered_fn * elevator_registered_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct elevator_ops {
    elevator_merge_fn * elevator_merge_fn;
    elevator_merged_fn * elevator_merged_fn;
    elevator_merge_req_fn * elevator_merge_req_fn;
    elevator_allow_bio_merge_fn * elevator_allow_bio_merge_fn;
    elevator_allow_rq_merge_fn * elevator_allow_rq_merge_fn;
    elevator_bio_merged_fn * elevator_bio_merged_fn;
    elevator_dispatch_fn * elevator_dispatch_fn;
    elevator_add_req_fn * elevator_add_req_fn;
    elevator_activate_req_fn * elevator_activate_req_fn;
    elevator_deactivate_req_fn * elevator_deactivate_req_fn;
    elevator_completed_req_fn * elevator_completed_req_fn;
    elevator_request_list_fn * elevator_former_req_fn;
    elevator_request_list_fn * elevator_latter_req_fn;
    elevator_init_icq_fn * elevator_init_icq_fn;
    elevator_exit_icq_fn * elevator_exit_icq_fn;
    elevator_set_req_fn * elevator_set_req_fn;
    elevator_put_req_fn * elevator_put_req_fn;
    elevator_may_queue_fn * elevator_may_queue_fn;
    elevator_init_fn * elevator_init_fn;
    elevator_exit_fn * elevator_exit_fn;
    elevator_registered_fn * elevator_registered_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct elevator_ops {
    elevator_merge_fn * elevator_merge_fn;
    elevator_merged_fn * elevator_merged_fn;
    elevator_merge_req_fn * elevator_merge_req_fn;
    elevator_allow_bio_merge_fn * elevator_allow_bio_merge_fn;
    elevator_allow_rq_merge_fn * elevator_allow_rq_merge_fn;
    elevator_bio_merged_fn * elevator_bio_merged_fn;
    elevator_dispatch_fn * elevator_dispatch_fn;
    elevator_add_req_fn * elevator_add_req_fn;
    elevator_activate_req_fn * elevator_activate_req_fn;
    elevator_deactivate_req_fn * elevator_deactivate_req_fn;
    elevator_completed_req_fn * elevator_completed_req_fn;
    elevator_request_list_fn * elevator_former_req_fn;
    elevator_request_list_fn * elevator_latter_req_fn;
    elevator_init_icq_fn * elevator_init_icq_fn;
    elevator_exit_icq_fn * elevator_exit_icq_fn;
    elevator_set_req_fn * elevator_set_req_fn;
    elevator_put_req_fn * elevator_put_req_fn;
    elevator_may_queue_fn * elevator_may_queue_fn;
    elevator_init_fn * elevator_init_fn;
    elevator_exit_fn * elevator_exit_fn;
    elevator_registered_fn * elevator_registered_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct elevator_ops {
    elevator_merge_fn * elevator_merge_fn;
    elevator_merged_fn * elevator_merged_fn;
    elevator_merge_req_fn * elevator_merge_req_fn;
    elevator_allow_bio_merge_fn * elevator_allow_bio_merge_fn;
    elevator_allow_rq_merge_fn * elevator_allow_rq_merge_fn;
    elevator_bio_merged_fn * elevator_bio_merged_fn;
    elevator_dispatch_fn * elevator_dispatch_fn;
    elevator_add_req_fn * elevator_add_req_fn;
    elevator_activate_req_fn * elevator_activate_req_fn;
    elevator_deactivate_req_fn * elevator_deactivate_req_fn;
    elevator_completed_req_fn * elevator_completed_req_fn;
    elevator_request_list_fn * elevator_former_req_fn;
    elevator_request_list_fn * elevator_latter_req_fn;
    elevator_init_icq_fn * elevator_init_icq_fn;
    elevator_exit_icq_fn * elevator_exit_icq_fn;
    elevator_set_req_fn * elevator_set_req_fn;
    elevator_put_req_fn * elevator_put_req_fn;
    elevator_may_queue_fn * elevator_may_queue_fn;
    elevator_init_fn * elevator_init_fn;
    elevator_exit_fn * elevator_exit_fn;
    elevator_registered_fn * elevator_registered_fn;
}
```
</details>
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>elevator_allow_bio_merge_fn * elevator_allow_bio_merge_fn</code>
</li>
<li>
<b>Field added. </b>
<code>elevator_allow_rq_merge_fn * elevator_allow_rq_merge_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>elevator_allow_merge_fn * elevator_allow_merge_fn</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct elevator_ops {
    elevator_merge_fn * elevator_merge_fn;
    elevator_merged_fn * elevator_merged_fn;
    elevator_merge_req_fn * elevator_merge_req_fn;
    elevator_allow_bio_merge_fn * elevator_allow_bio_merge_fn;
    elevator_allow_rq_merge_fn * elevator_allow_rq_merge_fn;
    elevator_bio_merged_fn * elevator_bio_merged_fn;
    elevator_dispatch_fn * elevator_dispatch_fn;
    elevator_add_req_fn * elevator_add_req_fn;
    elevator_activate_req_fn * elevator_activate_req_fn;
    elevator_deactivate_req_fn * elevator_deactivate_req_fn;
    elevator_completed_req_fn * elevator_completed_req_fn;
    elevator_request_list_fn * elevator_former_req_fn;
    elevator_request_list_fn * elevator_latter_req_fn;
    elevator_init_icq_fn * elevator_init_icq_fn;
    elevator_exit_icq_fn * elevator_exit_icq_fn;
    elevator_set_req_fn * elevator_set_req_fn;
    elevator_put_req_fn * elevator_put_req_fn;
    elevator_may_queue_fn * elevator_may_queue_fn;
    elevator_init_fn * elevator_init_fn;
    elevator_exit_fn * elevator_exit_fn;
    elevator_registered_fn * elevator_registered_fn;
}
```
</details>
</li>
</ul>
