# Struct: <code>xattr_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * prefix;
    int flags;
    size_t (*)(const struct xattr_handler *, struct dentry *, char *, size_t, const char *, size_t) list;
    int (*)(const struct xattr_handler *, struct dentry *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct user_namespace *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct user_namespace *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct user_namespace *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct user_namespace *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct mnt_idmap *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct mnt_idmap *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
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
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
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
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xattr_handler {
    const char * name;
    const char * prefix;
    int flags;
    bool (*)(struct dentry *) list;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get;
    int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set;
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
<code>const char * name</code>
</li>
<li>
<b>Field type changed. </b>
<code>size_t (*)(const struct xattr_handler *, struct dentry *, char *, size_t, const char *, size_t) list</code> ➡️ <code>bool (*)(struct dentry *) list</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct xattr_handler *, struct dentry *, const char *, void *, size_t) get</code> ➡️ <code>int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, void *, size_t) get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct xattr_handler *, struct dentry *, const char *, const void *, size_t, int) set</code> ➡️ <code>int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct xattr_handler *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set</code> ➡️ <code>int (*)(const struct xattr_handler *, struct user_namespace *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set</code>
</li>
</ul>
</details>
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
<b>Field type changed. </b>
<code>int (*)(const struct xattr_handler *, struct user_namespace *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set</code> ➡️ <code>int (*)(const struct xattr_handler *, struct mnt_idmap *, struct dentry *, struct inode *, const char *, const void *, size_t, int) set</code>
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
