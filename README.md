Ubuntu 24.04 , 22.04, 20.04 and 18.04 with systemd, sshd, docker and docker compose. Full upgraded 24.06.2025(latest)
=========================
and
=========================
Debian 12, 11 and 10 with systemd, sshd, docker and docker compose. Full upgraded 24.06.2025(latest)
=========================
![systemd-ubuntu-24 04](https://github.com/user-attachments/assets/893be3c8-ed97-4d20-8879-92c4484b81e1)
Quick Start
=========================
Run the following to get started.
=========================
Ubuntu
=========================
docker run -d -p 2222:22 --name systemd-ubuntu-24.04 --privileged -v /sys/fs/cgroup:/sys/fs/cgroup:rw --cgroupns=host systemd25/systemd-ubuntu-24.04:latest
=========================
User:root
=========================
Password:SystemD123
=========================
=========================
=========================
Ubuntu:
=========================
docker run -d -p 2222:22 --name systemd-ubuntu-24.04 --privileged -v /sys/fs/cgroup:/sys/fs/cgroup:rw --cgroupns=host systemd25/systemd-ubuntu-22.04:latest
=========================
docker run -d -p 2222:22 --name systemd-ubuntu-24.04 --privileged -v /sys/fs/cgroup:/sys/fs/cgroup:rw --cgroupns=host systemd25/systemd-ubuntu-20.04:latest
=========================
docker run -d -p 2222:22 --name systemd-ubuntu-24.04 --privileged -v /sys/fs/cgroup:/sys/fs/cgroup:rw --cgroupns=host systemd25/systemd-ubuntu-18.04:latest
=========================
Debian:
=========================
docker run -d -p 2222:22 --name systemd-ubuntu-24.04 --privileged -v /sys/fs/cgroup:/sys/fs/cgroup:rw --cgroupns=host systemd25/systemd-debian-12:latest
=========================
docker run -d -p 2222:22 --name systemd-ubuntu-24.04 --privileged -v /sys/fs/cgroup:/sys/fs/cgroup:rw --cgroupns=host systemd25/systemd-debian-11:latest
=========================
sdocker run -d -p 2222:22 --name systemd-ubuntu-24.04 --privileged -v /sys/fs/cgroup:/sys/fs/cgroup:rw --cgroupns=host ystemd25/systemd-debian-10:latest
=========================
![systemd-ubuntu-22 04](https://github.com/user-attachments/assets/79a04fd3-43e5-4e36-ada5-5a389bc5aeec)
![systemd-ubuntu-20 04](https://github.com/user-attachments/assets/6e1c9d57-7dda-4d82-b8bc-649bcb777d6d)
![systemd-ubuntu-18 04](https://github.com/user-attachments/assets/e6de923a-48e5-40d9-a100-400c70277c47)
![systemd-debian-12](https://github.com/user-attachments/assets/5d79edb8-6d52-44f9-936a-0723147497b0)
![systemd-debian-11](https://github.com/user-attachments/assets/3304431a-f5d8-439c-8c38-469e281c044a)
![systemd-debian-10](https://github.com/user-attachments/assets/0f9ec830-bfe2-446f-bd4c-8b6a1a8fb9a2)
=========================
