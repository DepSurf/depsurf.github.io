# Struct: <code>nameidata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    unsigned int r_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    unsigned int root_seq;
    int dfd;
    kuid_t dir_uid;
    umode_t dir_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    unsigned int r_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    unsigned int root_seq;
    int dfd;
    kuid_t dir_uid;
    umode_t dir_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    unsigned int r_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    unsigned int root_seq;
    int dfd;
    kuid_t dir_uid;
    umode_t dir_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int state;
    unsigned int seq;
    unsigned int m_seq;
    unsigned int r_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    unsigned int root_seq;
    int dfd;
    kuid_t dir_uid;
    umode_t dir_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int state;
    unsigned int seq;
    unsigned int m_seq;
    unsigned int r_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    unsigned int root_seq;
    int dfd;
    kuid_t dir_uid;
    umode_t dir_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int state;
    unsigned int seq;
    unsigned int next_seq;
    unsigned int m_seq;
    unsigned int r_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    unsigned int root_seq;
    int dfd;
    vfsuid_t dir_vfsuid;
    umode_t dir_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int state;
    unsigned int seq;
    unsigned int next_seq;
    unsigned int m_seq;
    unsigned int r_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    unsigned int root_seq;
    int dfd;
    vfsuid_t dir_vfsuid;
    umode_t dir_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int state;
    unsigned int seq;
    unsigned int next_seq;
    unsigned int m_seq;
    unsigned int r_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    unsigned int root_seq;
    int dfd;
    vfsuid_t dir_vfsuid;
    umode_t dir_mode;
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
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
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
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nameidata {
    struct path path;
    struct qstr last;
    struct path root;
    struct inode * inode;
    unsigned int flags;
    unsigned int seq;
    unsigned int m_seq;
    int last_type;
    unsigned int depth;
    int total_link_count;
    struct saved * stack;
    struct saved[2] internal;
    struct filename * name;
    struct nameidata * saved;
    struct inode * link_inode;
    unsigned int root_seq;
    int dfd;
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
<code>struct inode * link_inode</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int r_seq</code>
</li>
<li>
<b>Field added. </b>
<code>kuid_t dir_uid</code>
</li>
<li>
<b>Field added. </b>
<code>umode_t dir_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>struct inode * link_inode</code>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int state</code>
</li>
</ul>
</details>
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
<code>unsigned int next_seq</code>
</li>
<li>
<b>Field added. </b>
<code>vfsuid_t dir_vfsuid</code>
</li>
<li>
<b>Field removed. </b>
<code>kuid_t dir_uid</code>
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
