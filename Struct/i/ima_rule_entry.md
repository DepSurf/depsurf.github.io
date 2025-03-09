# Struct: <code>ima_rule_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    u8[16] fsuuid;
    kuid_t uid;
    kuid_t fowner;
    struct (anon)[6] lsm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    u8[16] fsuuid;
    kuid_t uid;
    kuid_t fowner;
    int pcr;
    struct (anon)[6] lsm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    u8[16] fsuuid;
    kuid_t uid;
    kuid_t fowner;
    int pcr;
    struct (anon)[6] lsm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    char * keyrings;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_rule_opt_list * keyrings;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_rule_opt_list * keyrings;
    struct ima_rule_opt_list * label;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    unsigned int allowed_algos;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_rule_opt_list * keyrings;
    struct ima_rule_opt_list * label;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kgid_t gid;
    kuid_t fowner;
    kgid_t fgroup;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kgid_t, kgid_t) gid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    bool (*)(kgid_t, kgid_t) fgroup_op;
    int pcr;
    unsigned int allowed_algos;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_rule_opt_list * keyrings;
    struct ima_rule_opt_list * label;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kgid_t gid;
    kuid_t fowner;
    kgid_t fgroup;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kgid_t, kgid_t) gid_op;
    bool (*)(vfsuid_t, kuid_t) fowner_op;
    bool (*)(vfsgid_t, kgid_t) fgroup_op;
    int pcr;
    unsigned int allowed_algos;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_rule_opt_list * keyrings;
    struct ima_rule_opt_list * label;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kgid_t gid;
    kuid_t fowner;
    kgid_t fgroup;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kgid_t, kgid_t) gid_op;
    bool (*)(vfsuid_t, kuid_t) fowner_op;
    bool (*)(vfsgid_t, kgid_t) fgroup_op;
    int pcr;
    unsigned int allowed_algos;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_rule_opt_list * keyrings;
    struct ima_rule_opt_list * label;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kgid_t gid;
    kuid_t fowner;
    kgid_t fgroup;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kgid_t, kgid_t) gid_op;
    bool (*)(vfsuid_t, kuid_t) fowner_op;
    bool (*)(vfsgid_t, kgid_t) fgroup_op;
    int pcr;
    unsigned int allowed_algos;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_rule_opt_list * keyrings;
    struct ima_rule_opt_list * label;
    struct ima_template_desc * template;
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
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_template_desc * template;
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
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_template_desc * template;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ima_rule_entry {
    struct list_head list;
    int action;
    unsigned int flags;
    enum ima_hooks func;
    int mask;
    long unsigned int fsmagic;
    uuid_t fsuuid;
    kuid_t uid;
    kuid_t fowner;
    bool (*)(kuid_t, kuid_t) uid_op;
    bool (*)(kuid_t, kuid_t) fowner_op;
    int pcr;
    struct (anon)[6] lsm;
    char * fsname;
    struct ima_template_desc * template;
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
<code>int pcr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(kuid_t, kuid_t) uid_op</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(kuid_t, kuid_t) fowner_op</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[16] fsuuid</code> ➡️ <code>uuid_t fsuuid</code>
</li>
</ul>
</details>
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
<code>char * fsname</code>
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
<code>struct ima_template_desc * template</code>
</li>
</ul>
</details>
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
<code>char * keyrings</code>
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
<code>char * keyrings</code> ➡️ <code>struct ima_rule_opt_list * keyrings</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ima_rule_opt_list * label</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int allowed_algos</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>kgid_t gid</code>
</li>
<li>
<b>Field added. </b>
<code>kgid_t fgroup</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(kgid_t, kgid_t) gid_op</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(kgid_t, kgid_t) fgroup_op</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>bool (*)(kuid_t, kuid_t) fowner_op</code> ➡️ <code>bool (*)(vfsuid_t, kuid_t) fowner_op</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(kgid_t, kgid_t) fgroup_op</code> ➡️ <code>bool (*)(vfsgid_t, kgid_t) fgroup_op</code>
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
