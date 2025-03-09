# Struct: <code>console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *) exit;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *) exit;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *) exit;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *) exit;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    uint ispeed;
    uint ospeed;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *) exit;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    uint ispeed;
    uint ospeed;
    u64 seq;
    long unsigned int dropped;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *) exit;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    uint ispeed;
    uint ospeed;
    u64 seq;
    long unsigned int dropped;
    void * data;
    struct hlist_node node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *) exit;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    uint ispeed;
    uint ospeed;
    u64 seq;
    long unsigned int dropped;
    void * data;
    struct hlist_node node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *) exit;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    uint ispeed;
    uint ospeed;
    u64 seq;
    long unsigned int dropped;
    void * data;
    struct hlist_node node;
    bool (*)(struct console *, struct nbcon_write_context *) write_atomic;
    atomic_t nbcon_state;
    atomic_long_t nbcon_seq;
    struct printk_buffers * pbufs;
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
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
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
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct console {
    char[16] name;
    void (*)(struct console *, const char *, unsigned int) write;
    int (*)(struct console *, char *, unsigned int) read;
    struct tty_driver * (*)(struct console *, int *) device;
    void (*)() unblank;
    int (*)(struct console *, char *) setup;
    int (*)(struct console *, char *, int, char *) match;
    short int flags;
    short int index;
    int cflag;
    void * data;
    struct console * next;
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct console *) exit</code>
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
<code>uint ispeed</code>
</li>
<li>
<b>Field added. </b>
<code>uint ospeed</code>
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
<code>u64 seq</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int dropped</code>
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
<code>struct hlist_node node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct console * next</code>
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
<code>bool (*)(struct console *, struct nbcon_write_context *) write_atomic</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t nbcon_state</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t nbcon_seq</code>
</li>
<li>
<b>Field added. </b>
<code>struct printk_buffers * pbufs</code>
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
