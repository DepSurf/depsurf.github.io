# Struct: <code>mcinfo_logical_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct mcinfo_logical_cpu {
    uint32_t mc_cpunr;
    uint32_t mc_chipid;
    uint16_t mc_coreid;
    uint16_t mc_threadid;
    uint32_t mc_apicid;
    uint32_t mc_clusterid;
    uint32_t mc_ncores;
    uint32_t mc_ncores_active;
    uint32_t mc_nthreads;
    uint32_t mc_cpuid_level;
    uint32_t mc_family;
    uint32_t mc_vendor;
    uint32_t mc_model;
    uint32_t mc_step;
    char[16] mc_vendorid;
    char[64] mc_brandid;
    uint32_t[7] mc_cpu_caps;
    uint32_t mc_cache_size;
    uint32_t mc_cache_alignment;
    uint32_t mc_nmsrvals;
    struct mcinfo_msr[8] mc_msrvalues;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
