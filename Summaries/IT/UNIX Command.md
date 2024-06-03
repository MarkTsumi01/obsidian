
What is Unix ?

	Unix is a powerful, multiuser, multitasking operating system originally developed in the 1970s at AT&T's Bell Labs. It is widely known for its portability, stability, and security, and it has influenced many other operating systems, including Linux and macOS. Unix provides a range of tools and utilities for efficient file management, process control, and system administration, and it uses a command-line interface (CLI) for user interaction. Key features include a hierarchical file system, support for multiple users and processes, and a variety of scripting and programming capabilities.


Unix Command

	โครงสร้าง <command> <flag> <input> <output>

	cat : ใช้สำหรับโชว์หรือดูไฟล์ | flag ( -n ) | cat text.txt 

	grep : ใช้สำหรับหาไฟล์หรือสิ่งที่ต้องการจะหา | flah ( -E (regex), -i (ingore), -c ) | grep "Hello world" cat.txt
		grep -E "(Hello World!|Hello Dan) cat.txt"

	head : ใช้สำหรับโชว์จากด้านบนระบุจำนวนได้ | flag (-n 1) | head -n 1 cat.txt

	tail : ใช้สำหรับโชว์จากด้านล่างระบุจำนวนได้ | flag (-n 1) | tail -n 1 cat.txt

	cut  : ใช้สำหรับโชว์ข้อมูลเฉพาะส่วนจาก table | cut -d'|' -f2,3,4 example.txt

	uniq : ใช้สำหรับแสดงโดยไม่แสดงค่าที่ซ้ำ | flag ( -c, -d, -u ) | uniq example.txt

	sort : ใช้สำหรับเรียง | flag ( -n )

	sed : ใช้สำหรับเขียนทับแต่ไม่ได้เซฟ | flag (-E) | sed -E 's/New.*/Los Angelis/' example.txt

	pipeline : ใช้สำหรับการดำเนินการหลายคำสั่งพร้อมกัน | mkdir test | touch example.txt 

	cd : ใช้สำหรับเปลี่ยนโฟล์เดอร์ : cd unix

	ls : ใช้สำหรับโชว์ : flag ( -a , -la, -alh) : ls -a

	cp : ใช้สำหรับการก็อปปี้หรือสร้างไฟล์ใหม่ : cp ex1.txt ext2.txt

	mkdir : ใช้สำหรับสร้าง directory : mkdir project

	chmod : ใช้ในการกำหนดสิทธิ์ของ directory หรือไฟล์นั้นๆ

	pwd : ใช้สำหรับโชว์ว่าเราทำอะไรอยู่ตรงไหน

	rm : ใช้สำหรับการลบไฟล์ : flag (-r ,-rf) : rm example.txt

	touch : ใช้สำหรับสร้างไฟล์ : touch example.txt