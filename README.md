Exercise Framework
=================

To deploy/run this framework

1. Install python(2.7*)
2. source env_init
	if you are using MAC machine, you may get following error
		gevent/libevent.h:9:19: error: event.h: No such file or directory
	Run 'brew install libevent'
		then 'CFLAGS="-I /opt/local/include -L /opt/local/lib" pip install gevent'
			(source http://stackoverflow.com/questions/7630388/how-can-i-install-the-python-library-gevent-on-mac-os-x-lion)
3. python __init__.py
