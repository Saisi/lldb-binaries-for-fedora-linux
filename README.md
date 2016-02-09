Prebuilt LLDB binaries for 64-bit Fedora Linux

	How to setup binaries
	-----------------------------
	Extract bin.tar.gz to get bin/
	In your .bashrc
		Add bin/ location to $PATH
		Add bin/lib/lib64/python2.7/site-packages/ to your PYTHONPATH
		Add bin/lib to LD_LIBRARY_PATH

	Entries in .bashrc for bin.tar.gz  extracted to ~/bin: 
	export PATH=$PATH:~/bin:~/bin/lib
	export LD_LIBRARY_PATH=~/bin/lib
	export PYTHONPATH=$PYTHONPATH:~/bin/lib/lib64/python2.7/site-packages/
	
	After which, you should be able to invoke lldb seamlessly
