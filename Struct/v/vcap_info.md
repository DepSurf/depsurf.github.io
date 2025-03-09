# Struct: <code>vcap_info</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vcap_info {
    char * name;
    u16 rows;
    u16 sw_count;
    u16 sw_width;
    u16 sticky_width;
    u16 act_width;
    u16 default_cnt;
    u16 require_cnt_dis;
    u16 version;
    const struct vcap_set * keyfield_set;
    int keyfield_set_size;
    const struct vcap_set * actionfield_set;
    int actionfield_set_size;
    const struct vcap_field * * keyfield_set_map;
    int * keyfield_set_map_size;
    const struct vcap_field * * actionfield_set_map;
    int * actionfield_set_map_size;
    const struct vcap_typegroup * * keyfield_set_typegroups;
    const struct vcap_typegroup * * actionfield_set_typegroups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vcap_info {
    char * name;
    u16 rows;
    u16 sw_count;
    u16 sw_width;
    u16 sticky_width;
    u16 act_width;
    u16 default_cnt;
    u16 require_cnt_dis;
    u16 version;
    const struct vcap_set * keyfield_set;
    int keyfield_set_size;
    const struct vcap_set * actionfield_set;
    int actionfield_set_size;
    const struct vcap_field * * keyfield_set_map;
    int * keyfield_set_map_size;
    const struct vcap_field * * actionfield_set_map;
    int * actionfield_set_map_size;
    const struct vcap_typegroup * * keyfield_set_typegroups;
    const struct vcap_typegroup * * actionfield_set_typegroups;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vcap_info {
    char * name;
    u16 rows;
    u16 sw_count;
    u16 sw_width;
    u16 sticky_width;
    u16 act_width;
    u16 default_cnt;
    u16 require_cnt_dis;
    u16 version;
    const struct vcap_set * keyfield_set;
    int keyfield_set_size;
    const struct vcap_set * actionfield_set;
    int actionfield_set_size;
    const struct vcap_field * * keyfield_set_map;
    int * keyfield_set_map_size;
    const struct vcap_field * * actionfield_set_map;
    int * actionfield_set_map_size;
    const struct vcap_typegroup * * keyfield_set_typegroups;
    const struct vcap_typegroup * * actionfield_set_typegroups;
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct vcap_info {
    char * name;
    u16 rows;
    u16 sw_count;
    u16 sw_width;
    u16 sticky_width;
    u16 act_width;
    u16 default_cnt;
    u16 require_cnt_dis;
    u16 version;
    const struct vcap_set * keyfield_set;
    int keyfield_set_size;
    const struct vcap_set * actionfield_set;
    int actionfield_set_size;
    const struct vcap_field * * keyfield_set_map;
    int * keyfield_set_map_size;
    const struct vcap_field * * actionfield_set_map;
    int * actionfield_set_map_size;
    const struct vcap_typegroup * * keyfield_set_typegroups;
    const struct vcap_typegroup * * actionfield_set_typegroups;
}
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
