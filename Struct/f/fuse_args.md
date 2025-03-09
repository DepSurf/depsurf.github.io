# Struct: <code>fuse_args</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    struct (anon) in;
    struct (anon) out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    struct (anon) in;
    struct (anon) out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    struct (anon) in;
    struct (anon) out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    struct (anon) in;
    struct (anon) out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    struct (anon) in;
    struct (anon) out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    struct (anon) in;
    struct (anon) out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    struct (anon) in;
    struct (anon) out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    struct (anon) in;
    struct (anon) out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_conn *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    bool may_block;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_conn *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    bool may_block;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_mount *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    bool may_block;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_mount *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool user_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    bool may_block;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_mount *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool user_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    bool may_block;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_mount *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool user_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    bool may_block;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_mount *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    uint8_t in_numargs;
    uint8_t out_numargs;
    uint8_t ext_idx;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool user_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    bool may_block;
    bool is_ext;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_mount *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    uint8_t in_numargs;
    uint8_t out_numargs;
    uint8_t ext_idx;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool user_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    bool may_block;
    bool is_ext;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_mount *, struct fuse_args *, int) end;
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
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_conn *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_conn *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_conn *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_conn *, struct fuse_args *, int) end;
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
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_conn *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_conn *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_conn *, struct fuse_args *, int) end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fuse_args {
    uint64_t nodeid;
    uint32_t opcode;
    short unsigned int in_numargs;
    short unsigned int out_numargs;
    bool force;
    bool noreply;
    bool nocreds;
    bool in_pages;
    bool out_pages;
    bool out_argvar;
    bool page_zeroing;
    bool page_replace;
    struct fuse_in_arg[3] in_args;
    struct fuse_arg[2] out_args;
    void (*)(struct fuse_conn *, struct fuse_args *, int) end;
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>uint64_t nodeid</code>
</li>
<li>
<b>Field added. </b>
<code>uint32_t opcode</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int in_numargs</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int out_numargs</code>
</li>
<li>
<b>Field added. </b>
<code>bool force</code>
</li>
<li>
<b>Field added. </b>
<code>bool noreply</code>
</li>
<li>
<b>Field added. </b>
<code>bool nocreds</code>
</li>
<li>
<b>Field added. </b>
<code>bool in_pages</code>
</li>
<li>
<b>Field added. </b>
<code>bool out_pages</code>
</li>
<li>
<b>Field added. </b>
<code>bool out_argvar</code>
</li>
<li>
<b>Field added. </b>
<code>bool page_zeroing</code>
</li>
<li>
<b>Field added. </b>
<code>bool page_replace</code>
</li>
<li>
<b>Field added. </b>
<code>struct fuse_in_arg[3] in_args</code>
</li>
<li>
<b>Field added. </b>
<code>struct fuse_arg[2] out_args</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct fuse_conn *, struct fuse_args *, int) end</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) in</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) out</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool may_block</code>
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
<code>void (*)(struct fuse_conn *, struct fuse_args *, int) end</code> ➡️ <code>void (*)(struct fuse_mount *, struct fuse_args *, int) end</code>
</li>
</ul>
</details>
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
<code>bool user_pages</code>
</li>
</ul>
</details>
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
<code>uint8_t ext_idx</code>
</li>
<li>
<b>Field added. </b>
<code>bool is_ext</code>
</li>
<li>
<b>Field type changed. </b>
<code>short unsigned int in_numargs</code> ➡️ <code>uint8_t in_numargs</code>
</li>
<li>
<b>Field type changed. </b>
<code>short unsigned int out_numargs</code> ➡️ <code>uint8_t out_numargs</code>
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
