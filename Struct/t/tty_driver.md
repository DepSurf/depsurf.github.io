# Struct: <code>tty_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tty_driver {
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
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
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
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
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tty_driver {
    int magic;
    struct kref kref;
    struct cdev * * cdevs;
    struct module * owner;
    const char * driver_name;
    const char * name;
    int name_base;
    int major;
    int minor_start;
    unsigned int num;
    short int type;
    short int subtype;
    struct ktermios init_termios;
    long unsigned int flags;
    struct proc_dir_entry * proc_entry;
    struct tty_driver * other;
    struct tty_struct * * ttys;
    struct tty_port * * ports;
    struct ktermios * * termios;
    void * driver_state;
    const struct tty_operations * ops;
    struct list_head tty_drivers;
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int magic</code>
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
