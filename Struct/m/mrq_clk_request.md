# Struct: <code>mrq_clk_request</code>

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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mrq_clk_request {
    uint32_t cmd_and_id;
    struct cmd_clk_get_rate_request clk_get_rate;
    struct cmd_clk_set_rate_request clk_set_rate;
    struct cmd_clk_round_rate_request clk_round_rate;
    struct cmd_clk_get_parent_request clk_get_parent;
    struct cmd_clk_set_parent_request clk_set_parent;
    struct cmd_clk_enable_request clk_enable;
    struct cmd_clk_disable_request clk_disable;
    struct cmd_clk_is_enabled_request clk_is_enabled;
    struct cmd_clk_get_all_info_request clk_get_all_info;
    struct cmd_clk_get_max_clk_id_request clk_get_max_clk_id;
    struct cmd_clk_get_fmax_at_vmin_request clk_get_fmax_at_vmin;
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct mrq_clk_request {
    uint32_t cmd_and_id;
    struct cmd_clk_get_rate_request clk_get_rate;
    struct cmd_clk_set_rate_request clk_set_rate;
    struct cmd_clk_round_rate_request clk_round_rate;
    struct cmd_clk_get_parent_request clk_get_parent;
    struct cmd_clk_set_parent_request clk_set_parent;
    struct cmd_clk_enable_request clk_enable;
    struct cmd_clk_disable_request clk_disable;
    struct cmd_clk_is_enabled_request clk_is_enabled;
    struct cmd_clk_get_all_info_request clk_get_all_info;
    struct cmd_clk_get_max_clk_id_request clk_get_max_clk_id;
    struct cmd_clk_get_fmax_at_vmin_request clk_get_fmax_at_vmin;
}
```
</details>
</li>
</ul>
