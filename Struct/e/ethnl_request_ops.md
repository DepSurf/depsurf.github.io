# Struct: <code>ethnl_request_ops</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ethnl_request_ops {
    u8 request_cmd;
    u8 reply_cmd;
    u16 hdr_attr;
    unsigned int max_attr;
    unsigned int req_info_size;
    unsigned int reply_data_size;
    const struct nla_policy * request_policy;
    bool allow_nodev_do;
    int (*)(struct ethnl_req_info *, struct nlattr * *, struct netlink_ext_ack *) parse_request;
    int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, struct genl_info *) prepare_data;
    int (*)(const struct ethnl_req_info *, const struct ethnl_reply_data *) reply_size;
    int (*)(struct sk_buff *, const struct ethnl_req_info *, const struct ethnl_reply_data *) fill_reply;
    void (*)(struct ethnl_reply_data *) cleanup_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ethnl_request_ops {
    u8 request_cmd;
    u8 reply_cmd;
    u16 hdr_attr;
    unsigned int req_info_size;
    unsigned int reply_data_size;
    bool allow_nodev_do;
    int (*)(struct ethnl_req_info *, struct nlattr * *, struct netlink_ext_ack *) parse_request;
    int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, struct genl_info *) prepare_data;
    int (*)(const struct ethnl_req_info *, const struct ethnl_reply_data *) reply_size;
    int (*)(struct sk_buff *, const struct ethnl_req_info *, const struct ethnl_reply_data *) fill_reply;
    void (*)(struct ethnl_reply_data *) cleanup_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ethnl_request_ops {
    u8 request_cmd;
    u8 reply_cmd;
    u16 hdr_attr;
    unsigned int req_info_size;
    unsigned int reply_data_size;
    bool allow_nodev_do;
    int (*)(struct ethnl_req_info *, struct nlattr * *, struct netlink_ext_ack *) parse_request;
    int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, struct genl_info *) prepare_data;
    int (*)(const struct ethnl_req_info *, const struct ethnl_reply_data *) reply_size;
    int (*)(struct sk_buff *, const struct ethnl_req_info *, const struct ethnl_reply_data *) fill_reply;
    void (*)(struct ethnl_reply_data *) cleanup_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ethnl_request_ops {
    u8 request_cmd;
    u8 reply_cmd;
    u16 hdr_attr;
    unsigned int req_info_size;
    unsigned int reply_data_size;
    bool allow_nodev_do;
    int (*)(struct ethnl_req_info *, struct nlattr * *, struct netlink_ext_ack *) parse_request;
    int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, struct genl_info *) prepare_data;
    int (*)(const struct ethnl_req_info *, const struct ethnl_reply_data *) reply_size;
    int (*)(struct sk_buff *, const struct ethnl_req_info *, const struct ethnl_reply_data *) fill_reply;
    void (*)(struct ethnl_reply_data *) cleanup_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ethnl_request_ops {
    u8 request_cmd;
    u8 reply_cmd;
    u16 hdr_attr;
    unsigned int req_info_size;
    unsigned int reply_data_size;
    bool allow_nodev_do;
    int (*)(struct ethnl_req_info *, struct nlattr * *, struct netlink_ext_ack *) parse_request;
    int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, struct genl_info *) prepare_data;
    int (*)(const struct ethnl_req_info *, const struct ethnl_reply_data *) reply_size;
    int (*)(struct sk_buff *, const struct ethnl_req_info *, const struct ethnl_reply_data *) fill_reply;
    void (*)(struct ethnl_reply_data *) cleanup_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ethnl_request_ops {
    u8 request_cmd;
    u8 reply_cmd;
    u16 hdr_attr;
    unsigned int req_info_size;
    unsigned int reply_data_size;
    bool allow_nodev_do;
    int (*)(struct ethnl_req_info *, struct nlattr * *, struct netlink_ext_ack *) parse_request;
    int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, struct genl_info *) prepare_data;
    int (*)(const struct ethnl_req_info *, const struct ethnl_reply_data *) reply_size;
    int (*)(struct sk_buff *, const struct ethnl_req_info *, const struct ethnl_reply_data *) fill_reply;
    void (*)(struct ethnl_reply_data *) cleanup_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ethnl_request_ops {
    u8 request_cmd;
    u8 reply_cmd;
    u16 hdr_attr;
    unsigned int req_info_size;
    unsigned int reply_data_size;
    bool allow_nodev_do;
    u8 set_ntf_cmd;
    int (*)(struct ethnl_req_info *, struct nlattr * *, struct netlink_ext_ack *) parse_request;
    int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, struct genl_info *) prepare_data;
    int (*)(const struct ethnl_req_info *, const struct ethnl_reply_data *) reply_size;
    int (*)(struct sk_buff *, const struct ethnl_req_info *, const struct ethnl_reply_data *) fill_reply;
    void (*)(struct ethnl_reply_data *) cleanup_data;
    int (*)(struct ethnl_req_info *, struct genl_info *) set_validate;
    int (*)(struct ethnl_req_info *, struct genl_info *) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ethnl_request_ops {
    u8 request_cmd;
    u8 reply_cmd;
    u16 hdr_attr;
    unsigned int req_info_size;
    unsigned int reply_data_size;
    bool allow_nodev_do;
    u8 set_ntf_cmd;
    int (*)(struct ethnl_req_info *, struct nlattr * *, struct netlink_ext_ack *) parse_request;
    int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, const struct genl_info *) prepare_data;
    int (*)(const struct ethnl_req_info *, const struct ethnl_reply_data *) reply_size;
    int (*)(struct sk_buff *, const struct ethnl_req_info *, const struct ethnl_reply_data *) fill_reply;
    void (*)(struct ethnl_reply_data *) cleanup_data;
    int (*)(struct ethnl_req_info *, struct genl_info *) set_validate;
    int (*)(struct ethnl_req_info *, struct genl_info *) set;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct ethnl_request_ops {
    u8 request_cmd;
    u8 reply_cmd;
    u16 hdr_attr;
    unsigned int max_attr;
    unsigned int req_info_size;
    unsigned int reply_data_size;
    const struct nla_policy * request_policy;
    bool allow_nodev_do;
    int (*)(struct ethnl_req_info *, struct nlattr * *, struct netlink_ext_ack *) parse_request;
    int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, struct genl_info *) prepare_data;
    int (*)(const struct ethnl_req_info *, const struct ethnl_reply_data *) reply_size;
    int (*)(struct sk_buff *, const struct ethnl_req_info *, const struct ethnl_reply_data *) fill_reply;
    void (*)(struct ethnl_reply_data *) cleanup_data;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int max_attr</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct nla_policy * request_policy</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 set_ntf_cmd</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ethnl_req_info *, struct genl_info *) set_validate</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ethnl_req_info *, struct genl_info *) set</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, struct genl_info *) prepare_data</code> ➡️ <code>int (*)(const struct ethnl_req_info *, struct ethnl_reply_data *, const struct genl_info *) prepare_data</code>
</li>
</ul>
</details>
</li>
</ul>
