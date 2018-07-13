count_words: count_words.o lexer.o -ll
	gcc count_words.o lexer.o -ll -o count_words

count_words.o: count_words.c 
	gcc -c count_words.c

lexer.o: lexer.c
	gcc -c lexer.c

lexer.c: lexer.l
	flex -t lexer.l > lexer.c

