# Struct: <code>nd_region_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping * nd_mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping * nd_mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    long unsigned int flags;
    struct device_node * of_node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    long unsigned int flags;
    struct device_node * of_node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    int memregion;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    int memregion;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    int memregion;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
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
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
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
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct nd_mapping_desc * mapping</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nd_mapping * nd_mapping</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device_node * of_node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int target_node</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct nd_region *, struct bio *) flush</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int memregion</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nd_region_desc {
    struct resource * res;
    struct nd_mapping_desc * mapping;
    u16 num_mappings;
    const struct attribute_group * * attr_groups;
    struct nd_interleave_set * nd_set;
    void * provider_data;
    int num_lanes;
    int numa_node;
    int target_node;
    long unsigned int flags;
    struct device_node * of_node;
    int (*)(struct nd_region *, struct bio *) flush;
}
```
</details>
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
