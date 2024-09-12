```ini
[ citrizon 2024-09-12 05:44:40 AM ] Testing... Is this working??
[ citrizon 2024-09-12 05:45:10 AM ] Oh hello there! I am Botaro Shinomiya!
[ citrizon 2024-09-12 05:45:20 AM ] And... yeah this is my GitHub Profile for now.
[ citrizon 2024-09-12 05:45:26 AM ] Have fun around here ig haha :3
[ citrizon 2024-09-12 05:45:32 AM ] I will now end connection. 
panic@cpu0/thread=ffffff0149e64b00
ffffff00045d8290 trace:dtrace_action_panic+77 ()
ffffff00045d8450 trace:dtrace-probe+6f9 ()
ffffff00045d84f0 dtracedtrace_state_ _go +36b ()
ffffff00045d8d00 trace:dtrace_ _ioct1+74d () ffffff00045d8d40 genunix:cdev_ioctI+45()
ffffff00045d8d80 specfs:spec_ioctl+5a () ffffff00045d8e00 genunix:fop_ioctl+7b ()
ffffff00045d8f00 genunix:ioctl+18e ()
ffffff00045d8f10 unix:brand_sys_syscall+20d ()
```
