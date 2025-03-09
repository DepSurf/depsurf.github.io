# Struct: <code>ib_port_attr</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    bool grh_required;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    bool grh_required;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    u32 phys_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    u32 phys_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u16 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    u32 phys_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u16 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    u32 phys_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u16 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    u32 phys_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u16 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    u32 phys_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u16 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    u32 phys_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u16 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    u32 phys_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u16 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
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
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
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
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    unsigned int ip_gids;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    u16 port_cap_flags2;
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct ib_port_attr {
    u64 subnet_prefix;
    enum ib_port_state state;
    enum ib_mtu max_mtu;
    enum ib_mtu active_mtu;
    int gid_tbl_len;
    u32 port_cap_flags;
    u32 max_msg_sz;
    u32 bad_pkey_cntr;
    u32 qkey_viol_cntr;
    u16 pkey_tbl_len;
    u32 sm_lid;
    u32 lid;
    u8 lmc;
    u8 max_vl_num;
    u8 sm_sl;
    u8 subnet_timeout;
    u8 init_type_reply;
    u8 active_width;
    u8 active_speed;
    u8 phys_state;
    bool grh_required;
}
```
</details>
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
<code>unsigned int ip_gids</code>
</li>
<li>
<b>Field added. </b>
<code>u16 port_cap_flags2</code>
</li>
<li>
<b>Field removed. </b>
<code>bool grh_required</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 phys_mtu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u8 active_speed</code> ➡️ <code>u16 active_speed</code>
</li>
</ul>
</details>
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
