## Commands and file system
    Linux
	Kernel이란
		set of functions
	man
		manual이다
		man man
	> cd
		cd .   current directory를 뜻한다
	pushd
		saves current directory 해준다
	mv 옮기는 명령어
	ls
		ls -rlt  뒤에서부터 최근꺼롤  table과 time으로
		ls -l data   data폴더를 보여준다
	cp
		cp /etc/passwd ~/sample  복사해준다 home direcotry의 sample를 만들어준다
	rm
		-r 
			recursively
		-f
			never prompt
			
		-i
			prompt한다 
		rm data sample 
			이렇게 2개 지울수있다.
	Name pattern matching
		rm *
			all
		rm directory/*
			all in directory
	more 
		display files on screen page by page
	cat
		-n
			number lines
		cat > a.txt  하고 무언가를 입력하면 파일이 생긴다
		cat sample sample sample > big-sample
			3배가 되고 사이즈도 바뀐다
		sort big-sample > sorted-sample    sort 된 example이 나온다.
	Pipe and redirection
		ls -l | more
	exit
	grep
		print lines matching a pattern
		-i
			ignore case
		-n
			print line number
		m[ya]
			my or ma 
	ps
		current process
		r
			only running process
	pstree
		a tree of processes
	top
		Display Linux tasks
	kill
		kill -9
			9 means process
		kill -9 100
			kill process 100
				100 is pid
		kill -9 -1
			m
	tar
		path
			compress files and directories
		tar cvf name.tar directory
		
	df 
		report file system disk space usage
	du
		file space usage
	sudo
		sudo -u other-user 
			invoke shell with user other-user
		sudo /bin/bash 
			invoke superuser’s shell
	chown
		changes owner,permission of files and direct
			
		chown owner group file
			
		mRWXRWXRWX
			user group others 을 각각 뜻한다
			m은 type
	hostname
		name of this computer
	uname
		
	ifconfig
		network interface
	netstat
		network connections
		-l -t
			only listening sockets , -t tcp
		-i
			interface statistic
	cat /etc/hosts/
		stores hostname and ip-address
		/etc/resolv.conf
		/services/
	etc/profile
		global proflie
	which
		whereis 
			는source page file
		which는 execution file
	usr
		data for users
	etc
		configuration file
	dev
		hardware device 
	File Link
		ln my file myfile-link
		ln -s myfile myfile-sym-link
			a link file with the target file name in it
	attribute
		0
		user
			7
		group
			5
		other
			4
	vi
		x
			deleting
		i
			input mode
		yy
			paste
		yw
			copy word
		Configuraton
			여러가지 configuration이 있다.
>
