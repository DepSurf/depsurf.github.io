# Struct: <code>proto_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int) accept;
    int (*)(struct socket *, struct sockaddr *, int *, int) getname;
    unsigned int (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int) accept;
    int (*)(struct socket *, struct sockaddr *, int *, int) getname;
    unsigned int (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int) accept;
    int (*)(struct socket *, struct sockaddr *, int *, int) getname;
    unsigned int (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int *, int) getname;
    unsigned int (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int *, int) getname;
    unsigned int (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct seq_file *, struct socket *) show_fdinfo;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    unsigned int flags;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    void (*)(struct seq_file *, struct socket *) show_fdinfo;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    void (*)(struct seq_file *, struct socket *) show_fdinfo;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    void (*)(struct seq_file *, struct socket *) show_fdinfo;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    void (*)(struct seq_file *, struct socket *) show_fdinfo;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    void (*)(struct seq_file *, struct socket *) show_fdinfo;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, skb_read_actor_t) read_skb;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    void (*)(struct seq_file *, struct socket *) show_fdinfo;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct socket *) splice_eof;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, skb_read_actor_t) read_skb;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    void (*)(struct seq_file *, struct socket *) show_fdinfo;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    void (*)(struct socket *) splice_eof;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, skb_read_actor_t) read_skb;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
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
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
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
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct proto_ops {
    int family;
    struct module * owner;
    int (*)(struct socket *) release;
    int (*)(struct socket *, struct sockaddr *, int) bind;
    int (*)(struct socket *, struct sockaddr *, int, int) connect;
    int (*)(struct socket *, struct socket *) socketpair;
    int (*)(struct socket *, struct socket *, int, bool) accept;
    int (*)(struct socket *, struct sockaddr *, int) getname;
    __poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll;
    int (*)(struct socket *, unsigned int, long unsigned int) ioctl;
    int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl;
    int (*)(struct socket *, void *, bool, bool) gettstamp;
    int (*)(struct socket *, int) listen;
    int (*)(struct socket *, int) shutdown;
    int (*)(struct socket *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct socket *, int, int, char *, int *) getsockopt;
    int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct socket *, int, int, char *, int *) compat_getsockopt;
    int (*)(struct socket *, struct msghdr *, size_t) sendmsg;
    int (*)(struct socket *, struct msghdr *, size_t, int) recvmsg;
    int (*)(struct file *, struct socket *, struct vm_area_struct *) mmap;
    ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage;
    ssize_t (*)(struct socket *, loff_t *, struct pipe_inode_info *, size_t, unsigned int) splice_read;
    int (*)(struct sock *, int) set_peek_off;
    int (*)(struct socket *) peek_len;
    int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock;
    int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked;
    int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked;
    int (*)(struct sock *, int) set_rcvlowat;
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
<code>int (*)(struct socket *) peek_len</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, read_descriptor_t *, sk_read_actor_t) read_sock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct socket *, struct socket *, int) accept</code> ➡️ <code>int (*)(struct socket *, struct socket *, int, bool) accept</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, struct msghdr *, size_t) sendmsg_locked</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, int) set_rcvlowat</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct socket *, struct sockaddr *, int *, int) getname</code> ➡️ <code>int (*)(struct socket *, struct sockaddr *, int) getname</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int (*)(struct file *, struct socket *, struct poll_table_struct *) poll</code> ➡️ <code>__poll_t (*)(struct file *, struct socket *, struct poll_table_struct *) poll</code>
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
<code>int (*)(struct socket *, void *, bool, bool) gettstamp</code>
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
<code>void (*)(struct seq_file *, struct socket *) show_fdinfo</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct socket *, int, int, char *, int *) compat_getsockopt</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct socket *, int, int, char *, unsigned int) setsockopt</code> ➡️ <code>int (*)(struct socket *, int, int, sockptr_t, unsigned int) setsockopt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int flags</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, skb_read_actor_t) read_skb</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct socket *) splice_eof</code>
</li>
<li>
<b>Field removed. </b>
<code>ssize_t (*)(struct socket *, struct page *, int, size_t, int) sendpage</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, struct page *, int, size_t, int) sendpage_locked</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct socket *, int, int, char *, int *) compat_getsockopt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct socket *, unsigned int, long unsigned int) compat_ioctl</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct socket *, int, int, char *, unsigned int) compat_setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct socket *, int, int, char *, int *) compat_getsockopt</code>
</li>
</ul>
</details>
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
