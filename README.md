# villoc2
Fork from villoc (https://github.com/wapiflapi/villoc) - Wapiflapi

I modified the tool to suit my needs in heap visualisation. The Trace format should display heap operations with this pattern :
```
<object type> operation(arg1, arg2, ..) = return
```

change the operations dictionnary if you need to add routines from other heap managers.

Supported heap managers
- Libc malloc/calloc/realloc/free
- Linux kernel kmalloc/kzalloc/kfree

