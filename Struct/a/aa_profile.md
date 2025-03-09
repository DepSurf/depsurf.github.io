# Struct: <code>aa_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net net;
    struct aa_rlimit rlimits;
    unsigned char * hash;
    char * dirname;
    struct dentry *[6] dents;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net net;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net net;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net net;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net net;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    int secmark_count;
    struct aa_secmark * secmark;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    int secmark_count;
    struct aa_secmark * secmark;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    int secmark_count;
    struct aa_secmark * secmark;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    int secmark_count;
    struct aa_secmark * secmark;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    struct aa_attachment attach;
    struct list_head rules;
    struct aa_net_compat * net_compat;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    struct aa_attachment attach;
    struct list_head rules;
    struct aa_net_compat * net_compat;
    struct aa_audit_cache learning_cache;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[10] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    struct aa_attachment attach;
    struct list_head rules;
    struct aa_net_compat * net_compat;
    struct aa_audit_cache learning_cache;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[10] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    int signal;
    const char * disconnected;
    struct aa_attachment attach;
    struct list_head rules;
    struct aa_net_compat * net_compat;
    struct aa_audit_cache learning_cache;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[10] dents;
    struct rhashtable * data;
    struct aa_label label;
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
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
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
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct aa_profile {
    struct aa_policy base;
    struct aa_profile * parent;
    struct aa_ns * ns;
    const char * rename;
    const char * attach;
    struct aa_dfa * xmatch;
    int xmatch_len;
    enum audit_mode audit;
    long int mode;
    u32 path_flags;
    const char * disconnected;
    int size;
    struct aa_policydb policy;
    struct aa_file_rules file;
    struct aa_caps caps;
    struct aa_net_compat * net_compat;
    int xattr_count;
    char * * xattrs;
    struct aa_rlimit rlimits;
    struct aa_loaddata * rawdata;
    unsigned char * hash;
    char * dirname;
    struct dentry *[9] dents;
    struct rhashtable * data;
    struct aa_label label;
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
<code>struct aa_loaddata * rawdata</code>
</li>
<li>
<b>Field added. </b>
<code>struct rhashtable * data</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dentry *[6] dents</code> ➡️ <code>struct dentry *[9] dents</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct aa_net_compat * net_compat</code>
</li>
<li>
<b>Field added. </b>
<code>int xattr_count</code>
</li>
<li>
<b>Field added. </b>
<code>char * * xattrs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aa_net net</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int secmark_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct aa_secmark * secmark</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head rules</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aa_dfa * xmatch</code>
</li>
<li>
<b>Field removed. </b>
<code>int xmatch_len</code>
</li>
<li>
<b>Field removed. </b>
<code>int size</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aa_policydb policy</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aa_file_rules file</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aa_caps caps</code>
</li>
<li>
<b>Field removed. </b>
<code>int xattr_count</code>
</li>
<li>
<b>Field removed. </b>
<code>char * * xattrs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aa_rlimit rlimits</code>
</li>
<li>
<b>Field removed. </b>
<code>int secmark_count</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aa_secmark * secmark</code>
</li>
<li>
<b>Field type changed. </b>
<code>const char * attach</code> ➡️ <code>struct aa_attachment attach</code>
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
<code>struct aa_audit_cache learning_cache</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dentry *[9] dents</code> ➡️ <code>struct dentry *[10] dents</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int signal</code>
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
