# Wifi

sudo zypper addrepo https://download.opensuse.org/repositories/home:/Sauerland/openSUSE_Leap_15.3/
zypper ref
zypper --no-refresh in rtl8822bu-kmp-default
modprobe rtl8822bu
