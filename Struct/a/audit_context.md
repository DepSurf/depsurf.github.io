# Struct: <code>audit_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    struct lsmblob target_lsm;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    struct lsmblob target_lsm;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    struct lsmblob target_lsm;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    struct lsmblob target_lsm;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    enum (anon) context;
    enum audit_state state;
    enum audit_state current_state;
    struct audit_stamp stamp;
    int major;
    int uring_op;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    struct lsmblob target_lsm;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct open_how openat2;
    struct (anon) execve;
    struct (anon) module;
    struct (anon) time;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    enum (anon) context;
    enum audit_state state;
    enum audit_state current_state;
    struct audit_stamp stamp;
    int major;
    int uring_op;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    struct lsmblob target_lsm;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct open_how openat2;
    struct (anon) execve;
    struct (anon) module;
    struct (anon) time;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    enum (anon) context;
    enum audit_state state;
    enum audit_state current_state;
    struct audit_stamp stamp;
    int major;
    int uring_op;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    struct lsmblob target_lsm;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct open_how openat2;
    struct (anon) execve;
    struct (anon) module;
    struct (anon) time;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    enum (anon) context;
    enum audit_state state;
    enum audit_state current_state;
    struct audit_stamp stamp;
    int major;
    int uring_op;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    struct lsmblob target_blob;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct open_how openat2;
    struct (anon) execve;
    struct (anon) module;
    struct (anon) time;
    int[2] fds;
    struct audit_proctitle proctitle;
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
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
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
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct audit_context {
    int dummy;
    int in_syscall;
    enum audit_state state;
    enum audit_state current_state;
    unsigned int serial;
    int major;
    struct timespec64 ctime;
    long unsigned int[4] argv;
    long int return_code;
    u64 prio;
    int return_valid;
    struct audit_names[5] preallocated_names;
    int name_count;
    struct list_head names_list;
    char * filterkey;
    struct path pwd;
    struct audit_aux_data * aux;
    struct audit_aux_data * aux_pids;
    struct __kernel_sockaddr_storage * sockaddr;
    size_t sockaddr_len;
    pid_t pid;
    pid_t ppid;
    kuid_t uid;
    kuid_t euid;
    kuid_t suid;
    kuid_t fsuid;
    kgid_t gid;
    kgid_t egid;
    kgid_t sgid;
    kgid_t fsgid;
    long unsigned int personality;
    int arch;
    pid_t target_pid;
    kuid_t target_auid;
    kuid_t target_uid;
    unsigned int target_sessionid;
    u32 target_sid;
    char[16] target_comm;
    struct audit_tree_refs * trees;
    struct audit_tree_refs * first_trees;
    struct list_head killed_trees;
    int tree_count;
    int type;
    struct (anon) socketcall;
    struct (anon) ipc;
    struct (anon) mq_getsetattr;
    struct (anon) mq_notify;
    struct (anon) mq_sendrecv;
    struct (anon) mq_open;
    struct (anon) capset;
    struct (anon) mmap;
    struct (anon) execve;
    struct (anon) module;
    int[2] fds;
    struct audit_proctitle proctitle;
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
<code>struct (anon) module</code>
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
<b>Field type changed. </b>
<code>struct timespec ctime</code> ➡️ <code>struct timespec64 ctime</code>
</li>
</ul>
</details>
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
<code>struct lsmblob target_lsm</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 target_sid</code>
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum (anon) context</code>
</li>
<li>
<b>Field added. </b>
<code>struct audit_stamp stamp</code>
</li>
<li>
<b>Field added. </b>
<code>int uring_op</code>
</li>
<li>
<b>Field added. </b>
<code>struct open_how openat2</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) time</code>
</li>
<li>
<b>Field removed. </b>
<code>int in_syscall</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int serial</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timespec64 ctime</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>pid_t pid</code>
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
<code>struct lsmblob target_blob</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lsmblob target_lsm</code>
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
