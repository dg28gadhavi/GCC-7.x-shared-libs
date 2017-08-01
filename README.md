# GCC-7.x-shared-libs

sudo su -
cp libfl.so.2.0.0 /usr/lib/
chmod 755 /usr/lib/libfl.so.2.0.0
ln -s /usr/lib/libfl.so.2.0.0 /usr/lib/libfl.so
ln -s /usr/lib/libfl.so.2.0.0 /usr/lib/libfl.so.2
cp libfl.so.2.0.0 /usr/lib/x86_64-linux-gnu/
exit
