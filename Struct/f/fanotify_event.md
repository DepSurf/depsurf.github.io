# Struct: <code>fanotify_event</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    enum fanotify_event_type type;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    enum fanotify_event_type type;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    struct hlist_node merge_list;
    u32 mask;
    unsigned int type;
    unsigned int hash;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    struct hlist_node merge_list;
    u32 mask;
    unsigned int type;
    unsigned int hash;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    struct hlist_node merge_list;
    u32 mask;
    unsigned int type;
    unsigned int hash;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    struct hlist_node merge_list;
    u32 mask;
    unsigned int type;
    unsigned int hash;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    struct hlist_node merge_list;
    u32 mask;
    unsigned int type;
    unsigned int hash;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    struct hlist_node merge_list;
    u32 mask;
    unsigned int type;
    unsigned int hash;
    struct pid * pid;
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
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
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
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct fanotify_event {
    struct fsnotify_event fse;
    u32 mask;
    u8 fh_type;
    u8 fh_len;
    u16 pad;
    struct path path;
    struct fanotify_fid fid;
    struct pid * pid;
}
```
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
<code>enum fanotify_event_type type</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 fh_type</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 fh_len</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 pad</code>
</li>
<li>
<b>Field removed. </b>
<code>struct path path</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fanotify_fid fid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node merge_list</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int hash</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum fanotify_event_type type</code> ➡️ <code>unsigned int type</code>
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
