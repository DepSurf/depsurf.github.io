# Struct: <code>ppp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
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
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
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
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ppp {
    struct ppp_file file;
    struct file * owner;
    struct list_head channels;
    int n_channels;
    spinlock_t rlock;
    spinlock_t wlock;
    int * xmit_recursion;
    int mru;
    unsigned int flags;
    unsigned int xstate;
    unsigned int rstate;
    int debug;
    struct slcompress * vj;
    enum NPmode[6] npmode;
    struct sk_buff * xmit_pending;
    struct compressor * xcomp;
    void * xc_state;
    struct compressor * rcomp;
    void * rc_state;
    long unsigned int last_xmit;
    long unsigned int last_recv;
    struct net_device * dev;
    int closing;
    int nxchan;
    u32 nxseq;
    int mrru;
    u32 nextseq;
    u32 minseq;
    struct sk_buff_head mrq;
    struct bpf_prog * pass_filter;
    struct bpf_prog * active_filter;
    struct net * ppp_net;
    struct ppp_link_stats stats64;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int * xmit_recursion</code>
</li>
</ul>
</details>
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
