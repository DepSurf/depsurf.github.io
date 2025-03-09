# Struct: <code>inode_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, void * *) follow_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    void (*)(struct inode *, void *) put_link;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *) rename;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename2;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(struct vfsmount *, struct dentry *, struct kstat *) getattr;
    int (*)(struct dentry *, const char *, const void *, size_t, int) setxattr;
    ssize_t (*)(struct dentry *, const char *, void *, size_t) getxattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct dentry *, const char *) removexattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t, int *) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *) rename;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename2;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(struct vfsmount *, struct dentry *, struct kstat *) getattr;
    int (*)(struct dentry *, struct inode *, const char *, const void *, size_t, int) setxattr;
    ssize_t (*)(struct dentry *, struct inode *, const char *, void *, size_t) getxattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct dentry *, const char *) removexattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t, int *) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(struct vfsmount *, struct dentry *, struct kstat *) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t, int *) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t, int *) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t, int *) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t, int *) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct user_namespace *, struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct user_namespace *, struct dentry *, struct iattr *) setattr;
    int (*)(struct user_namespace *, const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct user_namespace *, struct inode *, struct posix_acl *, int) set_acl;
    int (*)(struct user_namespace *, struct dentry *, struct fileattr *) fileattr_set;
    int (*)(struct dentry *, struct fileattr *) fileattr_get;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct user_namespace *, struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int, bool) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct user_namespace *, struct dentry *, struct iattr *) setattr;
    int (*)(struct user_namespace *, const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct user_namespace *, struct inode *, struct posix_acl *, int) set_acl;
    int (*)(struct user_namespace *, struct dentry *, struct fileattr *) fileattr_set;
    int (*)(struct dentry *, struct fileattr *) fileattr_get;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct user_namespace *, struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int, bool) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct user_namespace *, struct dentry *, struct iattr *) setattr;
    int (*)(struct user_namespace *, const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct user_namespace *, struct inode *, struct posix_acl *, int) set_acl;
    int (*)(struct user_namespace *, struct dentry *, struct fileattr *) fileattr_set;
    int (*)(struct dentry *, struct fileattr *) fileattr_get;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct user_namespace *, struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int, bool) get_inode_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct user_namespace *, struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct user_namespace *, struct dentry *, struct iattr *) setattr;
    int (*)(struct user_namespace *, const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct user_namespace *, struct inode *, struct file *, umode_t) tmpfile;
    struct posix_acl * (*)(struct user_namespace *, struct dentry *, int) get_acl;
    int (*)(struct user_namespace *, struct dentry *, struct posix_acl *, int) set_acl;
    int (*)(struct user_namespace *, struct dentry *, struct fileattr *) fileattr_set;
    int (*)(struct dentry *, struct fileattr *) fileattr_get;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct mnt_idmap *, struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int, bool) get_inode_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct mnt_idmap *, struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct mnt_idmap *, struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct mnt_idmap *, struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct mnt_idmap *, struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct mnt_idmap *, struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct mnt_idmap *, struct dentry *, struct iattr *) setattr;
    int (*)(struct mnt_idmap *, const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct mnt_idmap *, struct inode *, struct file *, umode_t) tmpfile;
    struct posix_acl * (*)(struct mnt_idmap *, struct dentry *, int) get_acl;
    int (*)(struct mnt_idmap *, struct dentry *, struct posix_acl *, int) set_acl;
    int (*)(struct mnt_idmap *, struct dentry *, struct fileattr *) fileattr_set;
    int (*)(struct dentry *, struct fileattr *) fileattr_get;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct mnt_idmap *, struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int, bool) get_inode_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct mnt_idmap *, struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct mnt_idmap *, struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct mnt_idmap *, struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct mnt_idmap *, struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct mnt_idmap *, struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct mnt_idmap *, struct dentry *, struct iattr *) setattr;
    int (*)(struct mnt_idmap *, const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct mnt_idmap *, struct inode *, struct file *, umode_t) tmpfile;
    struct posix_acl * (*)(struct mnt_idmap *, struct dentry *, int) get_acl;
    int (*)(struct mnt_idmap *, struct dentry *, struct posix_acl *, int) set_acl;
    int (*)(struct mnt_idmap *, struct dentry *, struct fileattr *) fileattr_set;
    int (*)(struct dentry *, struct fileattr *) fileattr_get;
    struct offset_ctx * (*)(struct inode *) get_offset_ctx;
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
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
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
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inode_operations {
    struct dentry * (*)(struct inode *, struct dentry *, unsigned int) lookup;
    const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link;
    int (*)(struct inode *, int) permission;
    struct posix_acl * (*)(struct inode *, int) get_acl;
    int (*)(struct dentry *, char *, int) readlink;
    int (*)(struct inode *, struct dentry *, umode_t, bool) create;
    int (*)(struct dentry *, struct inode *, struct dentry *) link;
    int (*)(struct inode *, struct dentry *) unlink;
    int (*)(struct inode *, struct dentry *, const char *) symlink;
    int (*)(struct inode *, struct dentry *, umode_t) mkdir;
    int (*)(struct inode *, struct dentry *) rmdir;
    int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod;
    int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename;
    int (*)(struct dentry *, struct iattr *) setattr;
    int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr;
    ssize_t (*)(struct dentry *, char *, size_t) listxattr;
    int (*)(struct inode *, struct fiemap_extent_info *, u64, u64) fiemap;
    int (*)(struct inode *, struct timespec64 *, int) update_time;
    int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open;
    int (*)(struct inode *, struct dentry *, umode_t) tmpfile;
    int (*)(struct inode *, struct posix_acl *, int) set_acl;
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
<code>const char * (*)(struct dentry *, struct inode *, struct delayed_call *) get_link</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * (*)(struct dentry *, void * *) follow_link</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct inode *, void *) put_link</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dentry *, const char *, const void *, size_t, int) setxattr</code> ➡️ <code>int (*)(struct dentry *, struct inode *, const char *, const void *, size_t, int) setxattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>ssize_t (*)(struct dentry *, const char *, void *, size_t) getxattr</code> ➡️ <code>ssize_t (*)(struct dentry *, struct inode *, const char *, void *, size_t) getxattr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename2</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dentry *, struct inode *, const char *, const void *, size_t, int) setxattr</code>
</li>
<li>
<b>Field removed. </b>
<code>ssize_t (*)(struct dentry *, struct inode *, const char *, void *, size_t) getxattr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dentry *, const char *) removexattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *) rename</code> ➡️ <code>int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename</code>
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
<code>int (*)(struct vfsmount *, struct dentry *, struct kstat *) getattr</code> ➡️ <code>int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr</code>
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
<code>int (*)(struct inode *, struct timespec *, int) update_time</code> ➡️ <code>int (*)(struct inode *, struct timespec64 *, int) update_time</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t, int *) atomic_open</code> ➡️ <code>int (*)(struct inode *, struct dentry *, struct file *, unsigned int, umode_t) atomic_open</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct user_namespace *, struct dentry *, struct fileattr *) fileattr_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dentry *, struct fileattr *) fileattr_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, int) permission</code> ➡️ <code>int (*)(struct user_namespace *, struct inode *, int) permission</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct dentry *, umode_t, bool) create</code> ➡️ <code>int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, bool) create</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct dentry *, const char *) symlink</code> ➡️ <code>int (*)(struct user_namespace *, struct inode *, struct dentry *, const char *) symlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct dentry *, umode_t) mkdir</code> ➡️ <code>int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) mkdir</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct dentry *, umode_t, dev_t) mknod</code> ➡️ <code>int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, dev_t) mknod</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename</code> ➡️ <code>int (*)(struct user_namespace *, struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dentry *, struct iattr *) setattr</code> ➡️ <code>int (*)(struct user_namespace *, struct dentry *, struct iattr *) setattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct path *, struct kstat *, u32, unsigned int) getattr</code> ➡️ <code>int (*)(struct user_namespace *, const struct path *, struct kstat *, u32, unsigned int) getattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct dentry *, umode_t) tmpfile</code> ➡️ <code>int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) tmpfile</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct posix_acl *, int) set_acl</code> ➡️ <code>int (*)(struct user_namespace *, struct inode *, struct posix_acl *, int) set_acl</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct posix_acl * (*)(struct inode *, int) get_acl</code> ➡️ <code>struct posix_acl * (*)(struct inode *, int, bool) get_acl</code>
</li>
</ul>
</details>
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
<code>struct posix_acl * (*)(struct inode *, int, bool) get_inode_acl</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct posix_acl * (*)(struct inode *, int, bool) get_acl</code> ➡️ <code>struct posix_acl * (*)(struct user_namespace *, struct dentry *, int) get_acl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) tmpfile</code> ➡️ <code>int (*)(struct user_namespace *, struct inode *, struct file *, umode_t) tmpfile</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct inode *, struct posix_acl *, int) set_acl</code> ➡️ <code>int (*)(struct user_namespace *, struct dentry *, struct posix_acl *, int) set_acl</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct inode *, int) permission</code> ➡️ <code>int (*)(struct mnt_idmap *, struct inode *, int) permission</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, bool) create</code> ➡️ <code>int (*)(struct mnt_idmap *, struct inode *, struct dentry *, umode_t, bool) create</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct inode *, struct dentry *, const char *) symlink</code> ➡️ <code>int (*)(struct mnt_idmap *, struct inode *, struct dentry *, const char *) symlink</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t) mkdir</code> ➡️ <code>int (*)(struct mnt_idmap *, struct inode *, struct dentry *, umode_t) mkdir</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct inode *, struct dentry *, umode_t, dev_t) mknod</code> ➡️ <code>int (*)(struct mnt_idmap *, struct inode *, struct dentry *, umode_t, dev_t) mknod</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename</code> ➡️ <code>int (*)(struct mnt_idmap *, struct inode *, struct dentry *, struct inode *, struct dentry *, unsigned int) rename</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct dentry *, struct iattr *) setattr</code> ➡️ <code>int (*)(struct mnt_idmap *, struct dentry *, struct iattr *) setattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, const struct path *, struct kstat *, u32, unsigned int) getattr</code> ➡️ <code>int (*)(struct mnt_idmap *, const struct path *, struct kstat *, u32, unsigned int) getattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct inode *, struct file *, umode_t) tmpfile</code> ➡️ <code>int (*)(struct mnt_idmap *, struct inode *, struct file *, umode_t) tmpfile</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct posix_acl * (*)(struct user_namespace *, struct dentry *, int) get_acl</code> ➡️ <code>struct posix_acl * (*)(struct mnt_idmap *, struct dentry *, int) get_acl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct dentry *, struct posix_acl *, int) set_acl</code> ➡️ <code>int (*)(struct mnt_idmap *, struct dentry *, struct posix_acl *, int) set_acl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct user_namespace *, struct dentry *, struct fileattr *) fileattr_set</code> ➡️ <code>int (*)(struct mnt_idmap *, struct dentry *, struct fileattr *) fileattr_set</code>
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
<code>struct offset_ctx * (*)(struct inode *) get_offset_ctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct timespec64 *, int) update_time</code> ➡️ <code>int (*)(struct inode *, int) update_time</code>
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
