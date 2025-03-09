# Struct: <code>cpuset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
    struct cgroup_file partition_file;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
    struct cgroup_file partition_file;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
    enum prs_errcode prs_err;
    struct cgroup_file partition_file;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
    int nr_deadline_tasks;
    int nr_migrate_dl_tasks;
    u64 sum_migrate_dl_bw;
    enum prs_errcode prs_err;
    struct cgroup_file partition_file;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t effective_xcpus;
    cpumask_var_t exclusive_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
    int nr_deadline_tasks;
    int nr_migrate_dl_tasks;
    u64 sum_migrate_dl_bw;
    enum prs_errcode prs_err;
    struct cgroup_file partition_file;
    struct list_head remote_sibling;
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
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
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
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cpuset {
    struct cgroup_subsys_state css;
    long unsigned int flags;
    cpumask_var_t cpus_allowed;
    nodemask_t mems_allowed;
    cpumask_var_t effective_cpus;
    nodemask_t effective_mems;
    cpumask_var_t subparts_cpus;
    nodemask_t old_mems_allowed;
    struct fmeter fmeter;
    int attach_in_progress;
    int pn;
    int relax_domain_level;
    int nr_subparts_cpus;
    int partition_root_state;
    int use_parent_ecpus;
    int child_ecpus_count;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>cpumask_var_t subparts_cpus</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_subparts_cpus</code>
</li>
<li>
<b>Field added. </b>
<code>int partition_root_state</code>
</li>
<li>
<b>Field added. </b>
<code>int use_parent_ecpus</code>
</li>
<li>
<b>Field added. </b>
<code>int child_ecpus_count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<code>struct cgroup_file partition_file</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum prs_errcode prs_err</code>
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
<code>int nr_deadline_tasks</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_migrate_dl_tasks</code>
</li>
<li>
<b>Field added. </b>
<code>u64 sum_migrate_dl_bw</code>
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
<code>cpumask_var_t effective_xcpus</code>
</li>
<li>
<b>Field added. </b>
<code>cpumask_var_t exclusive_cpus</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_subparts</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head remote_sibling</code>
</li>
<li>
<b>Field removed. </b>
<code>cpumask_var_t subparts_cpus</code>
</li>
<li>
<b>Field removed. </b>
<code>int nr_subparts_cpus</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
