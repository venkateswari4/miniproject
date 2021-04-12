#comments
all.exe:main.c  accept.c deposit.c display.c search.c withdraw.c 
	gcc main.c accept.c deposit.c display.c search.c withdraw.c -o all.exe

run:all.exe 
	all.exe

test.exe:testbank.c  accept.c deposit.c display.c search.c withdraw.c unity/unity.c 
	gcc -I unity testbank.c accept.c deposit.c display.c search.c withdraw.c unity/unity.c -o test.exe

test:test.exe
	test.exe

clean:
	rm -f *.exe