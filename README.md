docker build . -t otp-app


docker run --privileged  -ti -e container=docker  -v /sys/fs/cgroup:/sys/fs/cgroup  otp-app /usr/sbin/init
