# Struct: <code>nfs_rpc_ops</code>

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
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, const struct qstr *) remove;
    void (*)(struct rpc_message *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct inode *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, struct rpc_cred *, u64, struct page * *, unsigned int, int) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, int) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    int (*)(struct inode *) return_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, const struct qstr *) remove;
    void (*)(struct rpc_message *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct inode *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, struct rpc_cred *, u64, struct page * *, unsigned int, int) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, int) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    int (*)(struct inode *) return_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, const struct qstr *) remove;
    void (*)(struct rpc_message *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct inode *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, struct rpc_cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    int (*)(struct inode *) return_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, const struct qstr *) remove;
    void (*)(struct rpc_message *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct inode *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, struct rpc_cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    int (*)(struct inode *) return_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, struct rpc_cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    int (*)(struct fs_context *, struct nfs_server *) submount;
    int (*)(struct fs_context *) try_get_tree;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, struct dentry *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct nfs_readdir_arg *, struct nfs_readdir_res *) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct fs_context *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    int (*)(struct fs_context *, struct nfs_server *) submount;
    int (*)(struct fs_context *) try_get_tree;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, struct dentry *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct nfs_readdir_arg *, struct nfs_readdir_res *) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct fs_context *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
    int (*)(struct nfs_server *, struct nfs_fh *) discover_trunking;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    int (*)(struct fs_context *, struct nfs_server *) submount;
    int (*)(struct fs_context *) try_get_tree;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *, const struct cred *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct nfs_readdir_arg *, struct nfs_readdir_res *) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct fs_context *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
    int (*)(struct nfs_server *, struct nfs_fh *) discover_trunking;
    void (*)(struct inode *) enable_swap;
    void (*)(struct inode *) disable_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    int (*)(struct fs_context *, struct nfs_server *) submount;
    int (*)(struct fs_context *) try_get_tree;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *, const struct cred *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct nfs_readdir_arg *, struct nfs_readdir_res *) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct fs_context *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
    int (*)(struct nfs_server *, struct nfs_fh *) discover_trunking;
    void (*)(struct inode *) enable_swap;
    void (*)(struct inode *) disable_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    int (*)(struct fs_context *, struct nfs_server *) submount;
    int (*)(struct fs_context *) try_get_tree;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *, const struct cred *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct nfs_readdir_arg *, struct nfs_readdir_res *) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct fs_context *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
    int (*)(struct nfs_server *, struct nfs_fh *) discover_trunking;
    void (*)(struct inode *) enable_swap;
    void (*)(struct inode *) disable_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    int (*)(struct fs_context *, struct nfs_server *) submount;
    int (*)(struct fs_context *) try_get_tree;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *, const struct cred *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct folio *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct nfs_readdir_arg *, struct nfs_readdir_res *) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct fs_context *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
    int (*)(struct nfs_server *, struct nfs_fh *) discover_trunking;
    void (*)(struct inode *) enable_swap;
    void (*)(struct inode *) disable_swap;
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
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
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
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
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
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, const struct qstr *) remove;
    void (*)(struct rpc_message *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct inode *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, struct rpc_cred *, u64, struct page * *, unsigned int, int) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, int) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    int (*)(struct inode *) return_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
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
<code>const struct nlmclnt_operations * nlmclnt_ops</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dentry *, struct rpc_cred *, u64, struct page * *, unsigned int, int) readdir</code> ➡️ <code>int (*)(struct dentry *, struct rpc_cred *, u64, struct page * *, unsigned int, bool) readdir</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct xdr_stream *, struct nfs_entry *, int) decode_dirent</code> ➡️ <code>int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent</code>
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
<b>Field removed. </b>
<code>int (*)(struct inode *) return_delegation</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) getattr</code> ➡️ <code>int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, const struct qstr *) remove</code> ➡️ <code>int (*)(struct inode *, struct dentry *) remove</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct rpc_message *, struct inode *) unlink_setup</code> ➡️ <code>void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct rpc_message *, struct inode *) rename_setup</code> ➡️ <code>void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct nfs_pgio_header *, struct rpc_message *) write_setup</code> ➡️ <code>void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct nfs_commit_data *, struct rpc_message *) commit_setup</code> ➡️ <code>void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup</code>
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
<code>int (*)(struct dentry *, struct rpc_cred *, u64, struct page * *, unsigned int, bool) readdir</code> ➡️ <code>int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    struct vfsmount * (*)(struct nfs_server *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) submount;
    struct dentry * (*)(int, const char *, struct nfs_mount_info *, struct nfs_subversion *) try_mount;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, const struct qstr *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct dentry *, const struct cred *, u64, struct page * *, unsigned int, bool) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct nfs_mount_info *, struct nfs_subversion *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct nfs_rpc_ops {
    u32 version;
    const struct dentry_operations * dentry_ops;
    const struct inode_operations * dir_inode_ops;
    const struct inode_operations * file_inode_ops;
    const struct file_operations * file_ops;
    const struct nlmclnt_operations * nlmclnt_ops;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) getroot;
    int (*)(struct fs_context *, struct nfs_server *) submount;
    int (*)(struct fs_context *) try_get_tree;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr;
    int (*)(struct dentry *, struct nfs_fattr *, struct iattr *) setattr;
    int (*)(struct inode *, struct dentry *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup;
    int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp;
    int (*)(struct inode *, struct nfs_access_entry *) access;
    int (*)(struct inode *, struct page *, unsigned int, unsigned int) readlink;
    int (*)(struct inode *, struct dentry *, struct iattr *, int) create;
    int (*)(struct inode *, struct dentry *) remove;
    void (*)(struct rpc_message *, struct dentry *, struct inode *) unlink_setup;
    void (*)(struct rpc_task *, struct nfs_unlinkdata *) unlink_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *) unlink_done;
    void (*)(struct rpc_message *, struct dentry *, struct dentry *) rename_setup;
    void (*)(struct rpc_task *, struct nfs_renamedata *) rename_rpc_prepare;
    int (*)(struct rpc_task *, struct inode *, struct inode *) rename_done;
    int (*)(struct inode *, struct inode *, const struct qstr *) link;
    int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink;
    int (*)(struct inode *, struct dentry *, struct iattr *) mkdir;
    int (*)(struct inode *, const struct qstr *) rmdir;
    int (*)(struct nfs_readdir_arg *, struct nfs_readdir_res *) readdir;
    int (*)(struct inode *, struct dentry *, struct iattr *, dev_t) mknod;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsstat *) statfs;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fsinfo *) fsinfo;
    int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_pathconf *) pathconf;
    int (*)(struct nfs_server *, struct nfs_fh *) set_capabilities;
    int (*)(struct xdr_stream *, struct nfs_entry *, bool) decode_dirent;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) pgio_rpc_prepare;
    void (*)(struct nfs_pgio_header *, struct rpc_message *) read_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) read_done;
    void (*)(struct nfs_pgio_header *, struct rpc_message *, struct rpc_clnt * *) write_setup;
    int (*)(struct rpc_task *, struct nfs_pgio_header *) write_done;
    void (*)(struct nfs_commit_data *, struct rpc_message *, struct rpc_clnt * *) commit_setup;
    void (*)(struct rpc_task *, struct nfs_commit_data *) commit_rpc_prepare;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done;
    int (*)(struct file *, int, struct file_lock *) lock;
    int (*)(const struct file_lock *) lock_check_bounds;
    void (*)(struct inode *) clear_acl_cache;
    void (*)(struct nfs_open_context *, int) close_context;
    struct inode * (*)(struct inode *, struct nfs_open_context *, int, struct iattr *, int *) open_context;
    int (*)(struct inode *, fmode_t) have_delegation;
    struct nfs_client * (*)(const struct nfs_client_initdata *) alloc_client;
    struct nfs_client * (*)(struct nfs_client *, const struct nfs_client_initdata *) init_client;
    void (*)(struct nfs_client *) free_client;
    struct nfs_server * (*)(struct fs_context *) create_server;
    struct nfs_server * (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, rpc_authflavor_t) clone_server;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct nfs_server *, struct nfs_fh *) discover_trunking</code>
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
<code>void (*)(struct inode *) enable_swap</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct inode *) disable_swap</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *, struct inode *) getattr</code> ➡️ <code>int (*)(struct nfs_server *, struct nfs_fh *, struct nfs_fattr *, struct inode *) getattr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct dentry *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookup</code> ➡️ <code>int (*)(struct inode *, struct dentry *, struct nfs_fh *, struct nfs_fattr *) lookup</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *, struct nfs4_label *) lookupp</code> ➡️ <code>int (*)(struct inode *, struct nfs_fh *, struct nfs_fattr *) lookupp</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct nfs_access_entry *) access</code> ➡️ <code>int (*)(struct inode *, struct nfs_access_entry *, const struct cred *) access</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, struct dentry *, struct page *, unsigned int, struct iattr *) symlink</code> ➡️ <code>int (*)(struct inode *, struct dentry *, struct folio *, unsigned int, struct iattr *) symlink</code>
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
