    execve("ARMimg_maker", ["ARMimg_maker", "U2W_Update.img"], 0x7eac5d5c /* 16 vars */) = 0
    open("/proc/self/exe", O_RDONLY)        = 4
    mmap2(NULL, 20432, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_ANONYMOUS, -1, 0) = 0x76f75000
    mmap2(0x76f75000, 17795, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_FIXED, 4, 0) = 0x76f75000
    cacheflush(0x76f78e04, 0x76f79fd0, 0)   = 0
    mprotect(0x76f78000, 8144, PROT_READ|PROT_EXEC) = 0
    readlink("/proc/self/exe", "ARMimg_maker", 4095) = 22
    cacheflush(0x7ed6732c, 0x7ed67460, 0)   = 0
    mmap2(0x10000, 98304, PROT_NONE, MAP_PRIVATE|MAP_FIXED|MAP_ANONYMOUS, -1, 0) = 0x10000
    mmap2(0x10000, 32012, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_FIXED|MAP_ANONYMOUS, -1, 0) = 0x10000
    cacheflush(0x10000, 0x10134, 0)         = 0
    mmap2(NULL, 13173, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_ANONYMOUS, -1, 0) = 0x76f71000
    open("/dev/hwaes", O_RDWR)              = 5
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x6, 0xc), 0x7ed67220) = 0
    close(5)                                = 0
    munmap(0x76f71000, 12149)               = 0
    cacheflush(0x10134, 0x17d0c, 0)         = 0
    cacheflush(0x17d0c, 0x17d14, 0)         = 0
    mprotect(0x10000, 32012, PROT_READ|PROT_EXEC) = 0
    mmap2(0x27000, 3688, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_FIXED|MAP_ANONYMOUS, -1, 0) = 0x27000
    cacheflush(0x27d0c, 0x27e68, 0)         = 0
    mprotect(0x27000, 3688, PROT_READ|PROT_WRITE) = 0
    brk(0x28000)                            = 0x12e4000
    open("/lib/ld-linux.so.3", O_RDONLY)    = 5
    read(5, "\177ELF\1\1\1\0\0\0\0\0\0\0\0\0\3\0(\0\1\0\0\0\340\n\0\0004\0\0\0|\t\2\0\2\2\0\0054\0 \0\6\0(\0\26\0\25\0\1\0\0p\370\355\1\0\370\355\1\0\370\355\1\0\220\0\0\0\220\0\0\0\4\0\0\0\4\0\0\0\1\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\210\356\1\0\210\356\1\0\5\0\0\0\0\0\1\0\1\0\0\0\210\374\1\0\210\374\2\0\210\374\2\0\370\v\0\0\314\f\0\0\6\0\0\0\0\0\1\0\2\0\0\0D\377\1\0D\377\2\0D\377\2\0\270\0\0\0\270\0\0\0\6\0\0\0\4\0\0\0Q\345td\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\6\0\0\0\20\0\0\0R\345td\210\374\1\0\210\374\2\0\210\374\2\0x\3\0\0x\3\0\0\4\0\0\0\1\0\0\0\21\0\0\0\35\0\0\0\3\0\0\0\0\0\0\0\31\0\0\0\17\0\0\0\23\0\0\0\6\0\0\0\10\0\0\0\4\0\0\0\0\0\0\0\0\0\0\0\22\0\0\0\n\0\0\0\7\0\0\0\t\0\0\0\21\0\0\0\20\0\0\0\v\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\25\0\0\0\32\0\0\0\33\0\0\0\0\0\0\0\5\0\0\0\34\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\f\0\0\0\0\0\0\0\0\0\0\0\24\0\0\0\0\0\0\0\27\0\0\0\r\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\26\0\0\0\30\0\0\0\0\0\0\0\16\0\0\0\0\0\0\0\21\0\0\0\3\0\0\0\10\0\0\0\10\0\0\0\0\4@\0= \0014\200\2 D\r\5\200\0\200\10K\0\300\n\20\20\200D\200\"\2\204L\0\0\0\0\0\3\0\0\0\5\0\0\0\6\0\0\0\0\0\0\0\10\0\0\0\v\0\0\0", 512) = 512
    mmap2(NULL, 200704, PROT_NONE, MAP_PRIVATE|MAP_ANONYMOUS, -1, 0) = 0x76f43000
    mmap2(0x76f43000, 126600, PROT_READ|PROT_EXEC, MAP_PRIVATE|MAP_FIXED, 5, 0) = 0x76f43000
    mmap2(0x76f72000, 6272, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_FIXED, 5, 0x1f000) = 0x76f72000
    close(5)                                = 0
    mmap2(NULL, 4096, PROT_READ, MAP_PRIVATE, 4, 0) = 0x76f42000
    close(4)                                = 0
    munmap(0x76f75000, 20432)               = 0
    brk(NULL)                               = 0x12e4000
    uname({sysname="Linux", nodename="sk_mainboard", ...}) = 0
    mmap2(NULL, 4096, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_ANONYMOUS, -1, 0) = 0x76f79000
    access("/etc/ld.so.preload", R_OK)      = -1 ENOENT (No such file or directory)
    open("/etc/ld.so.cache", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    open("/lib/tls/v7l/neon/vfp/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/tls/v7l/neon/vfp", 0x7ed67408) = -1 ENOENT (No such file or directory)
    open("/lib/tls/v7l/neon/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/tls/v7l/neon", 0x7ed67408) = -1 ENOENT (No such file or directory)
    open("/lib/tls/v7l/vfp/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/tls/v7l/vfp", 0x7ed67408)  = -1 ENOENT (No such file or directory)
    open("/lib/tls/v7l/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/tls/v7l", 0x7ed67408)      = -1 ENOENT (No such file or directory)
    open("/lib/tls/neon/vfp/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/tls/neon/vfp", 0x7ed67408) = -1 ENOENT (No such file or directory)
    open("/lib/tls/neon/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/tls/neon", 0x7ed67408)     = -1 ENOENT (No such file or directory)
    open("/lib/tls/vfp/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/tls/vfp", 0x7ed67408)      = -1 ENOENT (No such file or directory)
    open("/lib/tls/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/tls", 0x7ed67408)          = -1 ENOENT (No such file or directory)
    open("/lib/v7l/neon/vfp/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/v7l/neon/vfp", 0x7ed67408) = -1 ENOENT (No such file or directory)
    open("/lib/v7l/neon/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/v7l/neon", 0x7ed67408)     = -1 ENOENT (No such file or directory)
    open("/lib/v7l/vfp/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/v7l/vfp", 0x7ed67408)      = -1 ENOENT (No such file or directory)
    open("/lib/v7l/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/v7l", 0x7ed67408)          = -1 ENOENT (No such file or directory)
    open("/lib/neon/vfp/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/neon/vfp", 0x7ed67408)     = -1 ENOENT (No such file or directory)
    open("/lib/neon/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/neon", 0x7ed67408)         = -1 ENOENT (No such file or directory)
    open("/lib/vfp/libc.so.6", O_RDONLY|O_CLOEXEC) = -1 ENOENT (No such file or directory)
    stat64("/lib/vfp", 0x7ed67408)          = -1 ENOENT (No such file or directory)
    open("/lib/libc.so.6", O_RDONLY|O_CLOEXEC) = 4
    read(4, BINARY_DATA12) = 512
    fstat64(4, {st_mode=S_IFREG|0755, st_size=1251160, ...}) = 0
    mmap2(NULL, 1320320, PROT_READ|PROT_EXEC, MAP_PRIVATE|MAP_DENYWRITE, 4, 0) = 0x76dff000
    mprotect(0x76f2c000, 65536, PROT_NONE)  = 0
    mmap2(0x76f3c000, 12288, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_FIXED|MAP_DENYWRITE, 4, 0x12d000) = 0x76f3c000
    mmap2(0x76f3f000, 9600, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_FIXED|MAP_ANONYMOUS, -1, 0) = 0x76f3f000
    close(4)                                = 0
    mmap2(NULL, 4096, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_ANONYMOUS, -1, 0) = 0x76f78000
    set_tls(0x76f784c0)                     = 0
    mprotect(0x76f3c000, 8192, PROT_READ)   = 0
    mprotect(0x76f72000, 4096, PROT_READ)   = 0
    brk(NULL)                               = 0x12e4000
    brk(0x1305000)                          = 0x1305000
    open("U2W_Update.img", O_RDWR) = 4
    open("/dev/hwaes", O_RDWR)              = 5
    ioctl(5, _IOC(_IOC_WRITE, 0x62, 0, 0x24), 0x7ed67b94) = 0
    fstat64(4, {st_mode=S_IFREG|0777, st_size=7830754, ...}) = 0
    mmap2(NULL, 4096, PROT_READ|PROT_WRITE, MAP_PRIVATE|MAP_ANONYMOUS, -1, 0) = 0x76f77000
    _llseek(4, 0, [0], SEEK_SET)            = 0
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 0, [0], SEEK_SET)            = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 81920, [81920], SEEK_SET)    = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 163840, [163840], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 245760, [245760], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 327680, [327680], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 409600, [409600], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 491520, [491520], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 573440, [573440], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 655360, [655360], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 737280, [737280], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 819200, [819200], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 901120, [901120], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 983040, [983040], SEEK_SET)  = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1064960, [1064960], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1146880, [1146880], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1228800, [1228800], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1310720, [1310720], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1392640, [1392640], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1474560, [1474560], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1556480, [1556480], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1638400, [1638400], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1720320, [1720320], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1802240, [1802240], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1884160, [1884160], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 1966080, [1966080], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2048000, [2048000], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2129920, [2129920], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2211840, [2211840], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2293760, [2293760], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2375680, [2375680], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2457600, [2457600], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2539520, [2539520], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2621440, [2621440], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2703360, [2703360], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2785280, [2785280], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2867200, [2867200], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 2949120, [2949120], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3031040, [3031040], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3112960, [3112960], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3194880, [3194880], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3276800, [3276800], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3358720, [3358720], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3440640, [3440640], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3522560, [3522560], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3604480, [3604480], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3686400, [3686400], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3768320, [3768320], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3850240, [3850240], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 3932160, [3932160], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4014080, [4014080], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4096000, [4096000], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4177920, [4177920], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4259840, [4259840], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4341760, [4341760], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4423680, [4423680], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4505600, [4505600], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4587520, [4587520], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4669440, [4669440], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4751360, [4751360], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4833280, [4833280], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4915200, [4915200], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 4997120, [4997120], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5079040, [5079040], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5160960, [5160960], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5242880, [5242880], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5324800, [5324800], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5406720, [5406720], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5488640, [5488640], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5570560, [5570560], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5652480, [5652480], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5734400, [5734400], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5816320, [5816320], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5898240, [5898240], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 5980160, [5980160], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6062080, [6062080], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6144000, [6144000], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6225920, [6225920], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6307840, [6307840], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6389760, [6389760], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6471680, [6471680], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6553600, [6553600], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6635520, [6635520], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6717440, [6717440], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6799360, [6799360], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6881280, [6881280], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 6963200, [6963200], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 7045120, [7045120], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 7127040, [7127040], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 7208960, [7208960], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 7290880, [7290880], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 7372800, [7372800], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 7454720, [7454720], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 7536640, [7536640], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 7618560, [7618560], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 81920
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 7700480, [7700480], SEEK_SET) = 0
    write(4, BINARY_DATA, 81920) = 81920
    read(4, BINARY_DATA, 81920) = 48354
    read(4, BINARY_DATA, 32768)                      = 0
    ioctl(5, _IOC(_IOC_READ|_IOC_WRITE, 0x62, 0x1, 0xc), 0x7ed67bc4) = 0
    _llseek(4, 7782400, [7782400], SEEK_SET) = 0
    write(4, BINARY_DATA, 45056) = 45056
    rt_sigaction(SIGINT, {sa_handler=SIG_IGN, sa_mask=[], sa_flags=SA_RESTORER, sa_restorer=0x76e2c660}, {sa_handler=SIG_IGN, sa_mask=[], sa_flags=0}, 8) = 0
    rt_sigaction(SIGQUIT, {sa_handler=SIG_IGN, sa_mask=[], sa_flags=SA_RESTORER, sa_restorer=0x76e2c660}, {sa_handler=SIG_IGN, sa_mask=[], sa_flags=0}, 8) = 0
    rt_sigprocmask(SIG_BLOCK, [CHLD], [], 8) = 0
    clone(child_stack=NULL, flags=CLONE_PARENT_SETTID|SIGCHLD, parent_tid=[1922]) = 1922
    wait4(1922, [{WIFEXITED(s) && WEXITSTATUS(s) == 0}], 0, NULL) = 1922
    rt_sigaction(SIGINT, {sa_handler=SIG_IGN, sa_mask=[], sa_flags=SA_RESTORER, sa_restorer=0x76e2c660}, NULL, 8) = 0
    rt_sigaction(SIGQUIT, {sa_handler=SIG_IGN, sa_mask=[], sa_flags=SA_RESTORER, sa_restorer=0x76e2c660}, NULL, 8) = 0
    rt_sigprocmask(SIG_SETMASK, [], NULL, 8) = 0
    --- SIGCHLD {si_signo=SIGCHLD, si_code=CLD_EXITED, si_pid=1922, si_uid=0, si_status=0, si_utime=0, si_stime=0} ---
    write(4, BINARY_DATA, 3298) = 3298
    close(4)                                = 0
    munmap(0x76f77000, 4096)                = 0
    close(5)                                = 0
    exit_group(0)                           = ?
    +++ exited with 0 +++