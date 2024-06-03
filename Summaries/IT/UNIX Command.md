
What is Unix ?

	Unix is a powerful, multiuser, multitasking operating system originally developed in the 1970s at AT&T's Bell Labs. It is widely known for its portability, stability, and security, and it has influenced many other operating systems, including Linux and macOS. Unix provides a range of tools and utilities for efficient file management, process control, and system administration, and it uses a command-line interface (CLI) for user interaction. Key features include a hierarchical file system, support for multiple users and processes, and a variety of scripting and programming capabilities.


Unix Command

	โครงสร้าง <command> <flag> <input> <output>

	cat : ใช้สำหรับโชว์หรือดูไฟล์ | flag (-n) | cat text.txt 

	grep : ใช้สำหรับหาไฟล์หรือสิ่งที่ต้องการจะหา | flah ( -E (regex), -i (ingore), -c ) | grep "Hello world" cat.txt
		grep -E "(Hello World!|Hello Dan) cat.txt"

	head : ใช้สำหรับโชว์จากด้านบนระบุจำนวนได้ | flag (-n 1) | head -n 1 cat.txt

	tail : ใช้สำหรับโชว์จากด้านล่างระบุจำนวนได้ | flag (-n 1) | tail -n 1 cat.txt

	