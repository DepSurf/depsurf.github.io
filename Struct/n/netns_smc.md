# Struct: <code>netns_smc</code>

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
struct netns_smc {
    struct smc_stats * smc_stats;
    struct mutex mutex_fback_rsn;
    struct smc_stats_rsn * fback_rsn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_smc {
    struct smc_stats * smc_stats;
    struct mutex mutex_fback_rsn;
    struct smc_stats_rsn * fback_rsn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_smc {
    struct smc_stats * smc_stats;
    struct mutex mutex_fback_rsn;
    struct smc_stats_rsn * fback_rsn;
    bool limit_smc_hs;
    struct ctl_table_header * smc_hdr;
    unsigned int sysctl_autocorking_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_smc {
    struct smc_stats * smc_stats;
    struct mutex mutex_fback_rsn;
    struct smc_stats_rsn * fback_rsn;
    bool limit_smc_hs;
    struct ctl_table_header * smc_hdr;
    unsigned int sysctl_autocorking_size;
    unsigned int sysctl_smcr_buf_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netns_smc {
    struct smc_stats * smc_stats;
    struct mutex mutex_fback_rsn;
    struct smc_stats_rsn * fback_rsn;
    bool limit_smc_hs;
    struct ctl_table_header * smc_hdr;
    unsigned int sysctl_autocorking_size;
    unsigned int sysctl_smcr_buf_type;
    int sysctl_smcr_testlink_time;
    int sysctl_wmem;
    int sysctl_rmem;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netns_smc {
    struct smc_stats * smc_stats;
    struct mutex mutex_fback_rsn;
    struct smc_stats_rsn * fback_rsn;
    bool limit_smc_hs;
    struct ctl_table_header * smc_hdr;
    unsigned int sysctl_autocorking_size;
    unsigned int sysctl_smcr_buf_type;
    int sysctl_smcr_testlink_time;
    int sysctl_wmem;
    int sysctl_rmem;
    int sysctl_max_links_per_lgr;
    int sysctl_max_conns_per_lgr;
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
struct netns_smc {
    struct smc_stats * smc_stats;
    struct mutex mutex_fback_rsn;
    struct smc_stats_rsn * fback_rsn;
}
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool limit_smc_hs</code>
</li>
<li>
<b>Field added. </b>
<code>struct ctl_table_header * smc_hdr</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sysctl_autocorking_size</code>
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
<code>unsigned int sysctl_smcr_buf_type</code>
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
<code>int sysctl_smcr_testlink_time</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_wmem</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_rmem</code>
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
<code>int sysctl_max_links_per_lgr</code>
</li>
<li>
<b>Field added. </b>
<code>int sysctl_max_conns_per_lgr</code>
</li>
</ul>
</details>
</li>
</ul>
