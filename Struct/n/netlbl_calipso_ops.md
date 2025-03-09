# Struct: <code>netlbl_calipso_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
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
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
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
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct netlbl_calipso_ops {
    int (*)(struct calipso_doi *, struct netlbl_audit *) doi_add;
    void (*)(struct calipso_doi *) doi_free;
    int (*)(u32, struct netlbl_audit *) doi_remove;
    struct calipso_doi * (*)(u32) doi_getdef;
    void (*)(struct calipso_doi *) doi_putdef;
    int (*)(u32 *, int (*)(struct calipso_doi *, void *), void *) doi_walk;
    int (*)(struct sock *, struct netlbl_lsm_secattr *) sock_getattr;
    int (*)(struct sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) sock_setattr;
    void (*)(struct sock *) sock_delattr;
    int (*)(struct request_sock *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) req_setattr;
    void (*)(struct request_sock *) req_delattr;
    int (*)(const unsigned char *, struct netlbl_lsm_secattr *) opt_getattr;
    unsigned char * (*)(const struct sk_buff *) skbuff_optptr;
    int (*)(struct sk_buff *, const struct calipso_doi *, const struct netlbl_lsm_secattr *) skbuff_setattr;
    int (*)(struct sk_buff *) skbuff_delattr;
    void (*)() cache_invalidate;
    int (*)(const unsigned char *, const struct netlbl_lsm_secattr *) cache_add;
}
```
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
