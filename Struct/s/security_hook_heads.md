# Struct: <code>security_hook_heads</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct list_head binder_set_context_mgr;
    struct list_head binder_transaction;
    struct list_head binder_transfer_binder;
    struct list_head binder_transfer_file;
    struct list_head ptrace_access_check;
    struct list_head ptrace_traceme;
    struct list_head capget;
    struct list_head capset;
    struct list_head capable;
    struct list_head quotactl;
    struct list_head quota_on;
    struct list_head syslog;
    struct list_head settime;
    struct list_head vm_enough_memory;
    struct list_head bprm_set_creds;
    struct list_head bprm_check_security;
    struct list_head bprm_secureexec;
    struct list_head bprm_committing_creds;
    struct list_head bprm_committed_creds;
    struct list_head sb_alloc_security;
    struct list_head sb_free_security;
    struct list_head sb_copy_data;
    struct list_head sb_remount;
    struct list_head sb_kern_mount;
    struct list_head sb_show_options;
    struct list_head sb_statfs;
    struct list_head sb_mount;
    struct list_head sb_umount;
    struct list_head sb_pivotroot;
    struct list_head sb_set_mnt_opts;
    struct list_head sb_clone_mnt_opts;
    struct list_head sb_parse_opts_str;
    struct list_head dentry_init_security;
    struct list_head path_unlink;
    struct list_head path_mkdir;
    struct list_head path_rmdir;
    struct list_head path_mknod;
    struct list_head path_truncate;
    struct list_head path_symlink;
    struct list_head path_link;
    struct list_head path_rename;
    struct list_head path_chmod;
    struct list_head path_chown;
    struct list_head path_chroot;
    struct list_head inode_alloc_security;
    struct list_head inode_free_security;
    struct list_head inode_init_security;
    struct list_head inode_create;
    struct list_head inode_link;
    struct list_head inode_unlink;
    struct list_head inode_symlink;
    struct list_head inode_mkdir;
    struct list_head inode_rmdir;
    struct list_head inode_mknod;
    struct list_head inode_rename;
    struct list_head inode_readlink;
    struct list_head inode_follow_link;
    struct list_head inode_permission;
    struct list_head inode_setattr;
    struct list_head inode_getattr;
    struct list_head inode_setxattr;
    struct list_head inode_post_setxattr;
    struct list_head inode_getxattr;
    struct list_head inode_listxattr;
    struct list_head inode_removexattr;
    struct list_head inode_need_killpriv;
    struct list_head inode_killpriv;
    struct list_head inode_getsecurity;
    struct list_head inode_setsecurity;
    struct list_head inode_listsecurity;
    struct list_head inode_getsecid;
    struct list_head file_permission;
    struct list_head file_alloc_security;
    struct list_head file_free_security;
    struct list_head file_ioctl;
    struct list_head mmap_addr;
    struct list_head mmap_file;
    struct list_head file_mprotect;
    struct list_head file_lock;
    struct list_head file_fcntl;
    struct list_head file_set_fowner;
    struct list_head file_send_sigiotask;
    struct list_head file_receive;
    struct list_head file_open;
    struct list_head task_create;
    struct list_head task_free;
    struct list_head cred_alloc_blank;
    struct list_head cred_free;
    struct list_head cred_prepare;
    struct list_head cred_transfer;
    struct list_head kernel_act_as;
    struct list_head kernel_create_files_as;
    struct list_head kernel_fw_from_file;
    struct list_head kernel_module_request;
    struct list_head kernel_module_from_file;
    struct list_head task_fix_setuid;
    struct list_head task_setpgid;
    struct list_head task_getpgid;
    struct list_head task_getsid;
    struct list_head task_getsecid;
    struct list_head task_setnice;
    struct list_head task_setioprio;
    struct list_head task_getioprio;
    struct list_head task_setrlimit;
    struct list_head task_setscheduler;
    struct list_head task_getscheduler;
    struct list_head task_movememory;
    struct list_head task_kill;
    struct list_head task_wait;
    struct list_head task_prctl;
    struct list_head task_to_inode;
    struct list_head ipc_permission;
    struct list_head ipc_getsecid;
    struct list_head msg_msg_alloc_security;
    struct list_head msg_msg_free_security;
    struct list_head msg_queue_alloc_security;
    struct list_head msg_queue_free_security;
    struct list_head msg_queue_associate;
    struct list_head msg_queue_msgctl;
    struct list_head msg_queue_msgsnd;
    struct list_head msg_queue_msgrcv;
    struct list_head shm_alloc_security;
    struct list_head shm_free_security;
    struct list_head shm_associate;
    struct list_head shm_shmctl;
    struct list_head shm_shmat;
    struct list_head sem_alloc_security;
    struct list_head sem_free_security;
    struct list_head sem_associate;
    struct list_head sem_semctl;
    struct list_head sem_semop;
    struct list_head netlink_send;
    struct list_head d_instantiate;
    struct list_head getprocattr;
    struct list_head setprocattr;
    struct list_head ismaclabel;
    struct list_head secid_to_secctx;
    struct list_head secctx_to_secid;
    struct list_head release_secctx;
    struct list_head inode_notifysecctx;
    struct list_head inode_setsecctx;
    struct list_head inode_getsecctx;
    struct list_head unix_stream_connect;
    struct list_head unix_may_send;
    struct list_head socket_create;
    struct list_head socket_post_create;
    struct list_head socket_bind;
    struct list_head socket_connect;
    struct list_head socket_listen;
    struct list_head socket_accept;
    struct list_head socket_sendmsg;
    struct list_head socket_recvmsg;
    struct list_head socket_getsockname;
    struct list_head socket_getpeername;
    struct list_head socket_getsockopt;
    struct list_head socket_setsockopt;
    struct list_head socket_shutdown;
    struct list_head socket_sock_rcv_skb;
    struct list_head socket_getpeersec_stream;
    struct list_head socket_getpeersec_dgram;
    struct list_head sk_alloc_security;
    struct list_head sk_free_security;
    struct list_head sk_clone_security;
    struct list_head sk_getsecid;
    struct list_head sock_graft;
    struct list_head inet_conn_request;
    struct list_head inet_csk_clone;
    struct list_head inet_conn_established;
    struct list_head secmark_relabel_packet;
    struct list_head secmark_refcount_inc;
    struct list_head secmark_refcount_dec;
    struct list_head req_classify_flow;
    struct list_head tun_dev_alloc_security;
    struct list_head tun_dev_free_security;
    struct list_head tun_dev_create;
    struct list_head tun_dev_attach_queue;
    struct list_head tun_dev_attach;
    struct list_head tun_dev_open;
    struct list_head skb_owned_by;
    struct list_head xfrm_policy_alloc_security;
    struct list_head xfrm_policy_clone_security;
    struct list_head xfrm_policy_free_security;
    struct list_head xfrm_policy_delete_security;
    struct list_head xfrm_state_alloc;
    struct list_head xfrm_state_alloc_acquire;
    struct list_head xfrm_state_free_security;
    struct list_head xfrm_state_delete_security;
    struct list_head xfrm_policy_lookup;
    struct list_head xfrm_state_pol_flow_match;
    struct list_head xfrm_decode_session;
    struct list_head key_alloc;
    struct list_head key_free;
    struct list_head key_permission;
    struct list_head key_getsecurity;
    struct list_head audit_rule_init;
    struct list_head audit_rule_known;
    struct list_head audit_rule_match;
    struct list_head audit_rule_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct list_head binder_set_context_mgr;
    struct list_head binder_transaction;
    struct list_head binder_transfer_binder;
    struct list_head binder_transfer_file;
    struct list_head ptrace_access_check;
    struct list_head ptrace_traceme;
    struct list_head capget;
    struct list_head capset;
    struct list_head capable;
    struct list_head quotactl;
    struct list_head quota_on;
    struct list_head syslog;
    struct list_head settime;
    struct list_head vm_enough_memory;
    struct list_head bprm_set_creds;
    struct list_head bprm_check_security;
    struct list_head bprm_secureexec;
    struct list_head bprm_committing_creds;
    struct list_head bprm_committed_creds;
    struct list_head sb_alloc_security;
    struct list_head sb_free_security;
    struct list_head sb_copy_data;
    struct list_head sb_remount;
    struct list_head sb_kern_mount;
    struct list_head sb_show_options;
    struct list_head sb_statfs;
    struct list_head sb_mount;
    struct list_head sb_umount;
    struct list_head sb_pivotroot;
    struct list_head sb_set_mnt_opts;
    struct list_head sb_clone_mnt_opts;
    struct list_head sb_parse_opts_str;
    struct list_head dentry_init_security;
    struct list_head path_unlink;
    struct list_head path_mkdir;
    struct list_head path_rmdir;
    struct list_head path_mknod;
    struct list_head path_truncate;
    struct list_head path_symlink;
    struct list_head path_link;
    struct list_head path_rename;
    struct list_head path_chmod;
    struct list_head path_chown;
    struct list_head path_chroot;
    struct list_head inode_alloc_security;
    struct list_head inode_free_security;
    struct list_head inode_init_security;
    struct list_head inode_create;
    struct list_head inode_link;
    struct list_head inode_unlink;
    struct list_head inode_symlink;
    struct list_head inode_mkdir;
    struct list_head inode_rmdir;
    struct list_head inode_mknod;
    struct list_head inode_rename;
    struct list_head inode_readlink;
    struct list_head inode_follow_link;
    struct list_head inode_permission;
    struct list_head inode_setattr;
    struct list_head inode_getattr;
    struct list_head inode_setxattr;
    struct list_head inode_post_setxattr;
    struct list_head inode_getxattr;
    struct list_head inode_listxattr;
    struct list_head inode_removexattr;
    struct list_head inode_need_killpriv;
    struct list_head inode_killpriv;
    struct list_head inode_getsecurity;
    struct list_head inode_setsecurity;
    struct list_head inode_listsecurity;
    struct list_head inode_getsecid;
    struct list_head file_permission;
    struct list_head file_alloc_security;
    struct list_head file_free_security;
    struct list_head file_ioctl;
    struct list_head mmap_addr;
    struct list_head mmap_file;
    struct list_head file_mprotect;
    struct list_head file_lock;
    struct list_head file_fcntl;
    struct list_head file_set_fowner;
    struct list_head file_send_sigiotask;
    struct list_head file_receive;
    struct list_head file_open;
    struct list_head task_create;
    struct list_head task_free;
    struct list_head cred_alloc_blank;
    struct list_head cred_free;
    struct list_head cred_prepare;
    struct list_head cred_transfer;
    struct list_head kernel_act_as;
    struct list_head kernel_create_files_as;
    struct list_head kernel_read_file;
    struct list_head kernel_post_read_file;
    struct list_head kernel_module_request;
    struct list_head task_fix_setuid;
    struct list_head task_setpgid;
    struct list_head task_getpgid;
    struct list_head task_getsid;
    struct list_head task_getsecid;
    struct list_head task_setnice;
    struct list_head task_setioprio;
    struct list_head task_getioprio;
    struct list_head task_setrlimit;
    struct list_head task_setscheduler;
    struct list_head task_getscheduler;
    struct list_head task_movememory;
    struct list_head task_kill;
    struct list_head task_wait;
    struct list_head task_prctl;
    struct list_head task_to_inode;
    struct list_head ipc_permission;
    struct list_head ipc_getsecid;
    struct list_head msg_msg_alloc_security;
    struct list_head msg_msg_free_security;
    struct list_head msg_queue_alloc_security;
    struct list_head msg_queue_free_security;
    struct list_head msg_queue_associate;
    struct list_head msg_queue_msgctl;
    struct list_head msg_queue_msgsnd;
    struct list_head msg_queue_msgrcv;
    struct list_head shm_alloc_security;
    struct list_head shm_free_security;
    struct list_head shm_associate;
    struct list_head shm_shmctl;
    struct list_head shm_shmat;
    struct list_head sem_alloc_security;
    struct list_head sem_free_security;
    struct list_head sem_associate;
    struct list_head sem_semctl;
    struct list_head sem_semop;
    struct list_head netlink_send;
    struct list_head d_instantiate;
    struct list_head getprocattr;
    struct list_head setprocattr;
    struct list_head ismaclabel;
    struct list_head secid_to_secctx;
    struct list_head secctx_to_secid;
    struct list_head release_secctx;
    struct list_head inode_invalidate_secctx;
    struct list_head inode_notifysecctx;
    struct list_head inode_setsecctx;
    struct list_head inode_getsecctx;
    struct list_head unix_stream_connect;
    struct list_head unix_may_send;
    struct list_head socket_create;
    struct list_head socket_post_create;
    struct list_head socket_bind;
    struct list_head socket_connect;
    struct list_head socket_listen;
    struct list_head socket_accept;
    struct list_head socket_sendmsg;
    struct list_head socket_recvmsg;
    struct list_head socket_getsockname;
    struct list_head socket_getpeername;
    struct list_head socket_getsockopt;
    struct list_head socket_setsockopt;
    struct list_head socket_shutdown;
    struct list_head socket_sock_rcv_skb;
    struct list_head socket_getpeersec_stream;
    struct list_head socket_getpeersec_dgram;
    struct list_head sk_alloc_security;
    struct list_head sk_free_security;
    struct list_head sk_clone_security;
    struct list_head sk_getsecid;
    struct list_head sock_graft;
    struct list_head inet_conn_request;
    struct list_head inet_csk_clone;
    struct list_head inet_conn_established;
    struct list_head secmark_relabel_packet;
    struct list_head secmark_refcount_inc;
    struct list_head secmark_refcount_dec;
    struct list_head req_classify_flow;
    struct list_head tun_dev_alloc_security;
    struct list_head tun_dev_free_security;
    struct list_head tun_dev_create;
    struct list_head tun_dev_attach_queue;
    struct list_head tun_dev_attach;
    struct list_head tun_dev_open;
    struct list_head xfrm_policy_alloc_security;
    struct list_head xfrm_policy_clone_security;
    struct list_head xfrm_policy_free_security;
    struct list_head xfrm_policy_delete_security;
    struct list_head xfrm_state_alloc;
    struct list_head xfrm_state_alloc_acquire;
    struct list_head xfrm_state_free_security;
    struct list_head xfrm_state_delete_security;
    struct list_head xfrm_policy_lookup;
    struct list_head xfrm_state_pol_flow_match;
    struct list_head xfrm_decode_session;
    struct list_head key_alloc;
    struct list_head key_free;
    struct list_head key_permission;
    struct list_head key_getsecurity;
    struct list_head audit_rule_init;
    struct list_head audit_rule_known;
    struct list_head audit_rule_match;
    struct list_head audit_rule_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct list_head binder_set_context_mgr;
    struct list_head binder_transaction;
    struct list_head binder_transfer_binder;
    struct list_head binder_transfer_file;
    struct list_head ptrace_access_check;
    struct list_head ptrace_traceme;
    struct list_head capget;
    struct list_head capset;
    struct list_head capable;
    struct list_head quotactl;
    struct list_head quota_on;
    struct list_head syslog;
    struct list_head settime;
    struct list_head vm_enough_memory;
    struct list_head bprm_set_creds;
    struct list_head bprm_check_security;
    struct list_head bprm_secureexec;
    struct list_head bprm_committing_creds;
    struct list_head bprm_committed_creds;
    struct list_head sb_alloc_security;
    struct list_head sb_free_security;
    struct list_head sb_copy_data;
    struct list_head sb_remount;
    struct list_head sb_kern_mount;
    struct list_head sb_show_options;
    struct list_head sb_statfs;
    struct list_head sb_mount;
    struct list_head sb_umount;
    struct list_head sb_pivotroot;
    struct list_head sb_set_mnt_opts;
    struct list_head sb_clone_mnt_opts;
    struct list_head sb_parse_opts_str;
    struct list_head dentry_init_security;
    struct list_head dentry_create_files_as;
    struct list_head path_unlink;
    struct list_head path_mkdir;
    struct list_head path_rmdir;
    struct list_head path_mknod;
    struct list_head path_truncate;
    struct list_head path_symlink;
    struct list_head path_link;
    struct list_head path_rename;
    struct list_head path_chmod;
    struct list_head path_chown;
    struct list_head path_chroot;
    struct list_head inode_alloc_security;
    struct list_head inode_free_security;
    struct list_head inode_init_security;
    struct list_head inode_create;
    struct list_head inode_link;
    struct list_head inode_unlink;
    struct list_head inode_symlink;
    struct list_head inode_mkdir;
    struct list_head inode_rmdir;
    struct list_head inode_mknod;
    struct list_head inode_rename;
    struct list_head inode_readlink;
    struct list_head inode_follow_link;
    struct list_head inode_permission;
    struct list_head inode_setattr;
    struct list_head inode_getattr;
    struct list_head inode_setxattr;
    struct list_head inode_post_setxattr;
    struct list_head inode_getxattr;
    struct list_head inode_listxattr;
    struct list_head inode_removexattr;
    struct list_head inode_need_killpriv;
    struct list_head inode_killpriv;
    struct list_head inode_getsecurity;
    struct list_head inode_setsecurity;
    struct list_head inode_listsecurity;
    struct list_head inode_getsecid;
    struct list_head inode_copy_up;
    struct list_head inode_copy_up_xattr;
    struct list_head file_permission;
    struct list_head file_alloc_security;
    struct list_head file_free_security;
    struct list_head file_ioctl;
    struct list_head mmap_addr;
    struct list_head mmap_file;
    struct list_head file_mprotect;
    struct list_head file_lock;
    struct list_head file_fcntl;
    struct list_head file_set_fowner;
    struct list_head file_send_sigiotask;
    struct list_head file_receive;
    struct list_head file_open;
    struct list_head task_create;
    struct list_head task_free;
    struct list_head cred_alloc_blank;
    struct list_head cred_free;
    struct list_head cred_prepare;
    struct list_head cred_transfer;
    struct list_head kernel_act_as;
    struct list_head kernel_create_files_as;
    struct list_head kernel_read_file;
    struct list_head kernel_post_read_file;
    struct list_head kernel_module_request;
    struct list_head task_fix_setuid;
    struct list_head task_setpgid;
    struct list_head task_getpgid;
    struct list_head task_getsid;
    struct list_head task_getsecid;
    struct list_head task_setnice;
    struct list_head task_setioprio;
    struct list_head task_getioprio;
    struct list_head task_setrlimit;
    struct list_head task_setscheduler;
    struct list_head task_getscheduler;
    struct list_head task_movememory;
    struct list_head task_kill;
    struct list_head task_wait;
    struct list_head task_prctl;
    struct list_head task_to_inode;
    struct list_head ipc_permission;
    struct list_head ipc_getsecid;
    struct list_head msg_msg_alloc_security;
    struct list_head msg_msg_free_security;
    struct list_head msg_queue_alloc_security;
    struct list_head msg_queue_free_security;
    struct list_head msg_queue_associate;
    struct list_head msg_queue_msgctl;
    struct list_head msg_queue_msgsnd;
    struct list_head msg_queue_msgrcv;
    struct list_head shm_alloc_security;
    struct list_head shm_free_security;
    struct list_head shm_associate;
    struct list_head shm_shmctl;
    struct list_head shm_shmat;
    struct list_head sem_alloc_security;
    struct list_head sem_free_security;
    struct list_head sem_associate;
    struct list_head sem_semctl;
    struct list_head sem_semop;
    struct list_head netlink_send;
    struct list_head d_instantiate;
    struct list_head getprocattr;
    struct list_head setprocattr;
    struct list_head ismaclabel;
    struct list_head secid_to_secctx;
    struct list_head secctx_to_secid;
    struct list_head release_secctx;
    struct list_head inode_invalidate_secctx;
    struct list_head inode_notifysecctx;
    struct list_head inode_setsecctx;
    struct list_head inode_getsecctx;
    struct list_head unix_stream_connect;
    struct list_head unix_may_send;
    struct list_head socket_create;
    struct list_head socket_post_create;
    struct list_head socket_bind;
    struct list_head socket_connect;
    struct list_head socket_listen;
    struct list_head socket_accept;
    struct list_head socket_sendmsg;
    struct list_head socket_recvmsg;
    struct list_head socket_getsockname;
    struct list_head socket_getpeername;
    struct list_head socket_getsockopt;
    struct list_head socket_setsockopt;
    struct list_head socket_shutdown;
    struct list_head socket_sock_rcv_skb;
    struct list_head socket_getpeersec_stream;
    struct list_head socket_getpeersec_dgram;
    struct list_head sk_alloc_security;
    struct list_head sk_free_security;
    struct list_head sk_clone_security;
    struct list_head sk_getsecid;
    struct list_head sock_graft;
    struct list_head inet_conn_request;
    struct list_head inet_csk_clone;
    struct list_head inet_conn_established;
    struct list_head secmark_relabel_packet;
    struct list_head secmark_refcount_inc;
    struct list_head secmark_refcount_dec;
    struct list_head req_classify_flow;
    struct list_head tun_dev_alloc_security;
    struct list_head tun_dev_free_security;
    struct list_head tun_dev_create;
    struct list_head tun_dev_attach_queue;
    struct list_head tun_dev_attach;
    struct list_head tun_dev_open;
    struct list_head xfrm_policy_alloc_security;
    struct list_head xfrm_policy_clone_security;
    struct list_head xfrm_policy_free_security;
    struct list_head xfrm_policy_delete_security;
    struct list_head xfrm_state_alloc;
    struct list_head xfrm_state_alloc_acquire;
    struct list_head xfrm_state_free_security;
    struct list_head xfrm_state_delete_security;
    struct list_head xfrm_policy_lookup;
    struct list_head xfrm_state_pol_flow_match;
    struct list_head xfrm_decode_session;
    struct list_head key_alloc;
    struct list_head key_free;
    struct list_head key_permission;
    struct list_head key_getsecurity;
    struct list_head audit_rule_init;
    struct list_head audit_rule_known;
    struct list_head audit_rule_match;
    struct list_head audit_rule_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct list_head binder_set_context_mgr;
    struct list_head binder_transaction;
    struct list_head binder_transfer_binder;
    struct list_head binder_transfer_file;
    struct list_head ptrace_access_check;
    struct list_head ptrace_traceme;
    struct list_head capget;
    struct list_head capset;
    struct list_head capable;
    struct list_head quotactl;
    struct list_head quota_on;
    struct list_head syslog;
    struct list_head settime;
    struct list_head vm_enough_memory;
    struct list_head bprm_set_creds;
    struct list_head bprm_check_security;
    struct list_head bprm_secureexec;
    struct list_head bprm_committing_creds;
    struct list_head bprm_committed_creds;
    struct list_head sb_alloc_security;
    struct list_head sb_free_security;
    struct list_head sb_copy_data;
    struct list_head sb_remount;
    struct list_head sb_kern_mount;
    struct list_head sb_show_options;
    struct list_head sb_statfs;
    struct list_head sb_mount;
    struct list_head sb_umount;
    struct list_head sb_pivotroot;
    struct list_head sb_set_mnt_opts;
    struct list_head sb_clone_mnt_opts;
    struct list_head sb_parse_opts_str;
    struct list_head dentry_init_security;
    struct list_head dentry_create_files_as;
    struct list_head path_unlink;
    struct list_head path_mkdir;
    struct list_head path_rmdir;
    struct list_head path_mknod;
    struct list_head path_truncate;
    struct list_head path_symlink;
    struct list_head path_link;
    struct list_head path_rename;
    struct list_head path_chmod;
    struct list_head path_chown;
    struct list_head path_chroot;
    struct list_head inode_alloc_security;
    struct list_head inode_free_security;
    struct list_head inode_init_security;
    struct list_head inode_create;
    struct list_head inode_link;
    struct list_head inode_unlink;
    struct list_head inode_symlink;
    struct list_head inode_mkdir;
    struct list_head inode_rmdir;
    struct list_head inode_mknod;
    struct list_head inode_rename;
    struct list_head inode_readlink;
    struct list_head inode_follow_link;
    struct list_head inode_permission;
    struct list_head inode_setattr;
    struct list_head inode_getattr;
    struct list_head inode_setxattr;
    struct list_head inode_post_setxattr;
    struct list_head inode_getxattr;
    struct list_head inode_listxattr;
    struct list_head inode_removexattr;
    struct list_head inode_need_killpriv;
    struct list_head inode_killpriv;
    struct list_head inode_getsecurity;
    struct list_head inode_setsecurity;
    struct list_head inode_listsecurity;
    struct list_head inode_getsecid;
    struct list_head inode_copy_up;
    struct list_head inode_copy_up_xattr;
    struct list_head file_permission;
    struct list_head file_alloc_security;
    struct list_head file_free_security;
    struct list_head file_ioctl;
    struct list_head mmap_addr;
    struct list_head mmap_file;
    struct list_head file_mprotect;
    struct list_head file_lock;
    struct list_head file_fcntl;
    struct list_head file_set_fowner;
    struct list_head file_send_sigiotask;
    struct list_head file_receive;
    struct list_head file_open;
    struct list_head task_create;
    struct list_head task_alloc;
    struct list_head task_free;
    struct list_head cred_alloc_blank;
    struct list_head cred_free;
    struct list_head cred_prepare;
    struct list_head cred_transfer;
    struct list_head kernel_act_as;
    struct list_head kernel_create_files_as;
    struct list_head kernel_read_file;
    struct list_head kernel_post_read_file;
    struct list_head kernel_module_request;
    struct list_head task_fix_setuid;
    struct list_head task_setpgid;
    struct list_head task_getpgid;
    struct list_head task_getsid;
    struct list_head task_getsecid;
    struct list_head task_setnice;
    struct list_head task_setioprio;
    struct list_head task_getioprio;
    struct list_head task_prlimit;
    struct list_head task_setrlimit;
    struct list_head task_setscheduler;
    struct list_head task_getscheduler;
    struct list_head task_movememory;
    struct list_head task_kill;
    struct list_head task_prctl;
    struct list_head task_to_inode;
    struct list_head ipc_permission;
    struct list_head ipc_getsecid;
    struct list_head msg_msg_alloc_security;
    struct list_head msg_msg_free_security;
    struct list_head msg_queue_alloc_security;
    struct list_head msg_queue_free_security;
    struct list_head msg_queue_associate;
    struct list_head msg_queue_msgctl;
    struct list_head msg_queue_msgsnd;
    struct list_head msg_queue_msgrcv;
    struct list_head shm_alloc_security;
    struct list_head shm_free_security;
    struct list_head shm_associate;
    struct list_head shm_shmctl;
    struct list_head shm_shmat;
    struct list_head sem_alloc_security;
    struct list_head sem_free_security;
    struct list_head sem_associate;
    struct list_head sem_semctl;
    struct list_head sem_semop;
    struct list_head netlink_send;
    struct list_head d_instantiate;
    struct list_head getprocattr;
    struct list_head setprocattr;
    struct list_head ismaclabel;
    struct list_head secid_to_secctx;
    struct list_head secctx_to_secid;
    struct list_head release_secctx;
    struct list_head inode_invalidate_secctx;
    struct list_head inode_notifysecctx;
    struct list_head inode_setsecctx;
    struct list_head inode_getsecctx;
    struct list_head unix_stream_connect;
    struct list_head unix_may_send;
    struct list_head socket_create;
    struct list_head socket_post_create;
    struct list_head socket_bind;
    struct list_head socket_connect;
    struct list_head socket_listen;
    struct list_head socket_accept;
    struct list_head socket_sendmsg;
    struct list_head socket_recvmsg;
    struct list_head socket_getsockname;
    struct list_head socket_getpeername;
    struct list_head socket_getsockopt;
    struct list_head socket_setsockopt;
    struct list_head socket_shutdown;
    struct list_head socket_sock_rcv_skb;
    struct list_head socket_getpeersec_stream;
    struct list_head socket_getpeersec_dgram;
    struct list_head sk_alloc_security;
    struct list_head sk_free_security;
    struct list_head sk_clone_security;
    struct list_head sk_getsecid;
    struct list_head sock_graft;
    struct list_head inet_conn_request;
    struct list_head inet_csk_clone;
    struct list_head inet_conn_established;
    struct list_head secmark_relabel_packet;
    struct list_head secmark_refcount_inc;
    struct list_head secmark_refcount_dec;
    struct list_head req_classify_flow;
    struct list_head tun_dev_alloc_security;
    struct list_head tun_dev_free_security;
    struct list_head tun_dev_create;
    struct list_head tun_dev_attach_queue;
    struct list_head tun_dev_attach;
    struct list_head tun_dev_open;
    struct list_head ib_pkey_access;
    struct list_head ib_endport_manage_subnet;
    struct list_head ib_alloc_security;
    struct list_head ib_free_security;
    struct list_head xfrm_policy_alloc_security;
    struct list_head xfrm_policy_clone_security;
    struct list_head xfrm_policy_free_security;
    struct list_head xfrm_policy_delete_security;
    struct list_head xfrm_state_alloc;
    struct list_head xfrm_state_alloc_acquire;
    struct list_head xfrm_state_free_security;
    struct list_head xfrm_state_delete_security;
    struct list_head xfrm_policy_lookup;
    struct list_head xfrm_state_pol_flow_match;
    struct list_head xfrm_decode_session;
    struct list_head key_alloc;
    struct list_head key_free;
    struct list_head key_permission;
    struct list_head key_getsecurity;
    struct list_head audit_rule_init;
    struct list_head audit_rule_known;
    struct list_head audit_rule_match;
    struct list_head audit_rule_free;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct list_head binder_set_context_mgr;
    struct list_head binder_transaction;
    struct list_head binder_transfer_binder;
    struct list_head binder_transfer_file;
    struct list_head ptrace_access_check;
    struct list_head ptrace_traceme;
    struct list_head capget;
    struct list_head capset;
    struct list_head capable;
    struct list_head quotactl;
    struct list_head quota_on;
    struct list_head syslog;
    struct list_head settime;
    struct list_head vm_enough_memory;
    struct list_head bprm_set_creds;
    struct list_head bprm_check_security;
    struct list_head bprm_committing_creds;
    struct list_head bprm_committed_creds;
    struct list_head sb_alloc_security;
    struct list_head sb_free_security;
    struct list_head sb_copy_data;
    struct list_head sb_remount;
    struct list_head sb_kern_mount;
    struct list_head sb_show_options;
    struct list_head sb_statfs;
    struct list_head sb_mount;
    struct list_head sb_umount;
    struct list_head sb_pivotroot;
    struct list_head sb_set_mnt_opts;
    struct list_head sb_clone_mnt_opts;
    struct list_head sb_parse_opts_str;
    struct list_head dentry_init_security;
    struct list_head dentry_create_files_as;
    struct list_head path_unlink;
    struct list_head path_mkdir;
    struct list_head path_rmdir;
    struct list_head path_mknod;
    struct list_head path_truncate;
    struct list_head path_symlink;
    struct list_head path_link;
    struct list_head path_rename;
    struct list_head path_chmod;
    struct list_head path_chown;
    struct list_head path_chroot;
    struct list_head inode_alloc_security;
    struct list_head inode_free_security;
    struct list_head inode_init_security;
    struct list_head inode_create;
    struct list_head inode_link;
    struct list_head inode_unlink;
    struct list_head inode_symlink;
    struct list_head inode_mkdir;
    struct list_head inode_rmdir;
    struct list_head inode_mknod;
    struct list_head inode_rename;
    struct list_head inode_readlink;
    struct list_head inode_follow_link;
    struct list_head inode_permission;
    struct list_head inode_setattr;
    struct list_head inode_getattr;
    struct list_head inode_setxattr;
    struct list_head inode_post_setxattr;
    struct list_head inode_getxattr;
    struct list_head inode_listxattr;
    struct list_head inode_removexattr;
    struct list_head inode_need_killpriv;
    struct list_head inode_killpriv;
    struct list_head inode_getsecurity;
    struct list_head inode_setsecurity;
    struct list_head inode_listsecurity;
    struct list_head inode_getsecid;
    struct list_head inode_copy_up;
    struct list_head inode_copy_up_xattr;
    struct list_head file_permission;
    struct list_head file_alloc_security;
    struct list_head file_free_security;
    struct list_head file_ioctl;
    struct list_head mmap_addr;
    struct list_head mmap_file;
    struct list_head file_mprotect;
    struct list_head file_lock;
    struct list_head file_fcntl;
    struct list_head file_set_fowner;
    struct list_head file_send_sigiotask;
    struct list_head file_receive;
    struct list_head file_open;
    struct list_head task_alloc;
    struct list_head task_free;
    struct list_head cred_alloc_blank;
    struct list_head cred_free;
    struct list_head cred_prepare;
    struct list_head cred_transfer;
    struct list_head kernel_act_as;
    struct list_head kernel_create_files_as;
    struct list_head kernel_read_file;
    struct list_head kernel_post_read_file;
    struct list_head kernel_module_request;
    struct list_head task_fix_setuid;
    struct list_head task_setpgid;
    struct list_head task_getpgid;
    struct list_head task_getsid;
    struct list_head task_getsecid;
    struct list_head task_setnice;
    struct list_head task_setioprio;
    struct list_head task_getioprio;
    struct list_head task_prlimit;
    struct list_head task_setrlimit;
    struct list_head task_setscheduler;
    struct list_head task_getscheduler;
    struct list_head task_movememory;
    struct list_head task_kill;
    struct list_head task_prctl;
    struct list_head task_to_inode;
    struct list_head ipc_permission;
    struct list_head ipc_getsecid;
    struct list_head msg_msg_alloc_security;
    struct list_head msg_msg_free_security;
    struct list_head msg_queue_alloc_security;
    struct list_head msg_queue_free_security;
    struct list_head msg_queue_associate;
    struct list_head msg_queue_msgctl;
    struct list_head msg_queue_msgsnd;
    struct list_head msg_queue_msgrcv;
    struct list_head shm_alloc_security;
    struct list_head shm_free_security;
    struct list_head shm_associate;
    struct list_head shm_shmctl;
    struct list_head shm_shmat;
    struct list_head sem_alloc_security;
    struct list_head sem_free_security;
    struct list_head sem_associate;
    struct list_head sem_semctl;
    struct list_head sem_semop;
    struct list_head netlink_send;
    struct list_head d_instantiate;
    struct list_head getprocattr;
    struct list_head setprocattr;
    struct list_head ismaclabel;
    struct list_head secid_to_secctx;
    struct list_head secctx_to_secid;
    struct list_head release_secctx;
    struct list_head inode_invalidate_secctx;
    struct list_head inode_notifysecctx;
    struct list_head inode_setsecctx;
    struct list_head inode_getsecctx;
    struct list_head unix_stream_connect;
    struct list_head unix_may_send;
    struct list_head socket_create;
    struct list_head socket_post_create;
    struct list_head socket_bind;
    struct list_head socket_connect;
    struct list_head socket_listen;
    struct list_head socket_accept;
    struct list_head socket_sendmsg;
    struct list_head socket_recvmsg;
    struct list_head socket_getsockname;
    struct list_head socket_getpeername;
    struct list_head socket_getsockopt;
    struct list_head socket_setsockopt;
    struct list_head socket_shutdown;
    struct list_head socket_sock_rcv_skb;
    struct list_head socket_getpeersec_stream;
    struct list_head socket_getpeersec_dgram;
    struct list_head sk_alloc_security;
    struct list_head sk_free_security;
    struct list_head sk_clone_security;
    struct list_head sk_getsecid;
    struct list_head sock_graft;
    struct list_head inet_conn_request;
    struct list_head inet_csk_clone;
    struct list_head inet_conn_established;
    struct list_head secmark_relabel_packet;
    struct list_head secmark_refcount_inc;
    struct list_head secmark_refcount_dec;
    struct list_head req_classify_flow;
    struct list_head tun_dev_alloc_security;
    struct list_head tun_dev_free_security;
    struct list_head tun_dev_create;
    struct list_head tun_dev_attach_queue;
    struct list_head tun_dev_attach;
    struct list_head tun_dev_open;
    struct list_head ib_pkey_access;
    struct list_head ib_endport_manage_subnet;
    struct list_head ib_alloc_security;
    struct list_head ib_free_security;
    struct list_head xfrm_policy_alloc_security;
    struct list_head xfrm_policy_clone_security;
    struct list_head xfrm_policy_free_security;
    struct list_head xfrm_policy_delete_security;
    struct list_head xfrm_state_alloc;
    struct list_head xfrm_state_alloc_acquire;
    struct list_head xfrm_state_free_security;
    struct list_head xfrm_state_delete_security;
    struct list_head xfrm_policy_lookup;
    struct list_head xfrm_state_pol_flow_match;
    struct list_head xfrm_decode_session;
    struct list_head key_alloc;
    struct list_head key_free;
    struct list_head key_permission;
    struct list_head key_getsecurity;
    struct list_head audit_rule_init;
    struct list_head audit_rule_known;
    struct list_head audit_rule_match;
    struct list_head audit_rule_free;
    struct list_head bpf;
    struct list_head bpf_map;
    struct list_head bpf_prog;
    struct list_head bpf_map_alloc_security;
    struct list_head bpf_map_free_security;
    struct list_head bpf_prog_alloc_security;
    struct list_head bpf_prog_free_security;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_copy_data;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_parse_opts_str;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_creds_for_exec;
    struct hlist_head bprm_creds_from_file;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_module_request;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_fix_setgid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head post_notification;
    struct hlist_head watch_key;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
    struct hlist_head perf_event_open;
    struct hlist_head perf_event_alloc;
    struct hlist_head perf_event_free;
    struct hlist_head perf_event_read;
    struct hlist_head perf_event_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_creds_for_exec;
    struct hlist_head bprm_creds_from_file;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_module_request;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_post_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_fix_setgid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head post_notification;
    struct hlist_head watch_key;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
    struct hlist_head perf_event_open;
    struct hlist_head perf_event_alloc;
    struct hlist_head perf_event_free;
    struct hlist_head perf_event_read;
    struct hlist_head perf_event_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_creds_for_exec;
    struct hlist_head bprm_creds_from_file;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_delete;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_mnt_opts_compat;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_init_security_anon;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_module_request;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_post_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_fix_setgid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid_subj;
    struct hlist_head task_getsecid_obj;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head post_notification;
    struct hlist_head watch_key;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
    struct hlist_head perf_event_open;
    struct hlist_head perf_event_alloc;
    struct hlist_head perf_event_free;
    struct hlist_head perf_event_read;
    struct hlist_head perf_event_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_creds_for_exec;
    struct hlist_head bprm_creds_from_file;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_delete;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_mnt_opts_compat;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_init_security_anon;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_module_request;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_post_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_fix_setgid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid_subj;
    struct hlist_head task_getsecid_obj;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head post_notification;
    struct hlist_head watch_key;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
    struct hlist_head perf_event_open;
    struct hlist_head perf_event_alloc;
    struct hlist_head perf_event_free;
    struct hlist_head perf_event_read;
    struct hlist_head perf_event_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_creds_for_exec;
    struct hlist_head bprm_creds_from_file;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_delete;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_mnt_opts_compat;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_init_security_anon;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_module_request;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_post_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_fix_setgid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head current_getsecid_subj;
    struct hlist_head task_getsecid_obj;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head userns_create;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head post_notification;
    struct hlist_head watch_key;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head sctp_assoc_established;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
    struct hlist_head perf_event_open;
    struct hlist_head perf_event_alloc;
    struct hlist_head perf_event_free;
    struct hlist_head perf_event_read;
    struct hlist_head perf_event_write;
    struct hlist_head uring_override_creds;
    struct hlist_head uring_sqpoll;
    struct hlist_head uring_cmd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_creds_for_exec;
    struct hlist_head bprm_creds_from_file;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_delete;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_mnt_opts_compat;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_init_security_anon;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_set_acl;
    struct hlist_head inode_get_acl;
    struct hlist_head inode_remove_acl;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head file_truncate;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_module_request;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_post_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_fix_setgid;
    struct hlist_head task_fix_setgroups;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head current_getsecid_subj;
    struct hlist_head task_getsecid_obj;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head userns_create;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head post_notification;
    struct hlist_head watch_key;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head sctp_assoc_established;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
    struct hlist_head perf_event_open;
    struct hlist_head perf_event_alloc;
    struct hlist_head perf_event_free;
    struct hlist_head perf_event_read;
    struct hlist_head perf_event_write;
    struct hlist_head uring_override_creds;
    struct hlist_head uring_sqpoll;
    struct hlist_head uring_cmd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_creds_for_exec;
    struct hlist_head bprm_creds_from_file;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_submount;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_delete;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_mnt_opts_compat;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_init_security_anon;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_set_acl;
    struct hlist_head inode_get_acl;
    struct hlist_head inode_remove_acl;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head file_truncate;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_module_request;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_post_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_fix_setgid;
    struct hlist_head task_fix_setgroups;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head current_getsecid_subj;
    struct hlist_head task_getsecid_obj;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head userns_create;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head post_notification;
    struct hlist_head watch_key;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head sctp_assoc_established;
    struct hlist_head mptcp_add_subflow;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
    struct hlist_head perf_event_open;
    struct hlist_head perf_event_alloc;
    struct hlist_head perf_event_free;
    struct hlist_head perf_event_read;
    struct hlist_head perf_event_write;
    struct hlist_head uring_override_creds;
    struct hlist_head uring_sqpoll;
    struct hlist_head uring_cmd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_creds_for_exec;
    struct hlist_head bprm_creds_from_file;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_submount;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_delete;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_mnt_opts_compat;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_init_security_anon;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_set_acl;
    struct hlist_head inode_get_acl;
    struct hlist_head inode_remove_acl;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getlsmblob;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head file_ioctl_compat;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head file_truncate;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head cred_getlsmblob;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_module_request;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_post_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_fix_setgid;
    struct hlist_head task_fix_setgroups;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head current_getlsmblob_subj;
    struct hlist_head task_getlsmblob_obj;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head userns_create;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getlsmblob;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getselfattr;
    struct hlist_head setselfattr;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head lsmblob_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head post_notification;
    struct hlist_head watch_key;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head sctp_assoc_established;
    struct hlist_head mptcp_add_subflow;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
    struct hlist_head perf_event_open;
    struct hlist_head perf_event_alloc;
    struct hlist_head perf_event_free;
    struct hlist_head perf_event_read;
    struct hlist_head perf_event_write;
    struct hlist_head uring_override_creds;
    struct hlist_head uring_sqpoll;
    struct hlist_head uring_cmd;
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
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
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
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct security_hook_heads {
    struct hlist_head binder_set_context_mgr;
    struct hlist_head binder_transaction;
    struct hlist_head binder_transfer_binder;
    struct hlist_head binder_transfer_file;
    struct hlist_head ptrace_access_check;
    struct hlist_head ptrace_traceme;
    struct hlist_head capget;
    struct hlist_head capset;
    struct hlist_head capable;
    struct hlist_head quotactl;
    struct hlist_head quota_on;
    struct hlist_head syslog;
    struct hlist_head settime;
    struct hlist_head vm_enough_memory;
    struct hlist_head bprm_set_creds;
    struct hlist_head bprm_check_security;
    struct hlist_head bprm_committing_creds;
    struct hlist_head bprm_committed_creds;
    struct hlist_head fs_context_dup;
    struct hlist_head fs_context_parse_param;
    struct hlist_head sb_alloc_security;
    struct hlist_head sb_free_security;
    struct hlist_head sb_free_mnt_opts;
    struct hlist_head sb_eat_lsm_opts;
    struct hlist_head sb_remount;
    struct hlist_head sb_kern_mount;
    struct hlist_head sb_show_options;
    struct hlist_head sb_statfs;
    struct hlist_head sb_mount;
    struct hlist_head sb_umount;
    struct hlist_head sb_pivotroot;
    struct hlist_head sb_set_mnt_opts;
    struct hlist_head sb_clone_mnt_opts;
    struct hlist_head sb_add_mnt_opt;
    struct hlist_head move_mount;
    struct hlist_head dentry_init_security;
    struct hlist_head dentry_create_files_as;
    struct hlist_head path_unlink;
    struct hlist_head path_mkdir;
    struct hlist_head path_rmdir;
    struct hlist_head path_mknod;
    struct hlist_head path_truncate;
    struct hlist_head path_symlink;
    struct hlist_head path_link;
    struct hlist_head path_rename;
    struct hlist_head path_chmod;
    struct hlist_head path_chown;
    struct hlist_head path_chroot;
    struct hlist_head path_notify;
    struct hlist_head inode_alloc_security;
    struct hlist_head inode_free_security;
    struct hlist_head inode_init_security;
    struct hlist_head inode_create;
    struct hlist_head inode_link;
    struct hlist_head inode_unlink;
    struct hlist_head inode_symlink;
    struct hlist_head inode_mkdir;
    struct hlist_head inode_rmdir;
    struct hlist_head inode_mknod;
    struct hlist_head inode_rename;
    struct hlist_head inode_readlink;
    struct hlist_head inode_follow_link;
    struct hlist_head inode_permission;
    struct hlist_head inode_setattr;
    struct hlist_head inode_getattr;
    struct hlist_head inode_setxattr;
    struct hlist_head inode_post_setxattr;
    struct hlist_head inode_getxattr;
    struct hlist_head inode_listxattr;
    struct hlist_head inode_removexattr;
    struct hlist_head inode_need_killpriv;
    struct hlist_head inode_killpriv;
    struct hlist_head inode_getsecurity;
    struct hlist_head inode_setsecurity;
    struct hlist_head inode_listsecurity;
    struct hlist_head inode_getsecid;
    struct hlist_head inode_copy_up;
    struct hlist_head inode_copy_up_xattr;
    struct hlist_head kernfs_init_security;
    struct hlist_head file_permission;
    struct hlist_head file_alloc_security;
    struct hlist_head file_free_security;
    struct hlist_head file_ioctl;
    struct hlist_head mmap_addr;
    struct hlist_head mmap_file;
    struct hlist_head file_mprotect;
    struct hlist_head file_lock;
    struct hlist_head file_fcntl;
    struct hlist_head file_set_fowner;
    struct hlist_head file_send_sigiotask;
    struct hlist_head file_receive;
    struct hlist_head file_open;
    struct hlist_head task_alloc;
    struct hlist_head task_free;
    struct hlist_head cred_alloc_blank;
    struct hlist_head cred_free;
    struct hlist_head cred_prepare;
    struct hlist_head cred_transfer;
    struct hlist_head cred_getsecid;
    struct hlist_head kernel_act_as;
    struct hlist_head kernel_create_files_as;
    struct hlist_head kernel_load_data;
    struct hlist_head kernel_read_file;
    struct hlist_head kernel_post_read_file;
    struct hlist_head kernel_module_request;
    struct hlist_head task_fix_setuid;
    struct hlist_head task_setpgid;
    struct hlist_head task_getpgid;
    struct hlist_head task_getsid;
    struct hlist_head task_getsecid;
    struct hlist_head task_setnice;
    struct hlist_head task_setioprio;
    struct hlist_head task_getioprio;
    struct hlist_head task_prlimit;
    struct hlist_head task_setrlimit;
    struct hlist_head task_setscheduler;
    struct hlist_head task_getscheduler;
    struct hlist_head task_movememory;
    struct hlist_head task_kill;
    struct hlist_head task_prctl;
    struct hlist_head task_to_inode;
    struct hlist_head ipc_permission;
    struct hlist_head ipc_getsecid;
    struct hlist_head msg_msg_alloc_security;
    struct hlist_head msg_msg_free_security;
    struct hlist_head msg_queue_alloc_security;
    struct hlist_head msg_queue_free_security;
    struct hlist_head msg_queue_associate;
    struct hlist_head msg_queue_msgctl;
    struct hlist_head msg_queue_msgsnd;
    struct hlist_head msg_queue_msgrcv;
    struct hlist_head shm_alloc_security;
    struct hlist_head shm_free_security;
    struct hlist_head shm_associate;
    struct hlist_head shm_shmctl;
    struct hlist_head shm_shmat;
    struct hlist_head sem_alloc_security;
    struct hlist_head sem_free_security;
    struct hlist_head sem_associate;
    struct hlist_head sem_semctl;
    struct hlist_head sem_semop;
    struct hlist_head netlink_send;
    struct hlist_head d_instantiate;
    struct hlist_head getprocattr;
    struct hlist_head setprocattr;
    struct hlist_head ismaclabel;
    struct hlist_head secid_to_secctx;
    struct hlist_head secctx_to_secid;
    struct hlist_head release_secctx;
    struct hlist_head inode_invalidate_secctx;
    struct hlist_head inode_notifysecctx;
    struct hlist_head inode_setsecctx;
    struct hlist_head inode_getsecctx;
    struct hlist_head unix_stream_connect;
    struct hlist_head unix_may_send;
    struct hlist_head socket_create;
    struct hlist_head socket_post_create;
    struct hlist_head socket_socketpair;
    struct hlist_head socket_bind;
    struct hlist_head socket_connect;
    struct hlist_head socket_listen;
    struct hlist_head socket_accept;
    struct hlist_head socket_sendmsg;
    struct hlist_head socket_recvmsg;
    struct hlist_head socket_getsockname;
    struct hlist_head socket_getpeername;
    struct hlist_head socket_getsockopt;
    struct hlist_head socket_setsockopt;
    struct hlist_head socket_shutdown;
    struct hlist_head socket_sock_rcv_skb;
    struct hlist_head socket_getpeersec_stream;
    struct hlist_head socket_getpeersec_dgram;
    struct hlist_head sk_alloc_security;
    struct hlist_head sk_free_security;
    struct hlist_head sk_clone_security;
    struct hlist_head sk_getsecid;
    struct hlist_head sock_graft;
    struct hlist_head inet_conn_request;
    struct hlist_head inet_csk_clone;
    struct hlist_head inet_conn_established;
    struct hlist_head secmark_relabel_packet;
    struct hlist_head secmark_refcount_inc;
    struct hlist_head secmark_refcount_dec;
    struct hlist_head req_classify_flow;
    struct hlist_head tun_dev_alloc_security;
    struct hlist_head tun_dev_free_security;
    struct hlist_head tun_dev_create;
    struct hlist_head tun_dev_attach_queue;
    struct hlist_head tun_dev_attach;
    struct hlist_head tun_dev_open;
    struct hlist_head sctp_assoc_request;
    struct hlist_head sctp_bind_connect;
    struct hlist_head sctp_sk_clone;
    struct hlist_head ib_pkey_access;
    struct hlist_head ib_endport_manage_subnet;
    struct hlist_head ib_alloc_security;
    struct hlist_head ib_free_security;
    struct hlist_head xfrm_policy_alloc_security;
    struct hlist_head xfrm_policy_clone_security;
    struct hlist_head xfrm_policy_free_security;
    struct hlist_head xfrm_policy_delete_security;
    struct hlist_head xfrm_state_alloc;
    struct hlist_head xfrm_state_alloc_acquire;
    struct hlist_head xfrm_state_free_security;
    struct hlist_head xfrm_state_delete_security;
    struct hlist_head xfrm_policy_lookup;
    struct hlist_head xfrm_state_pol_flow_match;
    struct hlist_head xfrm_decode_session;
    struct hlist_head key_alloc;
    struct hlist_head key_free;
    struct hlist_head key_permission;
    struct hlist_head key_getsecurity;
    struct hlist_head audit_rule_init;
    struct hlist_head audit_rule_known;
    struct hlist_head audit_rule_match;
    struct hlist_head audit_rule_free;
    struct hlist_head bpf;
    struct hlist_head bpf_map;
    struct hlist_head bpf_prog;
    struct hlist_head bpf_map_alloc_security;
    struct hlist_head bpf_map_free_security;
    struct hlist_head bpf_prog_alloc_security;
    struct hlist_head bpf_prog_free_security;
    struct hlist_head locked_down;
    struct hlist_head lock_kernel_down;
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
<code>struct list_head kernel_read_file</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head kernel_post_read_file</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head inode_invalidate_secctx</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head kernel_fw_from_file</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head kernel_module_from_file</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head skb_owned_by</code>
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
<code>struct list_head dentry_create_files_as</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head inode_copy_up</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head inode_copy_up_xattr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head task_alloc</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head task_prlimit</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head ib_pkey_access</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head ib_endport_manage_subnet</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head ib_alloc_security</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head ib_free_security</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head task_wait</code>
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
<code>struct list_head bpf</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head bpf_map</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head bpf_prog</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head bpf_map_alloc_security</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head bpf_map_free_security</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head bpf_prog_alloc_security</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head bpf_prog_free_security</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head bprm_secureexec</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head task_create</code>
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
<code>struct hlist_head cred_getsecid</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head socket_socketpair</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head sctp_assoc_request</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head sctp_bind_connect</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head sctp_sk_clone</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head binder_set_context_mgr</code> ➡️ <code>struct hlist_head binder_set_context_mgr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head binder_transaction</code> ➡️ <code>struct hlist_head binder_transaction</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head binder_transfer_binder</code> ➡️ <code>struct hlist_head binder_transfer_binder</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head binder_transfer_file</code> ➡️ <code>struct hlist_head binder_transfer_file</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head ptrace_access_check</code> ➡️ <code>struct hlist_head ptrace_access_check</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head ptrace_traceme</code> ➡️ <code>struct hlist_head ptrace_traceme</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head capget</code> ➡️ <code>struct hlist_head capget</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head capset</code> ➡️ <code>struct hlist_head capset</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head capable</code> ➡️ <code>struct hlist_head capable</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head quotactl</code> ➡️ <code>struct hlist_head quotactl</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head quota_on</code> ➡️ <code>struct hlist_head quota_on</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head syslog</code> ➡️ <code>struct hlist_head syslog</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head settime</code> ➡️ <code>struct hlist_head settime</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head vm_enough_memory</code> ➡️ <code>struct hlist_head vm_enough_memory</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bprm_set_creds</code> ➡️ <code>struct hlist_head bprm_set_creds</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bprm_check_security</code> ➡️ <code>struct hlist_head bprm_check_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bprm_committing_creds</code> ➡️ <code>struct hlist_head bprm_committing_creds</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bprm_committed_creds</code> ➡️ <code>struct hlist_head bprm_committed_creds</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_alloc_security</code> ➡️ <code>struct hlist_head sb_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_free_security</code> ➡️ <code>struct hlist_head sb_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_copy_data</code> ➡️ <code>struct hlist_head sb_copy_data</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_remount</code> ➡️ <code>struct hlist_head sb_remount</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_kern_mount</code> ➡️ <code>struct hlist_head sb_kern_mount</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_show_options</code> ➡️ <code>struct hlist_head sb_show_options</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_statfs</code> ➡️ <code>struct hlist_head sb_statfs</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_mount</code> ➡️ <code>struct hlist_head sb_mount</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_umount</code> ➡️ <code>struct hlist_head sb_umount</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_pivotroot</code> ➡️ <code>struct hlist_head sb_pivotroot</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_set_mnt_opts</code> ➡️ <code>struct hlist_head sb_set_mnt_opts</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_clone_mnt_opts</code> ➡️ <code>struct hlist_head sb_clone_mnt_opts</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sb_parse_opts_str</code> ➡️ <code>struct hlist_head sb_parse_opts_str</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head dentry_init_security</code> ➡️ <code>struct hlist_head dentry_init_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head dentry_create_files_as</code> ➡️ <code>struct hlist_head dentry_create_files_as</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_unlink</code> ➡️ <code>struct hlist_head path_unlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_mkdir</code> ➡️ <code>struct hlist_head path_mkdir</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_rmdir</code> ➡️ <code>struct hlist_head path_rmdir</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_mknod</code> ➡️ <code>struct hlist_head path_mknod</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_truncate</code> ➡️ <code>struct hlist_head path_truncate</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_symlink</code> ➡️ <code>struct hlist_head path_symlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_link</code> ➡️ <code>struct hlist_head path_link</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_rename</code> ➡️ <code>struct hlist_head path_rename</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_chmod</code> ➡️ <code>struct hlist_head path_chmod</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_chown</code> ➡️ <code>struct hlist_head path_chown</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head path_chroot</code> ➡️ <code>struct hlist_head path_chroot</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_alloc_security</code> ➡️ <code>struct hlist_head inode_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_free_security</code> ➡️ <code>struct hlist_head inode_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_init_security</code> ➡️ <code>struct hlist_head inode_init_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_create</code> ➡️ <code>struct hlist_head inode_create</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_link</code> ➡️ <code>struct hlist_head inode_link</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_unlink</code> ➡️ <code>struct hlist_head inode_unlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_symlink</code> ➡️ <code>struct hlist_head inode_symlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_mkdir</code> ➡️ <code>struct hlist_head inode_mkdir</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_rmdir</code> ➡️ <code>struct hlist_head inode_rmdir</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_mknod</code> ➡️ <code>struct hlist_head inode_mknod</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_rename</code> ➡️ <code>struct hlist_head inode_rename</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_readlink</code> ➡️ <code>struct hlist_head inode_readlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_follow_link</code> ➡️ <code>struct hlist_head inode_follow_link</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_permission</code> ➡️ <code>struct hlist_head inode_permission</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_setattr</code> ➡️ <code>struct hlist_head inode_setattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_getattr</code> ➡️ <code>struct hlist_head inode_getattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_setxattr</code> ➡️ <code>struct hlist_head inode_setxattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_post_setxattr</code> ➡️ <code>struct hlist_head inode_post_setxattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_getxattr</code> ➡️ <code>struct hlist_head inode_getxattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_listxattr</code> ➡️ <code>struct hlist_head inode_listxattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_removexattr</code> ➡️ <code>struct hlist_head inode_removexattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_need_killpriv</code> ➡️ <code>struct hlist_head inode_need_killpriv</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_killpriv</code> ➡️ <code>struct hlist_head inode_killpriv</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_getsecurity</code> ➡️ <code>struct hlist_head inode_getsecurity</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_setsecurity</code> ➡️ <code>struct hlist_head inode_setsecurity</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_listsecurity</code> ➡️ <code>struct hlist_head inode_listsecurity</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_getsecid</code> ➡️ <code>struct hlist_head inode_getsecid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_copy_up</code> ➡️ <code>struct hlist_head inode_copy_up</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_copy_up_xattr</code> ➡️ <code>struct hlist_head inode_copy_up_xattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_permission</code> ➡️ <code>struct hlist_head file_permission</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_alloc_security</code> ➡️ <code>struct hlist_head file_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_free_security</code> ➡️ <code>struct hlist_head file_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_ioctl</code> ➡️ <code>struct hlist_head file_ioctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head mmap_addr</code> ➡️ <code>struct hlist_head mmap_addr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head mmap_file</code> ➡️ <code>struct hlist_head mmap_file</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_mprotect</code> ➡️ <code>struct hlist_head file_mprotect</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_lock</code> ➡️ <code>struct hlist_head file_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_fcntl</code> ➡️ <code>struct hlist_head file_fcntl</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_set_fowner</code> ➡️ <code>struct hlist_head file_set_fowner</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_send_sigiotask</code> ➡️ <code>struct hlist_head file_send_sigiotask</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_receive</code> ➡️ <code>struct hlist_head file_receive</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head file_open</code> ➡️ <code>struct hlist_head file_open</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_alloc</code> ➡️ <code>struct hlist_head task_alloc</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_free</code> ➡️ <code>struct hlist_head task_free</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head cred_alloc_blank</code> ➡️ <code>struct hlist_head cred_alloc_blank</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head cred_free</code> ➡️ <code>struct hlist_head cred_free</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head cred_prepare</code> ➡️ <code>struct hlist_head cred_prepare</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head cred_transfer</code> ➡️ <code>struct hlist_head cred_transfer</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head kernel_act_as</code> ➡️ <code>struct hlist_head kernel_act_as</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head kernel_create_files_as</code> ➡️ <code>struct hlist_head kernel_create_files_as</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head kernel_read_file</code> ➡️ <code>struct hlist_head kernel_read_file</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head kernel_post_read_file</code> ➡️ <code>struct hlist_head kernel_post_read_file</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head kernel_module_request</code> ➡️ <code>struct hlist_head kernel_module_request</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_fix_setuid</code> ➡️ <code>struct hlist_head task_fix_setuid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_setpgid</code> ➡️ <code>struct hlist_head task_setpgid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_getpgid</code> ➡️ <code>struct hlist_head task_getpgid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_getsid</code> ➡️ <code>struct hlist_head task_getsid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_getsecid</code> ➡️ <code>struct hlist_head task_getsecid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_setnice</code> ➡️ <code>struct hlist_head task_setnice</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_setioprio</code> ➡️ <code>struct hlist_head task_setioprio</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_getioprio</code> ➡️ <code>struct hlist_head task_getioprio</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_prlimit</code> ➡️ <code>struct hlist_head task_prlimit</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_setrlimit</code> ➡️ <code>struct hlist_head task_setrlimit</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_setscheduler</code> ➡️ <code>struct hlist_head task_setscheduler</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_getscheduler</code> ➡️ <code>struct hlist_head task_getscheduler</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_movememory</code> ➡️ <code>struct hlist_head task_movememory</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_kill</code> ➡️ <code>struct hlist_head task_kill</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_prctl</code> ➡️ <code>struct hlist_head task_prctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head task_to_inode</code> ➡️ <code>struct hlist_head task_to_inode</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head ipc_permission</code> ➡️ <code>struct hlist_head ipc_permission</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head ipc_getsecid</code> ➡️ <code>struct hlist_head ipc_getsecid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head msg_msg_alloc_security</code> ➡️ <code>struct hlist_head msg_msg_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head msg_msg_free_security</code> ➡️ <code>struct hlist_head msg_msg_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head msg_queue_alloc_security</code> ➡️ <code>struct hlist_head msg_queue_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head msg_queue_free_security</code> ➡️ <code>struct hlist_head msg_queue_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head msg_queue_associate</code> ➡️ <code>struct hlist_head msg_queue_associate</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head msg_queue_msgctl</code> ➡️ <code>struct hlist_head msg_queue_msgctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head msg_queue_msgsnd</code> ➡️ <code>struct hlist_head msg_queue_msgsnd</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head msg_queue_msgrcv</code> ➡️ <code>struct hlist_head msg_queue_msgrcv</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head shm_alloc_security</code> ➡️ <code>struct hlist_head shm_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head shm_free_security</code> ➡️ <code>struct hlist_head shm_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head shm_associate</code> ➡️ <code>struct hlist_head shm_associate</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head shm_shmctl</code> ➡️ <code>struct hlist_head shm_shmctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head shm_shmat</code> ➡️ <code>struct hlist_head shm_shmat</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sem_alloc_security</code> ➡️ <code>struct hlist_head sem_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sem_free_security</code> ➡️ <code>struct hlist_head sem_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sem_associate</code> ➡️ <code>struct hlist_head sem_associate</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sem_semctl</code> ➡️ <code>struct hlist_head sem_semctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sem_semop</code> ➡️ <code>struct hlist_head sem_semop</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head netlink_send</code> ➡️ <code>struct hlist_head netlink_send</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head d_instantiate</code> ➡️ <code>struct hlist_head d_instantiate</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head getprocattr</code> ➡️ <code>struct hlist_head getprocattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head setprocattr</code> ➡️ <code>struct hlist_head setprocattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head ismaclabel</code> ➡️ <code>struct hlist_head ismaclabel</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head secid_to_secctx</code> ➡️ <code>struct hlist_head secid_to_secctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head secctx_to_secid</code> ➡️ <code>struct hlist_head secctx_to_secid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head release_secctx</code> ➡️ <code>struct hlist_head release_secctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_invalidate_secctx</code> ➡️ <code>struct hlist_head inode_invalidate_secctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_notifysecctx</code> ➡️ <code>struct hlist_head inode_notifysecctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_setsecctx</code> ➡️ <code>struct hlist_head inode_setsecctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inode_getsecctx</code> ➡️ <code>struct hlist_head inode_getsecctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head unix_stream_connect</code> ➡️ <code>struct hlist_head unix_stream_connect</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head unix_may_send</code> ➡️ <code>struct hlist_head unix_may_send</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_create</code> ➡️ <code>struct hlist_head socket_create</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_post_create</code> ➡️ <code>struct hlist_head socket_post_create</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_bind</code> ➡️ <code>struct hlist_head socket_bind</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_connect</code> ➡️ <code>struct hlist_head socket_connect</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_listen</code> ➡️ <code>struct hlist_head socket_listen</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_accept</code> ➡️ <code>struct hlist_head socket_accept</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_sendmsg</code> ➡️ <code>struct hlist_head socket_sendmsg</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_recvmsg</code> ➡️ <code>struct hlist_head socket_recvmsg</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_getsockname</code> ➡️ <code>struct hlist_head socket_getsockname</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_getpeername</code> ➡️ <code>struct hlist_head socket_getpeername</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_getsockopt</code> ➡️ <code>struct hlist_head socket_getsockopt</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_setsockopt</code> ➡️ <code>struct hlist_head socket_setsockopt</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_shutdown</code> ➡️ <code>struct hlist_head socket_shutdown</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_sock_rcv_skb</code> ➡️ <code>struct hlist_head socket_sock_rcv_skb</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_getpeersec_stream</code> ➡️ <code>struct hlist_head socket_getpeersec_stream</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head socket_getpeersec_dgram</code> ➡️ <code>struct hlist_head socket_getpeersec_dgram</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sk_alloc_security</code> ➡️ <code>struct hlist_head sk_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sk_free_security</code> ➡️ <code>struct hlist_head sk_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sk_clone_security</code> ➡️ <code>struct hlist_head sk_clone_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sk_getsecid</code> ➡️ <code>struct hlist_head sk_getsecid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sock_graft</code> ➡️ <code>struct hlist_head sock_graft</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inet_conn_request</code> ➡️ <code>struct hlist_head inet_conn_request</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inet_csk_clone</code> ➡️ <code>struct hlist_head inet_csk_clone</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head inet_conn_established</code> ➡️ <code>struct hlist_head inet_conn_established</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head secmark_relabel_packet</code> ➡️ <code>struct hlist_head secmark_relabel_packet</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head secmark_refcount_inc</code> ➡️ <code>struct hlist_head secmark_refcount_inc</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head secmark_refcount_dec</code> ➡️ <code>struct hlist_head secmark_refcount_dec</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head req_classify_flow</code> ➡️ <code>struct hlist_head req_classify_flow</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head tun_dev_alloc_security</code> ➡️ <code>struct hlist_head tun_dev_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head tun_dev_free_security</code> ➡️ <code>struct hlist_head tun_dev_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head tun_dev_create</code> ➡️ <code>struct hlist_head tun_dev_create</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head tun_dev_attach_queue</code> ➡️ <code>struct hlist_head tun_dev_attach_queue</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head tun_dev_attach</code> ➡️ <code>struct hlist_head tun_dev_attach</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head tun_dev_open</code> ➡️ <code>struct hlist_head tun_dev_open</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head ib_pkey_access</code> ➡️ <code>struct hlist_head ib_pkey_access</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head ib_endport_manage_subnet</code> ➡️ <code>struct hlist_head ib_endport_manage_subnet</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head ib_alloc_security</code> ➡️ <code>struct hlist_head ib_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head ib_free_security</code> ➡️ <code>struct hlist_head ib_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_policy_alloc_security</code> ➡️ <code>struct hlist_head xfrm_policy_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_policy_clone_security</code> ➡️ <code>struct hlist_head xfrm_policy_clone_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_policy_free_security</code> ➡️ <code>struct hlist_head xfrm_policy_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_policy_delete_security</code> ➡️ <code>struct hlist_head xfrm_policy_delete_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_state_alloc</code> ➡️ <code>struct hlist_head xfrm_state_alloc</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_state_alloc_acquire</code> ➡️ <code>struct hlist_head xfrm_state_alloc_acquire</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_state_free_security</code> ➡️ <code>struct hlist_head xfrm_state_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_state_delete_security</code> ➡️ <code>struct hlist_head xfrm_state_delete_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_policy_lookup</code> ➡️ <code>struct hlist_head xfrm_policy_lookup</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_state_pol_flow_match</code> ➡️ <code>struct hlist_head xfrm_state_pol_flow_match</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head xfrm_decode_session</code> ➡️ <code>struct hlist_head xfrm_decode_session</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head key_alloc</code> ➡️ <code>struct hlist_head key_alloc</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head key_free</code> ➡️ <code>struct hlist_head key_free</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head key_permission</code> ➡️ <code>struct hlist_head key_permission</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head key_getsecurity</code> ➡️ <code>struct hlist_head key_getsecurity</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head audit_rule_init</code> ➡️ <code>struct hlist_head audit_rule_init</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head audit_rule_known</code> ➡️ <code>struct hlist_head audit_rule_known</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head audit_rule_match</code> ➡️ <code>struct hlist_head audit_rule_match</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head audit_rule_free</code> ➡️ <code>struct hlist_head audit_rule_free</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bpf</code> ➡️ <code>struct hlist_head bpf</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bpf_map</code> ➡️ <code>struct hlist_head bpf_map</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bpf_prog</code> ➡️ <code>struct hlist_head bpf_prog</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bpf_map_alloc_security</code> ➡️ <code>struct hlist_head bpf_map_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bpf_map_free_security</code> ➡️ <code>struct hlist_head bpf_map_free_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bpf_prog_alloc_security</code> ➡️ <code>struct hlist_head bpf_prog_alloc_security</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head bpf_prog_free_security</code> ➡️ <code>struct hlist_head bpf_prog_free_security</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_head sb_free_mnt_opts</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head sb_eat_lsm_opts</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head sb_add_mnt_opt</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head kernel_load_data</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head sb_copy_data</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head sb_parse_opts_str</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_head fs_context_dup</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head fs_context_parse_param</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head move_mount</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head kernfs_init_security</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_head path_notify</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head locked_down</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head lock_kernel_down</code>
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
<code>struct hlist_head bprm_creds_for_exec</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head bprm_creds_from_file</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head task_fix_setgid</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head post_notification</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head watch_key</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head perf_event_open</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head perf_event_alloc</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head perf_event_free</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head perf_event_read</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head perf_event_write</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head bprm_set_creds</code>
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
<code>struct hlist_head kernel_post_load_data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_head sb_delete</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head sb_mnt_opts_compat</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head inode_init_security_anon</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head task_getsecid_subj</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head task_getsecid_obj</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head task_getsecid</code>
</li>
</ul>
</details>
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
<code>struct hlist_head current_getsecid_subj</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head userns_create</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head sctp_assoc_established</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head uring_override_creds</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head uring_sqpoll</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head uring_cmd</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head sb_add_mnt_opt</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head task_getsecid_subj</code>
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
<code>struct hlist_head inode_set_acl</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head inode_get_acl</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head inode_remove_acl</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head file_truncate</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head task_fix_setgroups</code>
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
<code>struct hlist_head fs_context_submount</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head mptcp_add_subflow</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_head inode_getlsmblob</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head file_ioctl_compat</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head cred_getlsmblob</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head current_getlsmblob_subj</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head task_getlsmblob_obj</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head ipc_getlsmblob</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head getselfattr</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head setselfattr</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_head lsmblob_to_secctx</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head inode_getsecid</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head current_getsecid_subj</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head task_getsecid_obj</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head ipc_getsecid</code>
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
