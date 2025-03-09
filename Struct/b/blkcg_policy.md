# Struct: <code>blkcg_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
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
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
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
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct blkcg_policy {
    int plid;
    struct cftype * dfl_cftypes;
    struct cftype * legacy_cftypes;
    blkcg_pol_alloc_cpd_fn * cpd_alloc_fn;
    blkcg_pol_init_cpd_fn * cpd_init_fn;
    blkcg_pol_free_cpd_fn * cpd_free_fn;
    blkcg_pol_bind_cpd_fn * cpd_bind_fn;
    blkcg_pol_alloc_pd_fn * pd_alloc_fn;
    blkcg_pol_init_pd_fn * pd_init_fn;
    blkcg_pol_online_pd_fn * pd_online_fn;
    blkcg_pol_offline_pd_fn * pd_offline_fn;
    blkcg_pol_free_pd_fn * pd_free_fn;
    blkcg_pol_reset_pd_stats_fn * pd_reset_stats_fn;
    blkcg_pol_stat_pd_fn * pd_stat_fn;
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
<code>blkcg_pol_stat_pd_fn * pd_stat_fn</code>
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
<b>Field removed. </b>
<code>blkcg_pol_init_cpd_fn * cpd_init_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>blkcg_pol_bind_cpd_fn * cpd_bind_fn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
