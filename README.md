# giaiphapdientu
giải pháp điện tử ITC

'''
Bước 1: Cài đặt các gói cần thiết
	> yum -y update
	> yum -y install yum-utils device-mapper-persistent-data lvm2
	

Bước 2: Thêm Docker stable repository
	> yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
	

Bước 3: Cài đặt Docker trên CentOS 7
	> yum -y install docker-ce
	

Bước 4: Khởi động docker
	> systemctl start docker
	> systemctl enable docker
	
'''