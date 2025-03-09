# Struct: <code>bau_control</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct bau_control {
    struct bau_desc * descriptor_base;
    struct bau_pq_entry * queue_first;
    struct bau_pq_entry * queue_last;
    struct bau_pq_entry * bau_msg_head;
    struct bau_control * uvhub_master;
    struct bau_control * socket_master;
    struct ptc_stats * statp;
    cpumask_t * cpumask;
    long unsigned int timeout_interval;
    long unsigned int set_bau_on_time;
    atomic_t active_descriptor_count;
    int plugged_tries;
    int timeout_tries;
    int ipi_attempts;
    int conseccompletes;
    u64 status_mmr;
    int status_index;
    bool nobau;
    short int baudisabled;
    short int cpu;
    short int osnode;
    short int uvhub_cpu;
    short int uvhub;
    short int uvhub_version;
    short int cpus_in_socket;
    short int cpus_in_uvhub;
    short int partition_base_pnode;
    short int busy;
    short unsigned int message_number;
    short unsigned int uvhub_quiesce;
    short int[20] socket_acknowledge_count;
    cycles_t send_message;
    cycles_t period_end;
    cycles_t period_time;
    spinlock_t uvhub_lock;
    spinlock_t queue_lock;
    spinlock_t disable_lock;
    int max_concurr;
    int max_concurr_const;
    int plugged_delay;
    int plugsb4reset;
    int timeoutsb4reset;
    int ipi_reset_limit;
    int complete_threshold;
    int cong_response_us;
    int cong_reps;
    cycles_t disabled_period;
    int period_giveups;
    int giveup_limit;
    long int period_requests;
    struct hub_and_pnode * thp;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
