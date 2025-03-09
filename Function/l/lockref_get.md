# Function: <code>lockref_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583005536,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:40",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_mknod",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_symlink",
        "fs/super.c:mount_ns",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_single",
        "fs/namei.c:path_get",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/dcache.c:d_find_any_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_instantiate_unique",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__d_obtain_alias",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:mnt_set_mountpoint",
        "fs/libfs.c:mount_pseudo",
        "fs/libfs.c:simple_link",
        "fs/proc/root.c:proc_mount",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create",
        "security/inode.c:securityfs_create_file",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005536,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583295984,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:40",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_find_any_alias",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:mnt_set_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create",
        "security/inode.c:__securityfs_setup_d_inode",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295984,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583414848,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:40",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_find_any_alias",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:mnt_set_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create",
        "security/inode.c:__securityfs_setup_d_inode",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414848,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583436592,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:40",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_find_any_alias",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:mnt_set_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/inode.c:configfs_create",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aafs_setup_d_inode",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583436592,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583616512,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:41",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_find_any_alias",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:mnt_set_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/inode.c:configfs_create",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583616512,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583832976,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:41",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:mnt_set_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/inode.c:configfs_create",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583832976,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583916672,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:41",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_ns",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:mnt_set_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:mount_pseudo_xattr",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/inode.c:configfs_create",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916672,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584096480,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/inode.c:configfs_create",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584096480,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584219120,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219120,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584625056,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mklink",
        "kernel/bpf/inode.c:bpf_mkmap",
        "kernel/bpf/inode.c:bpf_mkprog",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/super.c:get_tree_nodev",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:atomic_open",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:follow_dotdot",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_alias",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_recursive_removal",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_mk_null_file",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584625056,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743456,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/super.c:get_tree_nodev",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:atomic_open",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:follow_dotdot",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_alias",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_recursive_removal",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_mk_null_file",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743456,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584771600,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/super.c:get_tree_nodev",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_alias",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_recursive_removal",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/dir.c:fuse_dentry_automount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584771600,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585201488,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/super.c:get_tree_nodev",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_alias",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_recursive_removal",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201488,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586037792,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:43",
      "file": "lib/lockref.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:handle_dots",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_alias",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_recursive_removal",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_create",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/landlock/fs.c:collect_domain_accesses",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037792,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587019920,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:42",
      "file": "lib/lockref.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:handle_dots",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_alias",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_recursive_removal",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/landlock/fs.c:collect_domain_accesses",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587019920,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587274832,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:42",
      "file": "lib/lockref.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:handle_dots",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_alias",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_recursive_removal",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/landlock/fs.c:collect_domain_accesses",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587274832,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587563696,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:42",
      "file": "lib/lockref.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_symlink",
        "kernel/bpf/inode.c:bpf_mkobj_ops",
        "kernel/bpf/inode.c:bpf_mkdir",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_keyed",
        "fs/super.c:get_tree_single",
        "fs/super.c:get_tree_nodev",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:path_init",
        "fs/namei.c:handle_dots",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namei.c:follow_up",
        "fs/namei.c:nd_jump_root",
        "fs/namei.c:set_root",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:__d_obtain_alias",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_alias",
        "fs/namespace.c:__do_sys_fsmount",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/libfs.c:simple_recursive_removal",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_one",
        "fs/fuse/inode.c:fuse_get_tree",
        "fs/fuse/inode.c:fuse_get_tree_submount",
        "fs/efivarfs/inode.c:efivarfs_create",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/landlock/fs.c:collect_domain_accesses",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind_bsd",
        "net/unix/af_unix.c:unix_bind_bsd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587563696,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496092032,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:__arm64_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496092032,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229418312,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:detach_groups",
        "fs/configfs/dir.c:detach_attrs",
        "fs/configfs/dir.c:configfs_detach_prep",
        "fs/configfs/dir.c:configfs_remove_dir",
        "fs/configfs/dir.c:configfs_remove_dir",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "drivers/mtd/mtdsuper.c:mtd_get_sb",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229418312,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290335248,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_detach_prep",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "fs/exportfs/expfs.c:reconnect_path",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290335248,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275161620,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:__se_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_detach_prep",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275161620,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584187856,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584187856,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584123088,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123088,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584171616,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171616,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void lockref_get(struct lockref * lockref)
```

```json
{
  "name": "lockref_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584275776,
      "name": "lockref_get",
      "external": true,
      "loc": "lib/lockref.c:44",
      "file": "lib/lockref.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_dentry_finalize",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_link",
        "mm/shmem.c:shmem_mknod",
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:vfs_get_super",
        "fs/super.c:vfs_get_super",
        "fs/namei.c:vfs_rename",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namei.c:follow_up",
        "fs/namei.c:path_get",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:d_alloc_cursor",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:d_find_any_alias",
        "fs/namespace.c:__ia32_sys_fsmount",
        "fs/namespace.c:__x64_sys_fsmount",
        "fs/namespace.c:lock_mount",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:get_mountpoint",
        "fs/libfs.c:simple_link",
        "fs/fs_context.c:alloc_fs_context",
        "fs/kernfs/mount.c:kernfs_get_tree",
        "fs/kernfs/mount.c:kernfs_node_dentry",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir",
        "fs/ramfs/inode.c:ramfs_symlink",
        "fs/ramfs/inode.c:ramfs_mknod",
        "fs/hugetlbfs/inode.c:hugetlbfs_symlink",
        "fs/hugetlbfs/inode.c:hugetlbfs_mknod",
        "fs/ecryptfs/inode.c:ecryptfs_rename",
        "fs/ecryptfs/inode.c:ecryptfs_rmdir",
        "fs/ecryptfs/inode.c:ecryptfs_symlink",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_link",
        "fs/ecryptfs/inode.c:ecryptfs_do_unlink",
        "fs/ecryptfs/main.c:ecryptfs_mount",
        "ipc/mqueue.c:mqueue_create_attr",
        "security/inode.c:securityfs_create_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "drivers/base/devtmpfs.c:public_dev_mount",
        "net/unix/af_unix.c:unix_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275776,
      "name": "lockref_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
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
