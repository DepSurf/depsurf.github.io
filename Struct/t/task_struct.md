# Struct: <code>task_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    volatile long int state;
    void * stack;
    atomic_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    cpumask_t cpus_allowed;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    u32 vmacache_seqnum;
    struct vm_area_struct *[4] vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int memcg_may_oom;
    unsigned int memcg_kmem_skip_account;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid_link[3] pids;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    cputime_t utime;
    cputime_t stime;
    cputime_t utimescaled;
    cputime_t stimescaled;
    cputime_t gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct task_cputime cputime_expires;
    struct list_head[3] cpu_timers;
    const struct cred * real_cred;
    const struct cred * cred;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root pi_waiters;
    struct rb_node * pi_waiters_leftmost;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    long unsigned int ptrace_message;
    siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    cputime_t acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_next;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct list_head numa_entry;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct tlbflush_unmap_batch tlb_ubc;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    long unsigned int timer_slack_ns;
    long unsigned int default_timer_slack_ns;
    int curr_ret_stack;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    volatile long int state;
    void * stack;
    atomic_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    cpumask_t cpus_allowed;
    long unsigned int rcu_tasks_nvcsw;
    bool rcu_tasks_holdout;
    struct list_head rcu_tasks_holdout_list;
    int rcu_tasks_idle_cpu;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    u32 vmacache_seqnum;
    struct vm_area_struct *[4] vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int memcg_may_oom;
    unsigned int memcg_kmem_skip_account;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid_link[3] pids;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    cputime_t utime;
    cputime_t stime;
    cputime_t utimescaled;
    cputime_t stimescaled;
    cputime_t gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct task_cputime cputime_expires;
    struct list_head[3] cpu_timers;
    const struct cred * real_cred;
    const struct cred * cred;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root pi_waiters;
    struct rb_node * pi_waiters_leftmost;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    long unsigned int ptrace_message;
    siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    cputime_t acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_next;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct list_head numa_entry;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct tlbflush_unmap_batch tlb_ubc;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    atomic_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    cpumask_t cpus_allowed;
    long unsigned int rcu_tasks_nvcsw;
    bool rcu_tasks_holdout;
    struct list_head rcu_tasks_holdout_list;
    int rcu_tasks_idle_cpu;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    u32 vmacache_seqnum;
    struct vm_area_struct *[4] vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int memcg_may_oom;
    unsigned int memcg_kmem_skip_account;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid_link[3] pids;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    cputime_t utime;
    cputime_t stime;
    cputime_t gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct task_cputime cputime_expires;
    struct list_head[3] cpu_timers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root pi_waiters;
    struct rb_node * pi_waiters_leftmost;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    long unsigned int ptrace_message;
    siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    cputime_t acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    int closid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_next;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct list_head numa_entry;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct tlbflush_unmap_batch tlb_ubc;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    atomic_t stack_refcount;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    atomic_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    cpumask_t cpus_allowed;
    long unsigned int rcu_tasks_nvcsw;
    bool rcu_tasks_holdout;
    struct list_head rcu_tasks_holdout_list;
    int rcu_tasks_idle_cpu;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int memcg_may_oom;
    unsigned int memcg_kmem_skip_account;
    unsigned int no_cgroup_migration;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid_link[3] pids;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct task_cputime cputime_expires;
    struct list_head[3] cpu_timers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root pi_waiters;
    struct rb_node * pi_waiters_leftmost;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    long unsigned int ptrace_message;
    siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct list_head numa_entry;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct tlbflush_unmap_batch tlb_ubc;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    atomic_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    atomic_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    cpumask_t cpus_allowed;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int memcg_may_oom;
    unsigned int memcg_kmem_skip_account;
    unsigned int no_cgroup_migration;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid_link[3] pids;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct task_cputime cputime_expires;
    struct list_head[3] cpu_timers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    long unsigned int ptrace_message;
    siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct list_head numa_entry;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct tlbflush_unmap_batch tlb_ubc;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    atomic_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    atomic_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    cpumask_t cpus_allowed;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int memcg_may_oom;
    unsigned int memcg_kmem_skip_account;
    unsigned int no_cgroup_migration;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid_link[3] pids;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct task_cputime cputime_expires;
    struct list_head[3] cpu_timers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    long unsigned int ptrace_message;
    siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct list_head numa_entry;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_len;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    atomic_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    atomic_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    cpumask_t cpus_allowed;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct task_cputime cputime_expires;
    struct list_head[3] cpu_timers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_len;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    atomic_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct task_cputime cputime_expires;
    struct list_head[3] cpu_timers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    int on_cpu;
    struct __call_single_node wake_entry;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    int trc_reader_nesting;
    int trc_ipi_to_cpu;
    union rcu_special trc_reader_special;
    bool trc_reader_checked;
    struct list_head trc_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    unsigned int in_memstall;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 start_boottime;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u64 parent_exec_id;
    u64 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    u64 mce_addr;
    __u64 mce_ripv;
    __u64 mce_whole_page;
    __u64 __mce_reserved;
    struct callback_head mce_kill_me;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    int on_cpu;
    struct __call_single_node wake_entry;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    void * migration_pending;
    short unsigned int migration_disabled;
    short unsigned int migration_flags;
    int trc_reader_nesting;
    int trc_ipi_to_cpu;
    union rcu_special trc_reader_special;
    bool trc_reader_checked;
    struct list_head trc_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_psi_wake_requeue;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    unsigned int in_memstall;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 start_boottime;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    struct posix_cputimers_work posix_cputimers_work;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct io_uring_task * io_uring;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    struct syscall_user_dispatch syscall_dispatch;
    u64 parent_exec_id;
    u64 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_spinlock_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    struct kmap_ctrl kmap_ctrl;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    void * mce_vaddr;
    __u64 mce_kflags;
    u64 mce_addr;
    __u64 mce_ripv;
    __u64 mce_whole_page;
    __u64 __mce_reserved;
    struct callback_head mce_kill_me;
    struct llist_head kretprobe_instances;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    int on_cpu;
    struct __call_single_node wake_entry;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    void * migration_pending;
    short unsigned int migration_disabled;
    short unsigned int migration_flags;
    int trc_reader_nesting;
    int trc_ipi_to_cpu;
    union rcu_special trc_reader_special;
    bool trc_reader_checked;
    struct list_head trc_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_psi_wake_requeue;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    unsigned int in_memstall;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    void * pf_io_worker;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 start_boottime;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    struct posix_cputimers_work posix_cputimers_work;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct io_uring_task * io_uring;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    struct syscall_user_dispatch syscall_dispatch;
    u64 parent_exec_id;
    u64 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_spinlock_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    struct kmap_ctrl kmap_ctrl;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct bpf_local_storage * bpf_storage;
    void * mce_vaddr;
    __u64 mce_kflags;
    u64 mce_addr;
    __u64 mce_ripv;
    __u64 mce_whole_page;
    __u64 __mce_reserved;
    struct callback_head mce_kill_me;
    struct llist_head kretprobe_instances;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    unsigned int __state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    int on_cpu;
    struct __call_single_node wake_entry;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct sched_dl_entity dl;
    struct rb_node core_node;
    long unsigned int core_cookie;
    unsigned int core_occupation;
    struct task_group * sched_task_group;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t * user_cpus_ptr;
    cpumask_t cpus_mask;
    void * migration_pending;
    short unsigned int migration_disabled;
    short unsigned int migration_flags;
    int trc_reader_nesting;
    int trc_ipi_to_cpu;
    union rcu_special trc_reader_special;
    bool trc_reader_checked;
    struct list_head trc_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_psi_wake_requeue;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    unsigned int in_memstall;
    unsigned int in_eventfd_signal;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    void * pf_io_worker;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 start_boottime;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    struct posix_cputimers_work posix_cputimers_work;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct io_uring_task * io_uring;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    struct syscall_user_dispatch syscall_dispatch;
    u64 parent_exec_id;
    u64 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    unsigned int in_ubsan;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_spinlock_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    struct kmap_ctrl kmap_ctrl;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct bpf_local_storage * bpf_storage;
    struct bpf_run_ctx * bpf_ctx;
    void * mce_vaddr;
    __u64 mce_kflags;
    u64 mce_addr;
    __u64 mce_ripv;
    __u64 mce_whole_page;
    __u64 __mce_reserved;
    struct callback_head mce_kill_me;
    int mce_count;
    struct llist_head kretprobe_instances;
    struct callback_head l1d_flush_kill;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    unsigned int __state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    int on_cpu;
    struct __call_single_node wake_entry;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct sched_dl_entity dl;
    const struct sched_class * sched_class;
    struct rb_node core_node;
    long unsigned int core_cookie;
    unsigned int core_occupation;
    struct task_group * sched_task_group;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct sched_statistics stats;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t * user_cpus_ptr;
    cpumask_t cpus_mask;
    void * migration_pending;
    short unsigned int migration_disabled;
    short unsigned int migration_flags;
    int rcu_read_lock_nesting;
    union rcu_special rcu_read_unlock_special;
    struct list_head rcu_node_entry;
    struct rcu_node * rcu_blocked_node;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    int trc_reader_nesting;
    int trc_ipi_to_cpu;
    union rcu_special trc_reader_special;
    bool trc_reader_checked;
    struct list_head trc_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_psi_wake_requeue;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    unsigned int in_memstall;
    unsigned int in_eventfd_signal;
    unsigned int pasid_activated;
    unsigned int reported_split_lock;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    void * worker_private;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 start_boottime;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    struct posix_cputimers_work posix_cputimers_work;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct io_uring_task * io_uring;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    struct syscall_user_dispatch syscall_dispatch;
    u64 parent_exec_id;
    u64 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    unsigned int in_ubsan;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_spinlock_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    struct kmap_ctrl kmap_ctrl;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct timer_list oom_reaper_timer;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct bpf_local_storage * bpf_storage;
    struct bpf_run_ctx * bpf_ctx;
    void * mce_vaddr;
    __u64 mce_kflags;
    u64 mce_addr;
    __u64 mce_ripv;
    __u64 mce_whole_page;
    __u64 __mce_reserved;
    struct callback_head mce_kill_me;
    int mce_count;
    struct llist_head kretprobe_instances;
    struct llist_head rethooks;
    struct callback_head l1d_flush_kill;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    unsigned int __state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    int on_cpu;
    struct __call_single_node wake_entry;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct sched_dl_entity dl;
    const struct sched_class * sched_class;
    struct rb_node core_node;
    long unsigned int core_cookie;
    unsigned int core_occupation;
    struct task_group * sched_task_group;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct sched_statistics stats;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t * user_cpus_ptr;
    cpumask_t cpus_mask;
    void * migration_pending;
    short unsigned int migration_disabled;
    short unsigned int migration_flags;
    int rcu_read_lock_nesting;
    union rcu_special rcu_read_unlock_special;
    struct list_head rcu_node_entry;
    struct rcu_node * rcu_blocked_node;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    int trc_reader_nesting;
    int trc_ipi_to_cpu;
    union rcu_special trc_reader_special;
    struct list_head trc_holdout_list;
    struct list_head trc_blkd_node;
    int trc_blkd_cpu;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int in_lru_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    unsigned int in_memstall;
    unsigned int in_eventfd;
    unsigned int pasid_activated;
    unsigned int reported_split_lock;
    unsigned int in_thrashing;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    void * worker_private;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 start_boottime;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    struct posix_cputimers_work posix_cputimers_work;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct io_uring_task * io_uring;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    struct syscall_user_dispatch syscall_dispatch;
    u64 parent_exec_id;
    u64 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    unsigned int in_ubsan;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_spinlock_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context * perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    struct kmap_ctrl kmap_ctrl;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct timer_list oom_reaper_timer;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct bpf_local_storage * bpf_storage;
    struct bpf_run_ctx * bpf_ctx;
    void * mce_vaddr;
    __u64 mce_kflags;
    u64 mce_addr;
    __u64 mce_ripv;
    __u64 mce_whole_page;
    __u64 __mce_reserved;
    struct callback_head mce_kill_me;
    int mce_count;
    struct llist_head kretprobe_instances;
    struct llist_head rethooks;
    struct callback_head l1d_flush_kill;
    union rv_task_monitor[1] rv;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    unsigned int __state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    int on_cpu;
    struct __call_single_node wake_entry;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct sched_dl_entity dl;
    const struct sched_class * sched_class;
    struct rb_node core_node;
    long unsigned int core_cookie;
    unsigned int core_occupation;
    struct task_group * sched_task_group;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct sched_statistics stats;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t * user_cpus_ptr;
    cpumask_t cpus_mask;
    void * migration_pending;
    short unsigned int migration_disabled;
    short unsigned int migration_flags;
    int rcu_read_lock_nesting;
    union rcu_special rcu_read_unlock_special;
    struct list_head rcu_node_entry;
    struct rcu_node * rcu_blocked_node;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    int trc_reader_nesting;
    int trc_ipi_to_cpu;
    union rcu_special trc_reader_special;
    struct list_head trc_holdout_list;
    struct list_head trc_blkd_node;
    int trc_blkd_cpu;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int in_lru_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    unsigned int in_memstall;
    unsigned int in_eventfd;
    unsigned int pasid_activated;
    unsigned int reported_split_lock;
    unsigned int in_thrashing;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    void * worker_private;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 start_boottime;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    struct posix_cputimers_work posix_cputimers_work;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct io_uring_task * io_uring;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    struct syscall_user_dispatch syscall_dispatch;
    u64 parent_exec_id;
    u64 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    unsigned int in_ubsan;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_spinlock_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context * perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_len;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    int mm_cid;
    int last_mm_cid;
    int migrate_from_cpu;
    int mm_cid_active;
    struct callback_head cid_work;
    struct tlbflush_unmap_batch tlb_ubc;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct gendisk * throttle_disk;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    struct kmap_ctrl kmap_ctrl;
    struct callback_head rcu;
    refcount_t rcu_users;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct timer_list oom_reaper_timer;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct bpf_local_storage * bpf_storage;
    struct bpf_run_ctx * bpf_ctx;
    void * mce_vaddr;
    __u64 mce_kflags;
    u64 mce_addr;
    __u64 mce_ripv;
    __u64 mce_whole_page;
    __u64 __mce_reserved;
    struct callback_head mce_kill_me;
    int mce_count;
    struct llist_head kretprobe_instances;
    struct llist_head rethooks;
    struct callback_head l1d_flush_kill;
    union rv_task_monitor[1] rv;
    struct user_event_mm * user_event_mm;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    unsigned int __state;
    unsigned int saved_state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    int on_cpu;
    struct __call_single_node wake_entry;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct sched_dl_entity dl;
    struct sched_dl_entity * dl_server;
    const struct sched_class * sched_class;
    struct rb_node core_node;
    long unsigned int core_cookie;
    unsigned int core_occupation;
    struct task_group * sched_task_group;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct sched_statistics stats;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t * user_cpus_ptr;
    cpumask_t cpus_mask;
    void * migration_pending;
    short unsigned int migration_disabled;
    short unsigned int migration_flags;
    int rcu_read_lock_nesting;
    union rcu_special rcu_read_unlock_special;
    struct list_head rcu_node_entry;
    struct rcu_node * rcu_blocked_node;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    int trc_reader_nesting;
    int trc_ipi_to_cpu;
    union rcu_special trc_reader_special;
    struct list_head trc_holdout_list;
    struct list_head trc_blkd_node;
    int trc_blkd_cpu;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct address_space * faults_disabled_mapping;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_rt_mutex;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int in_lru_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    unsigned int in_memstall;
    unsigned int in_eventfd;
    unsigned int pasid_activated;
    unsigned int reported_split_lock;
    unsigned int in_thrashing;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    void * worker_private;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    struct vtime vtime;
    atomic_t tick_dep_mask;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 start_boottime;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    struct posix_cputimers_work posix_cputimers_work;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct io_uring_task * io_uring;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    struct syscall_user_dispatch syscall_dispatch;
    u64 parent_exec_id;
    u64 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    unsigned int in_ubsan;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_spinlock_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context * perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_len;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    int mm_cid;
    int last_mm_cid;
    int migrate_from_cpu;
    int mm_cid_active;
    struct callback_head cid_work;
    struct tlbflush_unmap_batch tlb_ubc;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    int latency_record_count;
    struct latency_record[32] latency_record;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct obj_cgroup * objcg;
    struct gendisk * throttle_disk;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    struct kmap_ctrl kmap_ctrl;
    struct callback_head rcu;
    refcount_t rcu_users;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct timer_list oom_reaper_timer;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct bpf_local_storage * bpf_storage;
    struct bpf_run_ctx * bpf_ctx;
    void * mce_vaddr;
    __u64 mce_kflags;
    u64 mce_addr;
    __u64 mce_ripv;
    __u64 mce_whole_page;
    __u64 __mce_reserved;
    struct callback_head mce_kill_me;
    int mce_count;
    struct llist_head kretprobe_instances;
    struct llist_head rethooks;
    struct callback_head l1d_flush_kill;
    union rv_task_monitor[1] rv;
    struct user_event_mm * user_event_mm;
    struct thread_struct thread;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct task_struct {
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    struct robust_list_head * robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    struct robust_list_head * robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    refcount_t stack_refcount;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    struct vtime vtime;
    atomic_t tick_dep_mask;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct task_struct {
    struct thread_info thread_info;
    volatile long int state;
    void * stack;
    refcount_t usage;
    unsigned int flags;
    unsigned int ptrace;
    struct llist_node wake_entry;
    int on_cpu;
    unsigned int cpu;
    unsigned int wakee_flips;
    long unsigned int wakee_flip_decay_ts;
    struct task_struct * last_wakee;
    int recent_used_cpu;
    int wake_cpu;
    int on_rq;
    int prio;
    int static_prio;
    int normal_prio;
    unsigned int rt_priority;
    const struct sched_class * sched_class;
    struct sched_entity se;
    struct sched_rt_entity rt;
    struct task_group * sched_task_group;
    struct sched_dl_entity dl;
    struct uclamp_se[2] uclamp_req;
    struct uclamp_se[2] uclamp;
    struct hlist_head preempt_notifiers;
    unsigned int btrace_seq;
    unsigned int policy;
    int nr_cpus_allowed;
    const cpumask_t * cpus_ptr;
    cpumask_t cpus_mask;
    int rcu_read_lock_nesting;
    union rcu_special rcu_read_unlock_special;
    struct list_head rcu_node_entry;
    struct rcu_node * rcu_blocked_node;
    long unsigned int rcu_tasks_nvcsw;
    u8 rcu_tasks_holdout;
    u8 rcu_tasks_idx;
    int rcu_tasks_idle_cpu;
    struct list_head rcu_tasks_holdout_list;
    struct sched_info sched_info;
    struct list_head tasks;
    struct plist_node pushable_tasks;
    struct rb_node pushable_dl_tasks;
    struct mm_struct * mm;
    struct mm_struct * active_mm;
    struct vmacache vmacache;
    struct task_rss_stat rss_stat;
    int exit_state;
    int exit_code;
    int exit_signal;
    int pdeath_signal;
    long unsigned int jobctl;
    unsigned int personality;
    unsigned int sched_reset_on_fork;
    unsigned int sched_contributes_to_load;
    unsigned int sched_migrated;
    unsigned int sched_remote_wakeup;
    unsigned int sched_psi_wake_requeue;
    unsigned int in_execve;
    unsigned int in_iowait;
    unsigned int restore_sigmask;
    unsigned int in_user_fault;
    unsigned int no_cgroup_migration;
    unsigned int frozen;
    unsigned int use_memdelay;
    long unsigned int atomic_flags;
    struct restart_block restart_block;
    pid_t pid;
    pid_t tgid;
    long unsigned int stack_canary;
    struct task_struct * real_parent;
    struct task_struct * parent;
    struct list_head children;
    struct list_head sibling;
    struct task_struct * group_leader;
    struct list_head ptraced;
    struct list_head ptrace_entry;
    struct pid * thread_pid;
    struct hlist_node[4] pid_links;
    struct list_head thread_group;
    struct list_head thread_node;
    struct completion * vfork_done;
    int * set_child_tid;
    int * clear_child_tid;
    u64 utime;
    u64 stime;
    u64 gtime;
    struct prev_cputime prev_cputime;
    long unsigned int nvcsw;
    long unsigned int nivcsw;
    u64 start_time;
    u64 real_start_time;
    long unsigned int min_flt;
    long unsigned int maj_flt;
    struct posix_cputimers posix_cputimers;
    const struct cred * ptracer_cred;
    const struct cred * real_cred;
    const struct cred * cred;
    struct key * cached_requested_key;
    char[16] comm;
    struct nameidata * nameidata;
    struct sysv_sem sysvsem;
    struct sysv_shm sysvshm;
    long unsigned int last_switch_count;
    long unsigned int last_switch_time;
    struct fs_struct * fs;
    struct files_struct * files;
    struct nsproxy * nsproxy;
    struct signal_struct * signal;
    struct sighand_struct * sighand;
    sigset_t blocked;
    sigset_t real_blocked;
    sigset_t saved_sigmask;
    struct sigpending pending;
    long unsigned int sas_ss_sp;
    size_t sas_ss_size;
    unsigned int sas_ss_flags;
    struct callback_head * task_works;
    struct audit_context * audit_context;
    kuid_t loginuid;
    unsigned int sessionid;
    struct seccomp seccomp;
    u32 parent_exec_id;
    u32 self_exec_id;
    spinlock_t alloc_lock;
    raw_spinlock_t pi_lock;
    struct wake_q_node wake_q;
    struct rb_root_cached pi_waiters;
    struct task_struct * pi_top_task;
    struct rt_mutex_waiter * pi_blocked_on;
    void * journal_info;
    struct bio_list * bio_list;
    struct blk_plug * plug;
    struct reclaim_state * reclaim_state;
    struct backing_dev_info * backing_dev_info;
    struct io_context * io_context;
    struct capture_control * capture_control;
    long unsigned int ptrace_message;
    kernel_siginfo_t * last_siginfo;
    struct task_io_accounting ioac;
    unsigned int psi_flags;
    u64 acct_rss_mem1;
    u64 acct_vm_mem1;
    u64 acct_timexpd;
    nodemask_t mems_allowed;
    seqcount_t mems_allowed_seq;
    int cpuset_mem_spread_rotor;
    int cpuset_slab_spread_rotor;
    struct css_set * cgroups;
    struct list_head cg_list;
    u32 closid;
    u32 rmid;
    struct robust_list_head * robust_list;
    struct compat_robust_list_head * compat_robust_list;
    struct list_head pi_state_list;
    struct futex_pi_state * pi_state_cache;
    struct mutex futex_exit_mutex;
    unsigned int futex_state;
    struct perf_event_context *[2] perf_event_ctxp;
    struct mutex perf_event_mutex;
    struct list_head perf_event_list;
    struct mempolicy * mempolicy;
    short int il_prev;
    short int pref_node_fork;
    int numa_scan_seq;
    unsigned int numa_scan_period;
    unsigned int numa_scan_period_max;
    int numa_preferred_nid;
    long unsigned int numa_migrate_retry;
    u64 node_stamp;
    u64 last_task_numa_placement;
    u64 last_sum_exec_runtime;
    struct callback_head numa_work;
    struct numa_group * numa_group;
    long unsigned int * numa_faults;
    long unsigned int total_numa_faults;
    long unsigned int[3] numa_faults_locality;
    long unsigned int numa_pages_migrated;
    struct rseq * rseq;
    u32 rseq_sig;
    long unsigned int rseq_event_mask;
    struct tlbflush_unmap_batch tlb_ubc;
    refcount_t rcu_users;
    struct callback_head rcu;
    struct pipe_inode_info * splice_pipe;
    struct page_frag task_frag;
    struct task_delay_info * delays;
    int nr_dirtied;
    int nr_dirtied_pause;
    long unsigned int dirty_paused_when;
    int latency_record_count;
    struct latency_record[32] latency_record;
    u64 timer_slack_ns;
    u64 default_timer_slack_ns;
    int curr_ret_stack;
    int curr_ret_depth;
    struct ftrace_ret_stack * ret_stack;
    long long unsigned int ftrace_timestamp;
    atomic_t trace_overrun;
    atomic_t tracing_graph_pause;
    long unsigned int trace;
    long unsigned int trace_recursion;
    struct mem_cgroup * memcg_in_oom;
    gfp_t memcg_oom_gfp_mask;
    int memcg_oom_order;
    unsigned int memcg_nr_pages_over_high;
    struct mem_cgroup * active_memcg;
    struct request_queue * throttle_queue;
    struct uprobe_task * utask;
    unsigned int sequential_io;
    unsigned int sequential_io_avg;
    int pagefault_disabled;
    struct task_struct * oom_reaper_list;
    struct vm_struct * stack_vm_area;
    refcount_t stack_refcount;
    int patch_state;
    void * security;
    struct thread_struct thread;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int rcu_tasks_nvcsw</code>
</li>
<li>
<b>Field added. </b>
<code>bool rcu_tasks_holdout</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rcu_tasks_holdout_list</code>
</li>
<li>
<b>Field added. </b>
<code>int rcu_tasks_idle_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sched_remote_wakeup</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int restore_sigmask</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sas_ss_flags</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * oom_reaper_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int timer_slack_ns</code> ➡️ <code>u64 timer_slack_ns</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int default_timer_slack_ns</code> ➡️ <code>u64 default_timer_slack_ns</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct thread_info thread_info</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Field added. </b>
<code>const struct cred * ptracer_cred</code>
</li>
<li>
<b>Field added. </b>
<code>int closid</code>
</li>
<li>
<b>Field added. </b>
<code>struct vm_struct * stack_vm_area</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t stack_refcount</code>
</li>
<li>
<b>Field removed. </b>
<code>cputime_t utimescaled</code>
</li>
<li>
<b>Field removed. </b>
<code>cputime_t stimescaled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int no_cgroup_migration</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * pi_top_task</code>
</li>
<li>
<b>Field added. </b>
<code>u32 rmid</code>
</li>
<li>
<b>Field added. </b>
<code>short int il_prev</code>
</li>
<li>
<b>Field added. </b>
<code>int patch_state</code>
</li>
<li>
<b>Field added. </b>
<code>void * security</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 vmacache_seqnum</code>
</li>
<li>
<b>Field removed. </b>
<code>short int il_next</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct vm_area_struct *[4] vmacache</code> ➡️ <code>struct vmacache vmacache</code>
</li>
<li>
<b>Field type changed. </b>
<code>cputime_t utime</code> ➡️ <code>u64 utime</code>
</li>
<li>
<b>Field type changed. </b>
<code>cputime_t stime</code> ➡️ <code>u64 stime</code>
</li>
<li>
<b>Field type changed. </b>
<code>cputime_t gtime</code> ➡️ <code>u64 gtime</code>
</li>
<li>
<b>Field type changed. </b>
<code>cputime_t acct_timexpd</code> ➡️ <code>u64 acct_timexpd</code>
</li>
<li>
<b>Field type changed. </b>
<code>int closid</code> ➡️ <code>u32 closid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 rcu_tasks_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rb_node * pi_waiters_leftmost</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool rcu_tasks_holdout</code> ➡️ <code>u8 rcu_tasks_holdout</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rb_root pi_waiters</code> ➡️ <code>struct rb_root_cached pi_waiters</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int recent_used_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct rseq * rseq</code>
</li>
<li>
<b>Field added. </b>
<code>u32 rseq_len</code>
</li>
<li>
<b>Field added. </b>
<code>u32 rseq_sig</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int rseq_event_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int sched_psi_wake_requeue</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int in_user_fault</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int use_memdelay</code>
</li>
<li>
<b>Field added. </b>
<code>struct pid * thread_pid</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node[4] pid_links</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_switch_time</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int psi_flags</code>
</li>
<li>
<b>Field added. </b>
<code>int curr_ret_depth</code>
</li>
<li>
<b>Field added. </b>
<code>struct mem_cgroup * active_memcg</code>
</li>
<li>
<b>Field added. </b>
<code>struct request_queue * throttle_queue</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int memcg_may_oom</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int memcg_kmem_skip_account</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pid_link[3] pids</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head numa_entry</code>
</li>
<li>
<b>Field type changed. </b>
<code>siginfo_t * last_siginfo</code> ➡️ <code>kernel_siginfo_t * last_siginfo</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct uclamp_se[2] uclamp_req</code>
</li>
<li>
<b>Field added. </b>
<code>struct uclamp_se[2] uclamp</code>
</li>
<li>
<b>Field added. </b>
<code>const cpumask_t * cpus_ptr</code>
</li>
<li>
<b>Field added. </b>
<code>cpumask_t cpus_mask</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int frozen</code>
</li>
<li>
<b>Field added. </b>
<code>struct key * cached_requested_key</code>
</li>
<li>
<b>Field added. </b>
<code>struct capture_control * capture_control</code>
</li>
<li>
<b>Field removed. </b>
<code>cpumask_t cpus_allowed</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rseq_len</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t usage</code> ➡️ <code>refcount_t usage</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t stack_refcount</code> ➡️ <code>refcount_t stack_refcount</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct posix_cputimers posix_cputimers</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex futex_exit_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int futex_state</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t rcu_users</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_cputime cputime_expires</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head[3] cpu_timers</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int trc_reader_nesting</code>
</li>
<li>
<b>Field added. </b>
<code>int trc_ipi_to_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>union rcu_special trc_reader_special</code>
</li>
<li>
<b>Field added. </b>
<code>bool trc_reader_checked</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head trc_holdout_list</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int in_memstall</code>
</li>
<li>
<b>Field added. </b>
<code>u64 start_boottime</code>
</li>
<li>
<b>Field added. </b>
<code>u64 mce_addr</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 mce_ripv</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 mce_whole_page</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 __mce_reserved</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head mce_kill_me</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 real_start_time</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct llist_node wake_entry</code> ➡️ <code>struct __call_single_node wake_entry</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 parent_exec_id</code> ➡️ <code>u64 parent_exec_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 self_exec_id</code> ➡️ <code>u64 self_exec_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * migration_pending</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int migration_disabled</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int migration_flags</code>
</li>
<li>
<b>Field added. </b>
<code>struct posix_cputimers_work posix_cputimers_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_uring_task * io_uring</code>
</li>
<li>
<b>Field added. </b>
<code>struct syscall_user_dispatch syscall_dispatch</code>
</li>
<li>
<b>Field added. </b>
<code>struct kmap_ctrl kmap_ctrl</code>
</li>
<li>
<b>Field added. </b>
<code>void * mce_vaddr</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 mce_kflags</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head kretprobe_instances</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int rcu_tasks_nvcsw</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 rcu_tasks_holdout</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 rcu_tasks_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>int rcu_tasks_idle_cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head rcu_tasks_holdout_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>seqcount_t mems_allowed_seq</code> ➡️ <code>seqcount_spinlock_t mems_allowed_seq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * pf_io_worker</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_local_storage * bpf_storage</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int __state</code>
</li>
<li>
<b>Field added. </b>
<code>struct rb_node core_node</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int core_cookie</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int core_occupation</code>
</li>
<li>
<b>Field added. </b>
<code>cpumask_t * user_cpus_ptr</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int in_eventfd_signal</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int in_ubsan</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_run_ctx * bpf_ctx</code>
</li>
<li>
<b>Field added. </b>
<code>int mce_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head l1d_flush_kill</code>
</li>
<li>
<b>Field removed. </b>
<code>volatile long int state</code>
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
<code>struct sched_statistics stats</code>
</li>
<li>
<b>Field added. </b>
<code>int rcu_read_lock_nesting</code>
</li>
<li>
<b>Field added. </b>
<code>union rcu_special rcu_read_unlock_special</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rcu_node_entry</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_node * rcu_blocked_node</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int rcu_tasks_nvcsw</code>
</li>
<li>
<b>Field added. </b>
<code>u8 rcu_tasks_holdout</code>
</li>
<li>
<b>Field added. </b>
<code>u8 rcu_tasks_idx</code>
</li>
<li>
<b>Field added. </b>
<code>int rcu_tasks_idle_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rcu_tasks_holdout_list</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pasid_activated</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int reported_split_lock</code>
</li>
<li>
<b>Field added. </b>
<code>void * worker_private</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list oom_reaper_timer</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head rethooks</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>void * pf_io_worker</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head trc_blkd_node</code>
</li>
<li>
<b>Field added. </b>
<code>int trc_blkd_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int in_lru_fault</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int in_eventfd</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int in_thrashing</code>
</li>
<li>
<b>Field added. </b>
<code>union rv_task_monitor[1] rv</code>
</li>
<li>
<b>Field removed. </b>
<code>bool trc_reader_checked</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vmacache vmacache</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_rss_stat rss_stat</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int sched_psi_wake_requeue</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int in_eventfd_signal</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int trace</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct perf_event_context *[2] perf_event_ctxp</code> ➡️ <code>struct perf_event_context * perf_event_ctxp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 rseq_len</code>
</li>
<li>
<b>Field added. </b>
<code>int mm_cid</code>
</li>
<li>
<b>Field added. </b>
<code>int last_mm_cid</code>
</li>
<li>
<b>Field added. </b>
<code>int migrate_from_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>int mm_cid_active</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head cid_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct gendisk * throttle_disk</code>
</li>
<li>
<b>Field added. </b>
<code>struct user_event_mm * user_event_mm</code>
</li>
<li>
<b>Field removed. </b>
<code>struct backing_dev_info * backing_dev_info</code>
</li>
<li>
<b>Field removed. </b>
<code>struct request_queue * throttle_queue</code>
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
<code>unsigned int saved_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct sched_dl_entity * dl_server</code>
</li>
<li>
<b>Field added. </b>
<code>struct address_space * faults_disabled_mapping</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sched_rt_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>struct vtime vtime</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t tick_dep_mask</code>
</li>
<li>
<b>Field added. </b>
<code>int latency_record_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct latency_record[32] latency_record</code>
</li>
<li>
<b>Field added. </b>
<code>struct obj_cgroup * objcg</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head thread_group</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int restore_sigmask</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 closid</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rmid</code>
</li>
<li>
<b>Field removed. </b>
<code>int patch_state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct thread_info thread_info</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head preempt_notifiers</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int restore_sigmask</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 closid</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rmid</code>
</li>
<li>
<b>Field removed. </b>
<code>struct compat_robust_list_head * compat_robust_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mempolicy * mempolicy</code>
</li>
<li>
<b>Field removed. </b>
<code>short int il_prev</code>
</li>
<li>
<b>Field removed. </b>
<code>short int pref_node_fork</code>
</li>
<li>
<b>Field removed. </b>
<code>int numa_scan_seq</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int numa_scan_period</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int numa_scan_period_max</code>
</li>
<li>
<b>Field removed. </b>
<code>int numa_preferred_nid</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int numa_migrate_retry</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 node_stamp</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 last_task_numa_placement</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 last_sum_exec_runtime</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head numa_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct numa_group * numa_group</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * numa_faults</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int total_numa_faults</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[3] numa_faults_locality</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int numa_pages_migrated</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vm_struct * stack_vm_area</code>
</li>
<li>
<b>Field removed. </b>
<code>refcount_t stack_refcount</code>
</li>
<li>
<b>Field removed. </b>
<code>int patch_state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u32 closid</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rmid</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vm_struct * stack_vm_area</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct uclamp_se[2] uclamp_req</code>
</li>
<li>
<b>Field removed. </b>
<code>struct uclamp_se[2] uclamp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head preempt_notifiers</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int restore_sigmask</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int stack_canary</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 closid</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rmid</code>
</li>
<li>
<b>Field removed. </b>
<code>struct compat_robust_list_head * compat_robust_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mempolicy * mempolicy</code>
</li>
<li>
<b>Field removed. </b>
<code>short int il_prev</code>
</li>
<li>
<b>Field removed. </b>
<code>short int pref_node_fork</code>
</li>
<li>
<b>Field removed. </b>
<code>int numa_scan_seq</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int numa_scan_period</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int numa_scan_period_max</code>
</li>
<li>
<b>Field removed. </b>
<code>int numa_preferred_nid</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int numa_migrate_retry</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 node_stamp</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 last_task_numa_placement</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 last_sum_exec_runtime</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head numa_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct numa_group * numa_group</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * numa_faults</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int total_numa_faults</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[3] numa_faults_locality</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int numa_pages_migrated</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rseq * rseq</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rseq_sig</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int rseq_event_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct uprobe_task * utask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vm_struct * stack_vm_area</code>
</li>
<li>
<b>Field removed. </b>
<code>int patch_state</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct vtime vtime</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t tick_dep_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct uclamp_se[2] uclamp_req</code>
</li>
<li>
<b>Field removed. </b>
<code>struct uclamp_se[2] uclamp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int rcu_read_lock_nesting</code>
</li>
<li>
<b>Field added. </b>
<code>union rcu_special rcu_read_unlock_special</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rcu_node_entry</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_node * rcu_blocked_node</code>
</li>
<li>
<b>Field added. </b>
<code>int latency_record_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct latency_record[32] latency_record</code>
</li>
</ul>
</details>
</li>
</ul>
