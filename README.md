# ListPIDs - Operating Systems project
  Added a syscall in OpenBSD's kernel in order to print informations about a given process and its children<br/>
  The syscall's header is defined in /kern/syscalls.master and  it's body in the /kern/sys_generic.c<br/>
  Used LIST_FOREACH which is a macro in OpenBSD that traverses a specific list
## Contents
- syscalls.master and sys_generic.c files
- user.c file that test the syscall's functionality
